# Docker Jenkins

This compose file allows to bootstrap an instance of the latest
Jenkins [Docker image](https://hub.docker.com/_/jenkins/) mounting a persistent data storage within the working directory of the host machine.

```

/var/jenkins_home is mounted under ${PWD}/jenkins

```

## Installation

docker-compose up -d

### Requirements

Docker Version >= 1.12.2

### Setup

git clone git@github.com:p0bailey/docker-jenkins.git

## Usage

docker-compose up -d

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

16 Oct 2016 - 1.0

## Author

Phillip Bailey - <phillip@bailey.st>

## License

MIT License
