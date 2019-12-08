# Kali Linux / Docker

Using Kali Linux for Penetration Testing & Security Training on Docker

## Getting Started

From [Official Kali Linux Docker Image](https://registry.hub.docker.com/r/kalilinux/kali-linux-docker) + python htop net-tools openssl nmap metasploit-framework

### Usage / Container Parameters

#### Pull

```shell
docker pull estebanrfp/kl
```

#### Run

```shell
docker run -h "kl" --name kl --privileged -t -i estebanrfp/kl /bin/bash
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.