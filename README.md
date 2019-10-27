### Camaleon-CMS
---
http://camaleon.tuzitio.com/

https://github.com/owen2345/camaleon-cms

```rb
// spec/mailers/send_mail_spec.rb

describe "CamaleonCms::HtmlMailer" do
  before(:each) do
    @site = creat(:site).decorate
  end
  describe 'empty content' do
    let(:mail) { CamalonCms::HtmlMailer.sender('test@gmail.com', "test") }
    
    it 'renders the subject' do
      expect(mail.subject).to eql('test')
    end
    
    it 'renders the reciever email' do
      expect(mail.to).to eql(['test@gmail.com'])
    end
    
    
  end
  
end

```

```
```

```
```


