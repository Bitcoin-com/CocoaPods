# Bitcoin.com CocoaPods

Interact with this repo
```bash
# Add the repo
pod repo add BitcoinComCocoaPods https://github.com/Bitcoin-com/CocoaPods.git

# Update the repo
pod repo push BitcoinComCocoaPods SLPWallet.podspec --allow-warnings
pod repo push BitcoinComCocoaPods BitcoinKit.podspec --allow-warnings
```

Add the repo in your Podfile
```ruby
source 'https://github.com/Bitcoin-com/CocoaPods.git'
source 'https://github.com/CocoaPods/Specs.git'

target '..' do 
# ...
end
```
