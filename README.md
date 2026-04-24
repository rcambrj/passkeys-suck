# Passkeys suck

This is the code for [passkeys-suck.com](https://passkeys-suck.com).

## Why do passkeys suck?

1. **Nobody knows what they are.** The average user can't tell you what a passkey is, whereas even an eight-year-old understands passwords. When a browser prompts "Save a passkey?", nobody knows what they're agreeing to — or where it's being saved. Customer support don't know either.

2. **Lose your device, lose your accounts.** Passkeys are bound to an authenticator. There's no "forgot password" flow. Drop your phone in a lake and you're locked out — permanently. Sync features (iCloud Keychain, Google Password Manager) are unreliable, optional, and most users don't even know they exist.

3. **You don't own your credentials.** Apple passkeys live in iCloud Keychain. Chrome passkeys live in Google Password Manager. 1Password and Lastpass don't allow exporting passkeys. The passkey standard doesn't mandate portability, so moving between ecosystems is painful or impossible, and most users don't even know which one they're using. 

4. **Sometimes they're mandatory.** Some websites _require_ passkeys to sign in, in addition to or instead of a password, and you won't know until it's too late. If you created your passkey on your phone and try to log in on your laptop, you might be out of luck.

5. **They don't work for everyone.** Shared computers, kiosks, and multi-user devices don't play well with passkeys. A library terminal, a family computer, a friend's borrowed laptop — passkeys assume one person per device, which is not how the real world works.