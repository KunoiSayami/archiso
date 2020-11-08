To build iso:

```
mkarchiso -v -w /tmp/archiso-tmp -g <YOUR_GPG_KEY_ID_HERE> -o build/ .
```

This iso will run sshd automatically, login with ssh key `id_ed25519_archiso` in project root
