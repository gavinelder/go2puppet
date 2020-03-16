# go2puppet

## About

The following is a MVP inspired by [bakeIT](https://github.com/clburlison/bakeit) && [go2chef](https://github.com/facebookincubator/go2chef) with the aim of supporting windows bootstrap of puppet nodes via in-tune deployment due to some nice ness with script reporting.

## Objectives

The following is a non-exhaustive list of objectives for a MVP

- Install puppet at a known version
- Configure basic puppet settings
- Verify the SSL connection is valid and in a good state

## Technologies

At a high level the technologies choosen are as follows.

- [GoLang](https://golang.org/) This has been choosen for it's ability to compile to OS-Native binaries easily supporting deployment within intune and better error reporting
- [cobra](https://github.com/spf13/cobra) This has been choosen as a flexible framework to build on
