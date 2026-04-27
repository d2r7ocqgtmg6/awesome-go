# Awesome Go

[![Build Status](https://github.com/awesome-go/awesome-go/actions/workflows/tests.yml/badge.svg)](https://github.com/awesome-go/awesome-go/actions)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true&logo=slack&colorB=red)](https://gophers.slack.com/messages/awesome)
[![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys)
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/avelino/awesome-go/)

A curated list of awesome Go frameworks, libraries, and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

**Contributing:**

Please take a quick look at the [contribution guidelines](CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

> _If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!_

## Contents

- [Awesome Go](#awesome-go)
  - [Contents](#contents)
  - [Audio and Music](#audio-and-music)
  - [Authentication and OAuth](#authentication-and-oauth)
  - [Blockchain](#blockchain)
  - [Bot Building](#bot-building)
  - [Build Automation](#build-automation)
  - [Command Line](#command-line)
  - [Configuration](#configuration)
  - [Data Structures and Algorithms](#data-structures-and-algorithms)
  - [Database](#database)
  - [Date and Time](#date-and-time)
  - [Distributed Systems](#distributed-systems)
  - [Error Handling](#error-handling)
  - [File Handling](#file-handling)
  - [Financial](#financial)
  - [Forms](#forms)
  - [Functional](#functional)
  - [Game Development](#game-development)
  - [Generators](#generators)
  - [Geographic](#geographic)
  - [Go Compilers](#go-compilers)
  - [Goroutines](#goroutines)
  - [GUI](#gui)
  - [Hardware](#hardware)
  - [Images](#images)
  - [IoT (Internet of Things)](#iot-internet-of-things)
  - [Job Scheduler](#job-scheduler)
  - [JSON](#json)
  - [Logging](#logging)
  - [Machine Learning](#machine-learning)
  - [Messaging](#messaging)
  - [Microsoft Office](#microsoft-office)
  - [Miscellaneous](#miscellaneous)
  - [Natural Language Processing](#natural-language-processing)
  - [Networking](#networking)
  - [ORM](#orm)
  - [Package Management](#package-management)
  - [Performance](#performance)
  - [Query Language](#query-language)
  - [Reflection](#reflection)
  - [Science and Data Analysis](#science-and-data-analysis)
  - [Security](#security)
  - [Serialization](#serialization)
  - [Server Applications](#server-applications)
  - [Stream Processing](#stream-processing)
  - [Template Engines](#template-engines)
  - [Testing](#testing)
  - [Text Processing](#text-processing)
  - [Third-party APIs](#third-party-apis)
  - [Utilities](#utilities)
  - [UUID](#uuid)
  - [Validation](#validation)
  - [Version Control](#version-control)
  - [Video](#video)
  - [Web Frameworks](#web-frameworks)
  - [WebAssembly](#webassembly)
  - [Windows](#windows)
  - [XML](#xml)
  - [Zero Trust](#zero-trust)
  - [Code Analysis](#code-analysis)
  - [Editor Plugins](#editor-plugins)
  - [Go Generate Tools](#go-generate-tools)
  - [Go Tools](#go-tools)
  - [Style Guides](#style-guides)
  - [Social Media](#social-media)
  - [Websites](#websites)
  - [Tutorials](#tutorials)

## Audio and Music

_Libraries for manipulating audio._

- [flac](https://github.com/mewkiz/flac) - Native Go FLAC encoder/decoder with support for FLAC streams.
- [gaad](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser.
- [GoAudio](https://github.com/DylanMeeus/GoAudio) - Native Go Audio Processing Library.
- [gosamplerate](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go.
- [id3v2](https://github.com/bogem/id3v2) - ID3 decoding and encoding library for Go.
- [malgo](https://github.com/gen2brain/malgo) - Mini audio library.
- [minimp3](https://github.com/tosone/minimp3) - Lightweight MP3 decoder library.
- [music-theory](https://github.com/go-music-theory/music-theory) - Music theory models in Go.
- [Oto](https://github.com/hajimehoshi/oto) - A low-level library to play sound on multiple platforms.
- [portaudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library.

## Authentication and OAuth

_Libraries for implementing authentication schemes._

- [authboss](https://github.com/volatiletech/authboss) - Modular authentication system for the web.
- [branca](https://github.com/essentialkaos/branca) - branca token [specification implementation](https://github.com/tuupola/branca-spec) for Golang 1.15+.
- [casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC.
- [cookiestxt](https://github.com/mengzhuo/cookiestxt) - provides a parser of cookies.txt file format.
- [go-guardian](https://github.com/shaj13/go-guardian) - Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token, and Certificate based authentication.
- [go-jose](https://github.com/go-jose/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.
- [gologin](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers.
- [gorbac](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang.
- [gosession](http://github.com/Kwynto/gosession) - This is quick session for net/http in GoLang. This package is perhaps the best implementation of the session mechanism, or at least it tries to become one.
- [goth](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box.
- [jeff](https://github.com/abraithwaite/jeff) - Simple, flexible, secure, and idiomatic web session management with pluggable backends.
- [jwt](https://github.com/pascaldekloe/jwt) - Lightweight JSON Web Token (JWT) library.
- [jwt](https://github.com/cristalhq/jwt) - Safe, simple, and fast JSON Web Tokens for Go.
- [jwt-auth](https://github.com/adam-hanna/jwt-auth) - JWT middleware for Golang http servers with many configuration options.
- [jwt-go](https://github.com/golang-jwt/jwt) - A full featured implementation of JSON Web Tokens (JWT). This library supports the parsing and verification as well as the generation and signing of JWTs.
- [keto](https://github.com/ory/keto) - Open Source (Go) implementation of "Zanzibar: Google's Consistent, Global Authorization System".
- [loginsrv](https://github.com/tarent/loginsrv) - JWT login microservice with pluggable backends such as OAuth2 (Github), htpasswd, osiam.
- [oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine, and App Engine support.
- [osin](https://github.com/openshift/osin) - Golang OAuth2 server library.
- [oidc](https://github.com/zitadel/oidc) - Easy to use OpenID Connect client and server library written for Go and certified by the OpenID Foundation.
- [openfga](https://github.com/openfga/openfga) - Implementation of fine-grained authorization based on the "Zanzibar: Google's Consistent, Global Authorization System" paper.
- [paseto](https://github.com/o1ecc/paseto) - Golang implementation of Platform-Agnostic Security Tokens specification.
- [permissions2](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states, and permissions. Uses secure cookies and bcrypt.
- [scope](https://github.com/SonicRoshan/scope) - Easily Manage OAuth2 Scopes In Go.
- [scs](https://github.com/alexedwards/scs) - Session Manager for HTTP servers.
- [securecookie](https://github.com/chmike/securecookie) - Efficient secure cookie encoding/decoding.
- [session](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE).
- [sessions](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers.
- [sessionup](https://github.com/swithek/sessionup) - Simple, yet effective HTTP session management and identification package.
- [sjwt](https://github.com/brianvoe/sjwt) - Simple jwt generator and parser.

---

See the full list at [awesome-go.com](https://awesome-go.com)

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting a PR.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Avelino](https://github.com/avelino) has waived all copyright and related or neighboring rights to this work.
