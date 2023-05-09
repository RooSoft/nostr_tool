## key converter
https://damus.io/key/

## jack's profile
cat 5-jacks_profile.json | websocat wss://relay.damus.io | jq ".[2].content | fromjson | ."

## CLI QR code
qrencode -t ansiutf8 nostr:npub1x470syrpdkyfw0m64nzjrmfyrk5ths4yx9ghj7g27m0x7sa68deq2jz4xc
