# duckduckgo-mail-ios-shortcuts

## Shortcuts
https://www.icloud.com/shortcuts/3a20ed932f3a4fb9a2939df923774990

## Get Bearer Token (Chrome Desktop)
1. Install [DuckDuckGo Chrome extension](https://chrome.google.com/webstore/detail/duckduckgo-privacy-essent/bkdgflcldnnnapblkhphbgpggdiikppg)
2. Enable Email Protection https://duckduckgo.com/email/enable-autofill
3. Right Click DuckDuckGo extension icon -> "Manage Extensions" -> "Inspect views background page"   
or    
just Inspect chrome-extension://bkdgflcldnnnapblkhphbgpggdiikppg/_generated_background_page.html
5. DevTools -> Network Tab
6. Click "Create New Duck Address" and you'll see an "address" request, in the "Request Headers" the "authorization: Bearer zkuxxxxxxxxxxxxx" is your token
7. Paste Bearer zkuxxxxxxxxxxxxx to your Shortcuts

https://www.youtube.com/watch?v=rOtUIkQoKL0
