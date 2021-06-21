# libssh2

**libssh2** is a client-side C library implementing the SSH2 protocol.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/libssh2
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y libssh2
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/libssh2).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/libssh2) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.
