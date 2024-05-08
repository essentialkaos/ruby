<p align="center"><a href="#readme"><img src="https://gh.kaos.st/ruby.svg"/></a></p>

<p align="center">
  <a href="https://kaos.sh/w/ruby/cd"><img src="https://kaos.sh/w/ruby/cd.svg" alt="GitHub Actions CD Status" /></a>
  <a href="#license"><img src="https://gh.kaos.st/apache2.svg"></a>
</p>

<p align="center"><a href="#versions">Versions</a> • <a href="#contributing">Contributing</a> • <a href="#license">License</a></p>

<br/>

This repository contains workflow for the automatic Ruby images building using [rbinstall](https://kaos.sh/rbinstall).

### Versions

| Base    | Jemalloc         | JRuby           |
|---------|------------------|-----------------|
| `2.7.7` | `2.7.7-jemalloc` | `jruby-9.3.9.0` |
| `2.7.8` | `2.7.8-jemalloc` | `jruby-9.3.10.0` |
| `3.0.5` | `3.0.5-jemalloc` | `jruby-9.4.0.0` |
| `3.0.6` | `3.0.6-jemalloc` | `jruby-9.4.1.0` |
| `3.1.3` | `3.1.3-jemalloc` | `jruby-9.4.2.0` |
| `3.1.4` | `3.1.4-jemalloc` | `jruby-9.4.3.0` |
| `3.2.0` | `3.2.0-jemalloc` | `jruby-9.4.4.0` |
| `3.2.1` | `3.2.1-jemalloc` | `jruby-9.4.5.0` |
| `3.2.2` | `3.2.2-jemalloc` | |
| `3.2.3` | `3.2.3-jemalloc` | |
| `3.2.4` | `3.2.4-jemalloc` | |
| `3.3.0` | `3.3.0-jemalloc` | |
| `3.3.1` | `3.3.1-jemalloc` | |

Usage exmplates:

Pull image from DockerHub:

```bash
docker pull essentialkaos/ruby:3.3.0-jemalloc
```

Pull image from GitHub Container Registry:

```bash
docker pull ghcr.io/essentialkaos/ruby:jruby-9.4.5.0
```

### Contributing

Before contributing to this project please read our [Contributing Guidelines](https://github.com/essentialkaos/contributing-guidelines#contributing-guidelines).

### License

[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)

<p align="center"><a href="https://essentialkaos.com"><img src="https://gh.kaos.st/ekgh.svg"/></a></p>
