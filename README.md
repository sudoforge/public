# bddenhartog/public

A collection of my public SSH and GPG keys.

I mostly use this to easily delegate access to new nodes, or provide my
information to those who need it.

# Vanity URLs

The following vanity URLs have been created for the resources in this repository:

| Short URL | File |
| --------- | ---- |
| git.io/bddenhartog.ssh | [ssh/code-1]() |
| git.io/bddenhartog.gpg | [gpg/C87073923F4C2CB44B0AA5EB62202C845DF563B5]() |

## Usage

Read below for usage instructions. V

### Adding my public ssh key to your authorized keys file

```
curl -Ls git.io/bddenhartog.ssh >> ~/.ssh/authorized_keys
```

### Comparing my GPG public key to one in your keyring

```
diff <(gpg --export --armor {email-or-key-id}) <(curl -s git.io/bddenhartog.gpg)
```
