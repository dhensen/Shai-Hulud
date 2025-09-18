# Shai-Hulud

I'm not hacked (yet) ;)

I noticed in the shai hulud hack summary that their payload will create a repo with this name and in their code was no exception handling.
So I decided to pre-create this repo.. just in case.. until they make their payload smarter.

You can read more about the hack here:

https://jfrog.com/blog/shai-hulud-npm-supply-chain-attack-new-compromised-packages-detected/

## What to do?

It's time to step up your developer security:

- 2FA everywhere
- Rotate passwords often
- Stop storing secrets in environment variables, use a secret vault
- Stop storing secrets in `.env` files, use your platform’s secret manager
- Audit and pin your dependencies, don’t just trust the latest version
- Add automated vulnerability scanning to your CI/CD
- Practice “least privilege” for tokens and API keys
- Keep your team aware of current supply chain threats

Stay paranoid. Stay safe. 🛡️

### Msg to the hackers:

![alt text](./davec.gif "Title")
