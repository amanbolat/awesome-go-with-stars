
# About
This repository is a clone of [Awesome Go](https://github.com/avelino/awesome-go) but with stars.
All repositories are still sorted alphabetically.

## Why?
Some of the viewers might be against this idea because "stars don't mean anything" or "stars != code quality".
Yet stars are about numbers, and numbers talk for themselves. First of all, stars may help some newcomers who 
are not familiar with Go ecosystem and want to find some good framework for the first project. 
This list will help them to find a few popular web-frameworks, libraries or tools for a quick start. Secondly, people like me 
might often use a such list of projects to find something trending or they just want to find similar libraries to 
run benchmarks.

## How?
This repository is updated every day by the script which is be run by scheduler. 
### Contents

- [Awesome Go](#awesome-go)
  - [Audio and Music](#audio-and-music)
  - [Authentication and OAuth](#authentication-and-oauth)
  - [Bot Building](#bot-building)
  - [Build Automation](#build-automation)
  - [Command Line](#command-line)
  - [Configuration](#configuration)
  - [Continuous Integration](#continuous-integration)
  - [CSS Preprocessors](#css-preprocessors)
  - [Data Structures](#data-structures)
  - [Database](#database)
  - [Database Drivers](#database-drivers)
  - [Date and Time](#date-and-time)
  - [Distributed Systems](#distributed-systems)
  - [Dynamic DNS](#dynamic-dns)
  - [Email](#email)
  - [Embeddable Scripting Languages](#embeddable-scripting-languages)
  - [Error Handling](#error-handling)
  - [File Handling](#file-handling)
  - [Financial](#financial)
  - [Forms](#forms)
  - [Functional](#functional)
  - [Game Development](#game-development)
  - [Generation and Generics](#generation-and-generics)
  - [Geographic](#geographic)
  - [Go Compilers](#go-compilers)
  - [Goroutines](#goroutines)
  - [GUI](#gui)
  - [Hardware](#hardware)
  - [Images](#images)
  - [IoT](#iot-internet-of-things)
  - [Job Scheduler](#job-scheduler)
  - [JSON](#json)
  - [Logging](#logging)
  - [Machine Learning](#machine-learning)
  - [Messaging](#messaging)
  - [Microsoft Office](#microsoft-office)
    - [Microsoft Excel](#microsoft-excel)
  - [Miscellaneous](#miscellaneous)
    - [Dependency Injection](#dependency-injection)
    - [Project Layout](#project-layout)
    - [Strings](#strings)
    - [Uncategorized](#uncategorized)
  - [Natural Language Processing](#natural-language-processing)
  - [Networking](#networking)
    - [HTTP Clients](#http-clients)
  - [OpenGL](#opengl)
  - [ORM](#orm)
  - [Package Management](#package-management)
  - [Performance](#performance)
  - [Query Language](#query-language)
  - [Resource Embedding](#resource-embedding)
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
    - [Middlewares](#middlewares)
      - [Actual middlewares](#actual-middlewares)
      - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
    - [Routers](#routers)
  - [WebAssembly](#webassembly)
  - [Windows](#windows)
  - [XML](#xml)
- [Tools](#tools)
  - [Code Analysis](#code-analysis)
  - [Editor Plugins](#editor-plugins)
  - [Go Generate Tools](#go-generate-tools)
  - [Go Tools](#go-tools)
  - [Software Packages](#software-packages)
    - [DevOps Tools](#devops-tools)
    - [Other Software](#other-software)
- [Resources](#resources)
  - [Benchmarks](#benchmarks)
  - [Conferences](#conferences)
  - [E-Books](#e-books)
  - [Gophers](#gophers)
  - [Meetups](#meetups)
  - [Style Guides](#style-guides)
  - [Twitter](#twitter)
  - [Websites](#websites)
    - [Tutorials](#tutorials)

## Audio and Music

*Libraries for manipulating audio.*

* <code>&nbsp;&nbsp;&nbsp;837</code> ![](https://img.shields.io/github/last-commit/hajimehoshi/oto) [Oto](https://github.com/hajimehoshi/oto) - A low-level library to play sound on multiple platforms.
* <code>&nbsp;&nbsp;&nbsp;460</code> ![](https://img.shields.io/github/last-commit/gordonklaus/portaudio) [PortAudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library.
* <code>&nbsp;&nbsp;&nbsp;349</code> ![](https://img.shields.io/github/last-commit/go-music-theory/music-theory) [music-theory](https://github.com/go-music-theory/music-theory) - Music theory models in Go.
* <code>&nbsp;&nbsp;&nbsp;342</code> ![](https://img.shields.io/github/last-commit/mdlayher/waveform) [waveform](https://github.com/mdlayher/waveform) - Go package capable of generating waveform images from audio streams.
* <code>&nbsp;&nbsp;&nbsp;259</code> ![](https://img.shields.io/github/last-commit/rakyll/portmidi) [portmidi](https://github.com/rakyll/portmidi) - Go bindings for PortMidi.
* <code>&nbsp;&nbsp;&nbsp;188</code> ![](https://img.shields.io/github/last-commit/bogem/id3v2) [id3v2](https://github.com/bogem/id3v2) - ID3 decoding and encoding library for Go.
* <code>&nbsp;&nbsp;&nbsp;159</code> ![](https://img.shields.io/github/last-commit/mewkiz/flac) [flac](https://github.com/mewkiz/flac) - Native Go FLAC encoder/decoder with support for FLAC streams.
* <code>&nbsp;&nbsp;&nbsp;150</code> ![](https://img.shields.io/github/last-commit/gen2brain/malgo) [malgo](https://github.com/gen2brain/malgo) - Mini audio library.
* <code>&nbsp;&nbsp;&nbsp;141</code> ![](https://img.shields.io/github/last-commit/DylanMeeus/GoAudio) [GoAudio](https://github.com/DylanMeeus/GoAudio) - Native Go Audio Processing Library.
* <code>&nbsp;&nbsp;&nbsp;140</code> ![](https://img.shields.io/github/last-commit/go-mix/mix) [mix](https://github.com/go-mix/mix) - Sequence-based Go-native audio mixer for music apps.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;86</code> ![](https://img.shields.io/github/last-commit/Comcast/gaad) [gaad](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;56</code> ![](https://img.shields.io/github/last-commit/tosone/minimp3) [minimp3](https://github.com/tosone/minimp3) - Lightweight MP3 decoder library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/mccoyst/vorbis) [vorbis](https://github.com/mccoyst/vorbis) - "Native" Go Vorbis decoder (uses CGO, but has no dependencies).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/dh1tw/gosamplerate) [gosamplerate](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go.

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

* <code>&nbsp;&nbsp;3747</code> ![](https://img.shields.io/github/last-commit/golang/oauth2) [oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support.
* <code>&nbsp;&nbsp;3278</code> ![](https://img.shields.io/github/last-commit/markbates/goth) [goth](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box.
* <code>&nbsp;&nbsp;2720</code> ![](https://img.shields.io/github/last-commit/volatiletech/authboss) [authboss](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time.
* <code>&nbsp;&nbsp;1799</code> ![](https://img.shields.io/github/last-commit/square/go-jose) [go-jose](https://github.com/square/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.
* <code>&nbsp;&nbsp;1798</code> ![](https://img.shields.io/github/last-commit/tarent/loginsrv) [loginsrv](https://github.com/tarent/loginsrv) - JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam.
* <code>&nbsp;&nbsp;1790</code> ![](https://img.shields.io/github/last-commit/RichardKnop/go-oauth2-server) [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - Standalone, specification-compliant, OAuth2 server written in Golang.
* <code>&nbsp;&nbsp;1682</code> ![](https://img.shields.io/github/last-commit/openshift/osin) [osin](https://github.com/openshift/osin) - Golang OAuth2 server library.
* <code>&nbsp;&nbsp;1422</code> ![](https://img.shields.io/github/last-commit/dghubble/gologin) [gologin](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers.
* <code>&nbsp;&nbsp;1200</code> ![](https://img.shields.io/github/last-commit/mikespook/gorbac) [gorbac](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang.
* <code>&nbsp;&nbsp;&nbsp;908</code> ![](https://img.shields.io/github/last-commit/alexedwards/scs) [scs](https://github.com/alexedwards/scs) - Session Manager for HTTP servers.
* <code>&nbsp;&nbsp;&nbsp;530</code> ![](https://img.shields.io/github/last-commit/o1egl/paseto) [paseto](https://github.com/o1egl/paseto) - Golang implementation of Platform-Agnostic Security Tokens (PASETO).
* <code>&nbsp;&nbsp;&nbsp;431</code> ![](https://img.shields.io/github/last-commit/xyproto/permissions2) [permissions2](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt.
* <code>&nbsp;&nbsp;&nbsp;291</code> ![](https://img.shields.io/github/last-commit/shaj13/go-guardian) [go-guardian](https://github.com/shaj13/go-guardian) - Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token and Certificate based authentication.
* <code>&nbsp;&nbsp;&nbsp;282</code> ![](https://img.shields.io/github/last-commit/cristalhq/jwt) [jwt](https://github.com/cristalhq/jwt) - Safe, simple and fast JSON Web Tokens for Go.
* <code>&nbsp;&nbsp;&nbsp;260</code> ![](https://img.shields.io/github/last-commit/pascaldekloe/jwt) [jwt](https://github.com/pascaldekloe/jwt) - Lightweight JSON Web Token (JWT) library.
* <code>&nbsp;&nbsp;&nbsp;229</code> ![](https://img.shields.io/github/last-commit/abraithwaite/jeff) [jeff](https://github.com/abraithwaite/jeff) - Simple, flexible, secure and idiomatic web session management with pluggable backends.
* <code>&nbsp;&nbsp;&nbsp;207</code> ![](https://img.shields.io/github/last-commit/goji/httpauth) [httpauth](https://github.com/goji/httpauth) - HTTP Authentication middleware.
* <code>&nbsp;&nbsp;&nbsp;205</code> ![](https://img.shields.io/github/last-commit/adam-hanna/jwt-auth) [jwt-auth](https://github.com/adam-hanna/jwt-auth) - JWT middleware for Golang http servers with many configuration options.
* <code>&nbsp;&nbsp;&nbsp;155</code> ![](https://img.shields.io/github/last-commit/hako/branca) [branca](https://github.com/hako/branca) - Golang implementation of Branca Tokens.
* <code>&nbsp;&nbsp;&nbsp;113</code> ![](https://img.shields.io/github/last-commit/swithek/sessionup) [sessionup](https://github.com/swithek/sessionup) - Simple, yet effective HTTP session management and identification package.
* <code>&nbsp;&nbsp;&nbsp;105</code> ![](https://img.shields.io/github/last-commit/icza/session) [session](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;93</code> ![](https://img.shields.io/github/last-commit/brianvoe/sjwt) [sjwt](https://github.com/brianvoe/sjwt) - Simple jwt generator and parser.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;91</code> ![](https://img.shields.io/github/last-commit/robbert229/jwt) [jwt](https://github.com/robbert229/jwt) - Clean and easy to use implementation of JSON Web Tokens (JWT).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;81</code> ![](https://img.shields.io/github/last-commit/zpatrick/rbac) [rbac](https://github.com/zpatrick/rbac) - Minimalistic RBAC package for Go applications.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;60</code> ![](https://img.shields.io/github/last-commit/adam-hanna/sessions) [sessions](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;52</code> ![](https://img.shields.io/github/last-commit/chmike/securecookie) [securecookie](https://github.com/chmike/securecookie) - Efficient secure cookie encoding/decoding.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> ![](https://img.shields.io/github/last-commit/dimuska139/go-email-normalizer) [go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) - Golang library for providing a canonical representation of email address.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> ![](https://img.shields.io/github/last-commit/jltorresm/otpgo) [otpgo](https://github.com/jltorresm/otpgo) - Time-Based One-Time Password (TOTP) and HMAC-Based One-Time Password (HOTP) library for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/grijul/otpgen) [otpgen](https://github.com/grijul/otpgen) - Library to generate TOTP/HOTP codes.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/SonicRoshan/scope) [scope](https://github.com/SonicRoshan/scope) - Easily Manage OAuth2 Scopes In Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/f0rmiga/sessiongate-go) [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) - Go session management using the SessionGate Redis module.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/mengzhuo/cookiestxt) [cookiestxt](https://github.com/mengzhuo/cookiestxt) - provides parser of cookies.txt file format.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> ![](https://img.shields.io/github/last-commit/hsluoyz/casbin) [casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC.

## Bot Building

*Libraries for building and working with bots.*

* <code>&nbsp;&nbsp;3004</code> ![](https://img.shields.io/github/last-commit/olivia-ai/olivia) [olivia](https://github.com/olivia-ai/olivia) - A chatbot built with an artificial neural network.
* <code>&nbsp;&nbsp;2988</code> ![](https://img.shields.io/github/last-commit/Syfaro/telegram-bot-api) [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client.
* <code>&nbsp;&nbsp;2020</code> ![](https://img.shields.io/github/last-commit/tucnak/telebot) [telebot](https://github.com/tucnak/telebot) - Telegram bot framework written in Go.
* <code>&nbsp;&nbsp;&nbsp;720</code> ![](https://img.shields.io/github/last-commit/stellar/kelp) [Kelp](https://github.com/stellar/kelp) - official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies.
* <code>&nbsp;&nbsp;&nbsp;690</code> ![](https://img.shields.io/github/last-commit/go-chat-bot/bot) [go-chat-bot](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go.
* <code>&nbsp;&nbsp;&nbsp;579</code> ![](https://img.shields.io/github/last-commit/saniales/golang-crypto-trading-bot) [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) - A golang implementation of a console-based trading bot for cryptocurrency exchanges.
* <code>&nbsp;&nbsp;&nbsp;542</code> ![](https://img.shields.io/github/last-commit/shomali11/slacker) [slacker](https://github.com/shomali11/slacker) - Easy to use framework to create Slack bots.
* <code>&nbsp;&nbsp;&nbsp;316</code> ![](https://img.shields.io/github/last-commit/yanzay/tbot) [tbot](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http.
* <code>&nbsp;&nbsp;&nbsp;196</code> ![](https://img.shields.io/github/last-commit/oklahomer/go-sarah) [go-sarah](https://github.com/oklahomer/go-sarah) - Framework to build bot for desired chat services including LINE, Slack, Gitter and more.
* <code>&nbsp;&nbsp;&nbsp;180</code> ![](https://img.shields.io/github/last-commit/gempir/go-twitch-irc) [go-twitch-irc](https://github.com/gempir/go-twitch-irc) - Libary to write bots for twitch.tv chat
* <code>&nbsp;&nbsp;&nbsp;171</code> ![](https://img.shields.io/github/last-commit/kyleterry/tenyks) [Tenyks](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging.
* <code>&nbsp;&nbsp;&nbsp;135</code> ![](https://img.shields.io/github/last-commit/sbstjn/hanu) [hanu](https://github.com/sbstjn/hanu) - Framework for writing Slack bots.
* <code>&nbsp;&nbsp;&nbsp;107</code> ![](https://img.shields.io/github/last-commit/olebedev/go-tgbot) [go-tgbot](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;63</code> ![](https://img.shields.io/github/last-commit/zhulik/margelet) [margelet](https://github.com/zhulik/margelet) - Framework for building Telegram bots.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> ![](https://img.shields.io/github/last-commit/ewohltman/ephemeral-roles) [ephemeral-roles](https://github.com/ewohltman/ephemeral-roles) - A Discord bot for managing ephemeral roles based upon voice channel member presence.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> ![](https://img.shields.io/github/last-commit/innogames/slack-bot) [slack-bot](https://github.com/innogames/slack-bot) - Ready to use Slack Bot for lazy developers: Custom commands, Jenkins, Jira, Bitbucket, Github...
* <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> ![](https://img.shields.io/github/last-commit/alexandre-normand/slackscot) [slackscot](https://github.com/alexandre-normand/slackscot) - Another framework for building Slack bots.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> ![](https://img.shields.io/github/last-commit/nikepan/govkbot) [govkbot](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> ![](https://img.shields.io/github/last-commit/NicoNex/echotron) [echotron](https://github.com/NicoNex/echotron) - Library for Telegram Bots written in pure Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/onrik/micha) [micha](https://github.com/onrik/micha) - Go Library for Telegram bot api.
* [go-joe](https://joe-bot.net) - A general-purpose bot library inspired by Hubot but written in Go.

## Build Automation

*Libraries and tools helping with build automation.*

* <code>&nbsp;&nbsp;4063</code> ![](https://img.shields.io/github/last-commit/tockins/realize) [realize](https://github.com/tockins/realize) - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths.
* <code>&nbsp;&nbsp;3701</code> ![](https://img.shields.io/github/last-commit/go-task/task) [Task](https://github.com/go-task/task) - simple "Make" alternative.
* <code>&nbsp;&nbsp;1577</code> ![](https://img.shields.io/github/last-commit/tj/mmake) [mmake](https://github.com/tj/mmake) - Modern Make.
* <code>&nbsp;&nbsp;&nbsp;241</code> ![](https://img.shields.io/github/last-commit/goyek/goyek) [goyek](https://github.com/goyek/goyek) - Create build pipelines in Go.
* <code>&nbsp;&nbsp;&nbsp;120</code> ![](https://img.shields.io/github/last-commit/taskctl/taskctl) [taskctl](https://github.com/taskctl/taskctl) - Concurrent task runner.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;96</code> ![](https://img.shields.io/github/last-commit/gopinath-langote/1build) [1build](https://github.com/gopinath-langote/1build) - Command line tool to frictionlessly manage project-specific commands.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> ![](https://img.shields.io/github/last-commit/maxcnunes/gaper) [gaper](https://github.com/maxcnunes/gaper) - Builds and restarts a Go project when it crashes or some watched file changes.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/GuilhermeCaruso/anko) [anko](https://github.com/GuilhermeCaruso/anko) - Simple application watcher for multiple programming languages.
* [gilbert](https://go-gilbert.github.io) - Build system and task runner for Go projects.

## Command Line

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* <code>&nbsp;22633</code> ![](https://img.shields.io/github/last-commit/spf13/cobra) [cobra](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions.
* <code>&nbsp;16274</code> ![](https://img.shields.io/github/last-commit/urfave/cli) [urfave/cli](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).
* <code>&nbsp;&nbsp;4407</code> ![](https://img.shields.io/github/last-commit/elves/elvish) [elvish](https://github.com/elves/elvish) - An expressive programming language and a versatile interactive shell.
* <code>&nbsp;&nbsp;3087</code> ![](https://img.shields.io/github/last-commit/alecthomas/kingpin) [kingpin](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands.
* <code>&nbsp;&nbsp;2117</code> ![](https://img.shields.io/github/last-commit/dnote/dnote) [Dnote](https://github.com/dnote/dnote) - A simple command line notebook with multi-device sync.
* <code>&nbsp;&nbsp;1989</code> ![](https://img.shields.io/github/last-commit/jessevdk/go-flags) [go-flags](https://github.com/jessevdk/go-flags) - go command line option parser.
* <code>&nbsp;&nbsp;1508</code> ![](https://img.shields.io/github/last-commit/spf13/pflag) [pflag](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.
* <code>&nbsp;&nbsp;1366</code> ![](https://img.shields.io/github/last-commit/mitchellh/cli) [mitchellh/cli](https://github.com/mitchellh/cli) - Go library for implementing command-line interfaces.
* <code>&nbsp;&nbsp;1200</code> ![](https://img.shields.io/github/last-commit/alexflint/go-arg) [go-arg](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go.
* <code>&nbsp;&nbsp;&nbsp;807</code> ![](https://img.shields.io/github/last-commit/peterh/liner) [liner](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces.
* <code>&nbsp;&nbsp;&nbsp;781</code> ![](https://img.shields.io/github/last-commit/posener/complete) [complete](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion.
* <code>&nbsp;&nbsp;&nbsp;742</code> ![](https://img.shields.io/github/last-commit/jawher/mow.cli) [mow.cli](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation.
* <code>&nbsp;&nbsp;&nbsp;726</code> ![](https://img.shields.io/github/last-commit/integrii/flaggy) [flaggy](https://github.com/integrii/flaggy) - A robust and idiomatic flags package with excellent subcommand support.
* <code>&nbsp;&nbsp;&nbsp;651</code> ![](https://img.shields.io/github/last-commit/nanovms/ops) [ops](https://github.com/nanovms/ops) - Unikernel Builder/Orchestrator.
* <code>&nbsp;&nbsp;&nbsp;593</code> ![](https://img.shields.io/github/last-commit/mkideal/cli) [cli](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang struct tags.
* <code>&nbsp;&nbsp;&nbsp;348</code> ![](https://img.shields.io/github/last-commit/akamensky/argparse) [argparse](https://github.com/akamensky/argparse) - Command line argument parser inspired by Python's argparse module.
* <code>&nbsp;&nbsp;&nbsp;186</code> ![](https://img.shields.io/github/last-commit/tucnak/climax) [climax](http://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.
* <code>&nbsp;&nbsp;&nbsp;162</code> ![](https://img.shields.io/github/last-commit/hidevopsio/hiboot) [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - cli application framework with auto configuration and dependency injection.
* <code>&nbsp;&nbsp;&nbsp;148</code> ![](https://img.shields.io/github/last-commit/jaffee/commandeer) [commandeer](https://github.com/jaffee/commandeer) - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags.
* <code>&nbsp;&nbsp;&nbsp;140</code> ![](https://img.shields.io/github/last-commit/dixonwille/wmenu) [wmenu](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompts users to make choices.
* <code>&nbsp;&nbsp;&nbsp;130</code> ![](https://img.shields.io/github/last-commit/octago/sflags) [sflags](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries.
* <code>&nbsp;&nbsp;&nbsp;114</code> ![](https://img.shields.io/github/last-commit/cosiner/flag) [flag](https://github.com/cosiner/flag) - Simple but powerful command line option parsing library for Go supporting subcommand.
* <code>&nbsp;&nbsp;&nbsp;108</code> ![](https://img.shields.io/github/last-commit/ukautz/clif) [ukautz/clif](https://github.com/ukautz/clif) - Small command line interface framework.
* <code>&nbsp;&nbsp;&nbsp;103</code> ![](https://img.shields.io/github/last-commit/liujianping/job) [job](https://github.com/liujianping/job) - JOB, make your short-term command as a long-term job.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;89</code> ![](https://img.shields.io/github/last-commit/teris-io/cli) [cli](https://github.com/teris-io/cli) - Simple and complete API for building command line interfaces in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;80</code> ![](https://img.shields.io/github/last-commit/codingconcepts/env) [env](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;78</code> ![](https://img.shields.io/github/last-commit/hedzr/cmdr) [cmdr](https://github.com/hedzr/cmdr) - A POSIX/GNU style, getopt-like command-line UI Go library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;74</code> ![](https://img.shields.io/github/last-commit/leaanthony/clir) [clîr](https://github.com/leaanthony/clir) - A Simple and Clear CLI library. Dependency free.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> ![](https://img.shields.io/github/last-commit/devfacet/gocmd) [gocmd](https://github.com/devfacet/gocmd) - Go library for building command line applications.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> ![](https://img.shields.io/github/last-commit/dixonwille/wlog) [wlog](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;44</code> ![](https://img.shields.io/github/last-commit/antham/strumt) [strumt](https://github.com/antham/strumt) - Library to create prompt chain.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> ![](https://img.shields.io/github/last-commit/DavidGamba/go-getoptions) [go-getoptions](https://github.com/DavidGamba/go-getoptions) - Go option parser inspired on the flexibility of Perl’s GetOpt::Long.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> ![](https://img.shields.io/github/last-commit/sgreben/flagvar) [flagvar](https://github.com/sgreben/flagvar) - A collection of flag argument types for Go's standard `flag` package.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/posener/cmd) [cmd](https://github.com/posener/cmd) - Extends the standard `flag` package to support sub commands and more in idomatic way.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> ![](https://img.shields.io/github/last-commit/cosiner/argv) [argv](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> ![](https://img.shields.io/github/last-commit/yitsushi/go-commander) [go-commander](https://github.com/yitsushi/go-commander) - Go library to simplify CLI workflow.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/Zaba505/sand) [sand](https://github.com/Zaba505/sand) - Simple API for creating interpreters and so much more.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> ![](https://img.shields.io/github/last-commit/liujianping/ts) [ts](https://github.com/liujianping/ts) - Timestamp convert & compare tool.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/rainu/go-command-chain) [command-chain](https://github.com/rainu/go-command-chain) - A go library for configure and run command chains - such like pipelining in unix shells.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/grijul/go-andotp) [go-andotp](https://github.com/grijul/go-andotp) - A CLI program to encrypt/decrypt <code>&nbsp;&nbsp;3099</code> ![](https://img.shields.io/github/last-commit/andOTP/andOTP) [andOTP](https://github.com/andOTP/andOTP) files. Can be used as library as well.

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* <code>&nbsp;11125</code> ![](https://img.shields.io/github/last-commit/gizak/termui) [termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by <code>&nbsp;14410</code> ![](https://img.shields.io/github/last-commit/yaronn/blessed-contrib) [blessed-contrib](https://github.com/yaronn/blessed-contrib).
* <code>&nbsp;&nbsp;7291</code> ![](https://img.shields.io/github/last-commit/jroimartin/gocui) [gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces.
* <code>&nbsp;&nbsp;4107</code> ![](https://img.shields.io/github/last-commit/nsf/termbox-go) [termbox-go](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces.
* <code>&nbsp;&nbsp;4052</code> ![](https://img.shields.io/github/last-commit/c-bata/go-prompt) [go-prompt](https://github.com/c-bata/go-prompt) - Library for building a powerful interactive prompt, inspired by <code>&nbsp;&nbsp;7196</code> ![](https://img.shields.io/github/last-commit/jonathanslenders/python-prompt-toolkit) [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).
* <code>&nbsp;&nbsp;1982</code> ![](https://img.shields.io/github/last-commit/schollz/progressbar) [progressbar](https://github.com/schollz/progressbar) - Basic thread-safe progress bar that works in every OS.
* <code>&nbsp;&nbsp;1814</code> ![](https://img.shields.io/github/last-commit/gosuri/uiprogress) [uiprogress](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications.
* <code>&nbsp;&nbsp;1769</code> ![](https://img.shields.io/github/last-commit/mum4k/termdash) [termdash](https://github.com/mum4k/termdash) - Go terminal dashboard based on **termbox-go** and inspired by <code>&nbsp;11125</code> ![](https://img.shields.io/github/last-commit/gizak/termui) [termui](https://github.com/gizak/termui).
* <code>&nbsp;&nbsp;1745</code> ![](https://img.shields.io/github/last-commit/pterm/pterm) [pterm](https://github.com/pterm/pterm) - A library to beautify console output on every platform with many combinable components.
* <code>&nbsp;&nbsp;1715</code> ![](https://img.shields.io/github/last-commit/guptarohit/asciigraph) [asciigraph](https://github.com/guptarohit/asciigraph) - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies.
* <code>&nbsp;&nbsp;1421</code> ![](https://img.shields.io/github/last-commit/vbauerster/mpb) [mpb](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications.
* <code>&nbsp;&nbsp;1325</code> ![](https://img.shields.io/github/last-commit/gosuri/uilive) [uilive](https://github.com/gosuri/uilive) - Library for updating terminal output in realtime.
* <code>&nbsp;&nbsp;1114</code> ![](https://img.shields.io/github/last-commit/logrusorgru/aurora) [aurora](https://github.com/logrusorgru/aurora) - ANSI terminal colors that supports fmt.Printf/Sprintf.
* <code>&nbsp;&nbsp;&nbsp;884</code> ![](https://img.shields.io/github/last-commit/gookit/color) [gookit/color](https://github.com/gookit/color) - Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows.
* <code>&nbsp;&nbsp;&nbsp;727</code> ![](https://img.shields.io/github/last-commit/muesli/termenv) [termenv](https://github.com/muesli/termenv) - Advanced ANSI style & color support for your terminal applications
* <code>&nbsp;&nbsp;&nbsp;617</code> ![](https://img.shields.io/github/last-commit/gosuri/uitable) [uitable](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data.
* <code>&nbsp;&nbsp;&nbsp;539</code> ![](https://img.shields.io/github/last-commit/mattn/go-colorable) [go-colorable](https://github.com/mattn/go-colorable) - Colorable writer for windows.
* <code>&nbsp;&nbsp;&nbsp;537</code> ![](https://img.shields.io/github/last-commit/mattn/go-isatty) [go-isatty](https://github.com/mattn/go-isatty) - isatty for golang.
* <code>&nbsp;&nbsp;&nbsp;403</code> ![](https://img.shields.io/github/last-commit/labstack/gommon) [gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text.
* <code>&nbsp;&nbsp;&nbsp;379</code> ![](https://img.shields.io/github/last-commit/ttacon/chalk) [chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output.
* <code>&nbsp;&nbsp;&nbsp;321</code> ![](https://img.shields.io/github/last-commit/alexeyco/simpletable) [simpletable](https://github.com/alexeyco/simpletable) - Simple tables in terminal with Go.
* <code>&nbsp;&nbsp;&nbsp;294</code> ![](https://img.shields.io/github/last-commit/cheynewallace/tabby) [tabby](https://github.com/cheynewallace/tabby) - A tiny library for super simple Golang tables.
* <code>&nbsp;&nbsp;&nbsp;207</code> ![](https://img.shields.io/github/last-commit/daviddengcn/go-colortext) [go-colortext](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals.
* <code>&nbsp;&nbsp;&nbsp;190</code> ![](https://img.shields.io/github/last-commit/theckman/yacspin) [yacspin](https://github.com/theckman/yacspin) - Yet Another CLi Spinner package, for working with terminal spinners.
* <code>&nbsp;&nbsp;&nbsp;140</code> ![](https://img.shields.io/github/last-commit/Delta456/box-cli-maker) [box-cli-maker](https://github.com/Delta456/box-cli-maker) - Make Highly Customized Boxes for your CLI.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;79</code> ![](https://img.shields.io/github/last-commit/mingrammer/cfmt) [cfmt](https://github.com/mingrammer/cfmt) - Contextual fmt inspired by bootstrap color classes.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;55</code> ![](https://img.shields.io/github/last-commit/InVisionApp/tabular) [tabular](https://github.com/InVisionApp/tabular) - Print ASCII tables from command line utilities without the need to pass large sets of data to the API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/wzshiming/ctc) [ctc](https://github.com/wzshiming/ctc) - The non-invasive cross-platform terminal color library does not need to modify the Print method.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> ![](https://img.shields.io/github/last-commit/i582/cfmt) [cfmt](https://github.com/i582/cfmt) - Simple and convenient formatted stylized output fully compatible with fmt library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/TreyBastian/colourize) [colourize](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> ![](https://img.shields.io/github/last-commit/cyucelen/marker) [marker](https://github.com/cyucelen/marker) - Easiest way to match and mark strings for colorful terminal outputs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/workanator/go-ataman) [go-ataman](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> ![](https://img.shields.io/github/last-commit/tomlazar/table) [table](https://github.com/tomlazar/table) - Small library for terminal color based tables .

## Configuration

*Libraries for configuration parsing.*

* <code>&nbsp;16376</code> ![](https://img.shields.io/github/last-commit/spf13/viper) [viper](https://github.com/spf13/viper) - Go configuration with fangs.
* <code>&nbsp;&nbsp;4023</code> ![](https://img.shields.io/github/last-commit/joho/godotenv) [godotenv](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`).
* <code>&nbsp;&nbsp;3707</code> ![](https://img.shields.io/github/last-commit/kelseyhightower/envconfig) [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - Go library for managing configuration data from environment variables.
* <code>&nbsp;&nbsp;2556</code> ![](https://img.shields.io/github/last-commit/go-ini/ini) [ini](https://github.com/go-ini/ini) - Go package to read and write INI files.
* <code>&nbsp;&nbsp;1961</code> ![](https://img.shields.io/github/last-commit/caarlos0/env) [env](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults).
* <code>&nbsp;&nbsp;&nbsp;613</code> ![](https://img.shields.io/github/last-commit/lalamove/konfig) [konfig](https://github.com/lalamove/konfig) - Composable, observable and performant config handling for Go for the distributed processing era.
* <code>&nbsp;&nbsp;&nbsp;555</code> ![](https://img.shields.io/github/last-commit/knadh/koanf) [koanf](https://github.com/knadh/koanf) - Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line.
* <code>&nbsp;&nbsp;&nbsp;401</code> ![](https://img.shields.io/github/last-commit/heetch/confita) [confita](https://github.com/heetch/confita) - Load configuration in cascade from multiple backends into a struct.
* <code>&nbsp;&nbsp;&nbsp;325</code> ![](https://img.shields.io/github/last-commit/ilyakaznacheev/cleanenv) [cleanenv](https://github.com/ilyakaznacheev/cleanenv) - Minimalistic configuration reader (from files, ENV, and wherever you want).
* <code>&nbsp;&nbsp;&nbsp;260</code> ![](https://img.shields.io/github/last-commit/JeremyLoy/config) [config](https://github.com/JeremyLoy/config) - Cloud native application configuration. Bind ENV to structs in only two lines.
* <code>&nbsp;&nbsp;&nbsp;259</code> ![](https://img.shields.io/github/last-commit/gookit/config) [gookit/config](https://github.com/gookit/config) - application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge.
* <code>&nbsp;&nbsp;&nbsp;256</code> ![](https://img.shields.io/github/last-commit/tucnak/store) [store](https://github.com/tucnak/store) - Lightweight configuration manager for Go.
* <code>&nbsp;&nbsp;&nbsp;248</code> ![](https://img.shields.io/github/last-commit/cristalhq/aconfig) [aconfig](https://github.com/cristalhq/aconfig) - Simple, useful and opinionated config loader.
* <code>&nbsp;&nbsp;&nbsp;239</code> ![](https://img.shields.io/github/last-commit/olebedev/config) [config](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with environment variables and flags parsing.
* <code>&nbsp;&nbsp;&nbsp;238</code> ![](https://img.shields.io/github/last-commit/hjson/hjson-go) [hjson](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments.
* <code>&nbsp;&nbsp;&nbsp;206</code> ![](https://img.shields.io/github/last-commit/vrischmann/envconfig) [envconfig](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables.
* <code>&nbsp;&nbsp;&nbsp;205</code> ![](https://img.shields.io/github/last-commit/joshbetz/config) [joshbetz/config](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP.
* <code>&nbsp;&nbsp;&nbsp;158</code> ![](https://img.shields.io/github/last-commit/golobby/config) [config](https://github.com/golobby/config) - A lightweight yet powerful config package for Go projects.
* <code>&nbsp;&nbsp;&nbsp;156</code> ![](https://img.shields.io/github/last-commit/kkyr/fig) [fig](https://github.com/kkyr/fig) - Tiny library for reading configuration from a file and from environment variables (with validation & defaults).
* <code>&nbsp;&nbsp;&nbsp;153</code> ![](https://img.shields.io/github/last-commit/go-gcfg/gcfg) [gcfg](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections.
* <code>&nbsp;&nbsp;&nbsp;148</code> ![](https://img.shields.io/github/last-commit/crgimenes/goConfig) [goConfig](https://github.com/crgimenes/goConfig) - Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file.
* <code>&nbsp;&nbsp;&nbsp;116</code> ![](https://img.shields.io/github/last-commit/adrg/xdg) [xdg](https://github.com/adrg/xdg) - Go implementation of the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) and [XDG user directories](https://wiki.archlinux.org/index.php/XDG_user_directories).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;95</code> ![](https://img.shields.io/github/last-commit/antham/envh) [envh](https://github.com/antham/envh) - Helpers to manage environment variables.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;93</code> ![](https://img.shields.io/github/last-commit/tomazk/envcfg) [envcfg](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;91</code> ![](https://img.shields.io/github/last-commit/goraz/onion) [onion](http://github.com/goraz/onion) - Layer based configuration for Go, Supports JSON, TOML, YAML, properties, etcd, env, and encryption using PGP.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;86</code> ![](https://img.shields.io/github/last-commit/beatlabs/harvester) [harvester](https://github.com/beatlabs/harvester) - Harvester, a easy to use static and dynamic configuration package supportig seeding, env vars and Consul integration.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;74</code> ![](https://img.shields.io/github/last-commit/sherifabdlnaby/configuro) [configuro](https://github.com/sherifabdlnaby/configuro) - opinionated configuration loading & validation framework from ENV and Files focused towards 12-Factor compliant applications.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;63</code> ![](https://img.shields.io/github/last-commit/OpenPeeDeeP/xdg) [xdg](https://github.com/OpenPeeDeeP/xdg) - Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> ![](https://img.shields.io/github/last-commit/ian-kent/gofigure) [gofigure](https://github.com/ian-kent/gofigure) - Go application configuration made easy.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> ![](https://img.shields.io/github/last-commit/paked/configure) [configure](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> ![](https://img.shields.io/github/last-commit/PaddleHQ/go-aws-ssm) [go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) - Go package that fetches parameters from AWS System Manager - Parameter Store.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> ![](https://img.shields.io/github/last-commit/BoRuDar/configuration) [configuration](https://github.com/BoRuDar/configuration) - Library for initializing configuration structs from env variables, files, flags and 'default' tag.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> ![](https://img.shields.io/github/last-commit/One-com/gone) [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> ![](https://img.shields.io/github/last-commit/schachmat/ingo) [ingo](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> ![](https://img.shields.io/github/last-commit/omeid/uconfig) [uConfig](https://github.com/omeid/uconfig) - Lightweight, zero-dependency, and extendable configuration management.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;32</code> ![](https://img.shields.io/github/last-commit/ufoscout/go-up) [go-up](https://github.com/ufoscout/go-up) - A simple configuration library with recursive placeholders resolution and no magic.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/sasbury/mini) [mini](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> ![](https://img.shields.io/github/last-commit/gurkankaymak/hocon) [hocon](https://github.com/gurkankaymak/hocon) - Configuration library for working with the HOCON(a human-friendly JSON superset) format, supports features like environment variables, referencing other values, comments and multiple files.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> ![](https://img.shields.io/github/last-commit/sakirsensoy/genv) [genv](https://github.com/sakirsensoy/genv) - Read environment variables easily with dotenv support.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> ![](https://img.shields.io/github/last-commit/the4thamigo-uk/conflate) [conflate](https://github.com/the4thamigo-uk/conflate) - Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/ian-kent/envconf) [envconf](https://github.com/ian-kent/envconf) - Configuration from environment.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/ianlopshire/go-ssm-config) [go-ssm-config](https://github.com/ianlopshire/go-ssm-config) - Go utility for loading configuration parameters from AWS SSM (Parameter Store).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/nasermirzaei89/env) [nasermirzaei89/env](https://github.com/nasermirzaei89/env) - Simple useful package for read environment variables.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/subpop/go-ini) [go-ini](https://github.com/subpop/go-ini) - A Go package that marshals and unmarshals INI-files.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/oblq/swap) [swap](https://github.com/oblq/swap) - Instantiate/configure structs recursively, based on build environment. (YAML, TOML, JSON and env).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/diegomarangoni/typenv) [typenv](https://github.com/diegomarangoni/typenv) - Minimalistic, zero dependency, typed environment variables library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> ![](https://img.shields.io/github/last-commit/milad-abbasi/gonfig) [gonfig](https://github.com/milad-abbasi/gonfig) - Tag-based configuration parser which loads values from different providers into typesafe struct.

## Continuous Integration

*Tools for help with continuous integration.*

* <code>&nbsp;23632</code> ![](https://img.shields.io/github/last-commit/drone/drone) [drone](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go.
* <code>&nbsp;&nbsp;3498</code> ![](https://img.shields.io/github/last-commit/ovh/cds) [CDS](https://github.com/ovh/cds) - Enterprise-Grade CI/CD and DevOps Automation Open Source Platform.
* <code>&nbsp;&nbsp;&nbsp;693</code> ![](https://img.shields.io/github/last-commit/mattn/goveralls) [goveralls](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system.
* <code>&nbsp;&nbsp;&nbsp;106</code> ![](https://img.shields.io/github/last-commit/go-playground/overalls) [overalls](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> ![](https://img.shields.io/github/last-commit/duck8823/duci) [duci](https://github.com/duck8823/duci) - A simple ci server no needs domain specific languages.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> ![](https://img.shields.io/github/last-commit/nikogura/gomason) [gomason](https://github.com/nikogura/gomason) - Test, Build, Sign, and Publish your go binaries from a clean workspace.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/LawrenceWoodman/roveralls) [roveralls](https://github.com/LawrenceWoodman/roveralls) - Recursive coverage testing tool.

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

* <code>&nbsp;&nbsp;&nbsp;446</code> ![](https://img.shields.io/github/last-commit/yosssi/gcss) [gcss](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor.
* <code>&nbsp;&nbsp;&nbsp;179</code> ![](https://img.shields.io/github/last-commit/wellington/go-libsass) [go-libsass](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project.

## Data Structures

*Generic datastructures and algorithms in Go.*

* <code>&nbsp;10295</code> ![](https://img.shields.io/github/last-commit/emirpasic/gods) [gods](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.
* <code>&nbsp;&nbsp;6120</code> ![](https://img.shields.io/github/last-commit/Workiva/go-datastructures) [go-datastructures](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures.
* <code>&nbsp;&nbsp;2027</code> ![](https://img.shields.io/github/last-commit/deckarep/golang-set) [golang-set](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go.
* <code>&nbsp;&nbsp;1694</code> ![](https://img.shields.io/github/last-commit/kniren/gota) [gota](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go.
* <code>&nbsp;&nbsp;1365</code> ![](https://img.shields.io/github/last-commit/tylertreat/BoomFilters) [boomfilters](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams.
* <code>&nbsp;&nbsp;1276</code> ![](https://img.shields.io/github/last-commit/RoaringBitmap/roaring) [roaring](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets.
* <code>&nbsp;&nbsp;1246</code> ![](https://img.shields.io/github/last-commit/willf/bloom) [willf/bloom](https://github.com/willf/bloom) - Go package implementing Bloom filters.
* <code>&nbsp;&nbsp;&nbsp;921</code> ![](https://img.shields.io/github/last-commit/eko/gocache) [gocache](https://github.com/eko/gocache) - A complete Go cache library with mutiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more.
* <code>&nbsp;&nbsp;&nbsp;814</code> ![](https://img.shields.io/github/last-commit/seiflotfy/cuckoofilter) [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go.
* <code>&nbsp;&nbsp;&nbsp;750</code> ![](https://img.shields.io/github/last-commit/axiomhq/hyperloglog) [hyperloglog](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.
* <code>&nbsp;&nbsp;&nbsp;704</code> ![](https://img.shields.io/github/last-commit/willf/bitset) [bitset](https://github.com/willf/bitset) - Go package implementing bitsets.
* <code>&nbsp;&nbsp;&nbsp;547</code> ![](https://img.shields.io/github/last-commit/shady831213/algorithms) [algorithms](https://github.com/shady831213/algorithms) - Algorithms and data structures.CLRS study.
* <code>&nbsp;&nbsp;&nbsp;542</code> ![](https://img.shields.io/github/last-commit/derekparker/trie) [trie](https://github.com/derekparker/trie) - Trie implementation in Go.
* <code>&nbsp;&nbsp;&nbsp;331</code> ![](https://img.shields.io/github/last-commit/hailocab/go-geoindex) [go-geoindex](https://github.com/hailocab/go-geoindex) - In-memory geo index.
* <code>&nbsp;&nbsp;&nbsp;292</code> ![](https://img.shields.io/github/last-commit/liyue201/gostl) [gostl](https://github.com/liyue201/gostl) - Data structure and algorithm library for go, designed to provide functions similar to C++ STL.
* <code>&nbsp;&nbsp;&nbsp;273</code> ![](https://img.shields.io/github/last-commit/hbollon/go-edlib) [go-edlib](https://github.com/hbollon/go-edlib) - Go string comparison and edit distance algorithms library (Levenshtein, LCS, Hamming, Damerau levenshtein, Jaro-Winkler, etc.) compatible with Unicode.
* <code>&nbsp;&nbsp;&nbsp;258</code> ![](https://img.shields.io/github/last-commit/ReneKroon/ttlcache) [ttlcache](https://github.com/ReneKroon/ttlcache) - In-memory string-interface{} cache with various time-based expiration options and callbacks.
* <code>&nbsp;&nbsp;&nbsp;257</code> ![](https://img.shields.io/github/last-commit/cbergoon/merkletree) [merkletree](https://github.com/cbergoon/merkletree) - Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures.
* <code>&nbsp;&nbsp;&nbsp;235</code> ![](https://img.shields.io/github/last-commit/google/hilbert) [hilbert](https://github.com/google/hilbert) - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves.
* <code>&nbsp;&nbsp;&nbsp;232</code> ![](https://img.shields.io/github/last-commit/gammazero/deque) [deque](https://github.com/gammazero/deque) - Fast ring-buffer deque (double-ended queue).
* <code>&nbsp;&nbsp;&nbsp;227</code> ![](https://img.shields.io/github/last-commit/ryszard/goskiplist) [goskiplist](https://github.com/ryszard/goskiplist) - Skip list implementation in Go.
* <code>&nbsp;&nbsp;&nbsp;196</code> ![](https://img.shields.io/github/last-commit/plar/go-adaptive-radix-tree) [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree.
* <code>&nbsp;&nbsp;&nbsp;166</code> ![](https://img.shields.io/github/last-commit/zhuangsirui/binpacker) [binpacker](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream.
* <code>&nbsp;&nbsp;&nbsp;166</code> ![](https://img.shields.io/github/last-commit/MauriceGit/skiplist) [skiplist](https://github.com/MauriceGit/skiplist) - Very fast Go Skiplist implementation.
* <code>&nbsp;&nbsp;&nbsp;164</code> ![](https://img.shields.io/github/last-commit/linvon/cuckoo-filter) [cuckoo-filter](https://github.com/linvon/cuckoo-filter) - Cuckoo filter: a comprehensive cuckoo filter, which is configurable and space optimized compared with other implements, and all features mentioned in original paper is available.
* <code>&nbsp;&nbsp;&nbsp;153</code> ![](https://img.shields.io/github/last-commit/agnivade/levenshtein) [levenshtein](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go.
* <code>&nbsp;&nbsp;&nbsp;144</code> ![](https://img.shields.io/github/last-commit/zhenjl/bloom) [bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go.
* <code>&nbsp;&nbsp;&nbsp;140</code> ![](https://img.shields.io/github/last-commit/enriquebris/goconcurrentqueue) [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) - Concurrent FIFO queue.
* <code>&nbsp;&nbsp;&nbsp;137</code> ![](https://img.shields.io/github/last-commit/disksing/iter) [iter](https://github.com/disksing/iter) - Go implementation of C++ STL iterators and algorithms.
* <code>&nbsp;&nbsp;&nbsp;120</code> ![](https://img.shields.io/github/last-commit/TheTannerRyan/ring) [ring](https://github.com/TheTannerRyan/ring) - Go implementation of a high performance, thread safe bloom filter.
* <code>&nbsp;&nbsp;&nbsp;116</code> ![](https://img.shields.io/github/last-commit/aurelien-rainone/go-rquad) [go-rquad](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding.
* <code>&nbsp;&nbsp;&nbsp;107</code> ![](https://img.shields.io/github/last-commit/zhenjl/encoding) [encoding](https://github.com/zhenjl/encoding) - Integer Compression Libraries for Go.
* <code>&nbsp;&nbsp;&nbsp;107</code> ![](https://img.shields.io/github/last-commit/yourbasic/bit) [bit](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions.
* <code>&nbsp;&nbsp;&nbsp;100</code> ![](https://img.shields.io/github/last-commit/rocketlaunchr/remember-go) [remember-go](https://github.com/rocketlaunchr/remember-go) - A universal interface for caching slow database queries (backed by redis, memcached, ristretto, or in-memory).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;94</code> ![](https://img.shields.io/github/last-commit/InVisionApp/conjungo) [conjungo](https://github.com/InVisionApp/conjungo) - A small, powerful and flexible merge library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;74</code> ![](https://img.shields.io/github/last-commit/kelindar/bitmap) [bitmap](https://github.com/kelindar/bitmap) - Dense, zero-allocation, SIMD-enabled bitmap/bitset in Go
* <code>&nbsp;&nbsp;&nbsp;&nbsp;73</code> ![](https://img.shields.io/github/last-commit/gansidui/skiplist) [skiplist](https://github.com/gansidui/skiplist) - Skiplist implementation in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;68</code> ![](https://img.shields.io/github/last-commit/OrlovEvgeny/go-mcache) [go-mcache](https://github.com/OrlovEvgeny/go-mcache) - Fast in-memory key:value store/cache library. Pointer caches.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;63</code> ![](https://img.shields.io/github/last-commit/yourbasic/bloom) [bloom](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> ![](https://img.shields.io/github/last-commit/agext/levenshtein) [levenshtein](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> ![](https://img.shields.io/github/last-commit/seiflotfy/count-min-log) [count-min-log](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;44</code> ![](https://img.shields.io/github/last-commit/superwhiskers/crunch) [crunch](https://github.com/superwhiskers/crunch) - Go package implementing buffers for handling various datatypes easily.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> ![](https://img.shields.io/github/last-commit/kak-tus/nan) [nan](https://github.com/kak-tus/nan) - Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> ![](https://img.shields.io/github/last-commit/zoumo/goset) [goset](https://github.com/zoumo/goset) - A useful Set collection implementation for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> ![](https://img.shields.io/github/last-commit/free/concurrent-writer) [concurrent-writer](https://github.com/free/concurrent-writer) - Highly concurrent drop-in replacement for `bufio.Writer`.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> ![](https://img.shields.io/github/last-commit/emvi/hide) [hide](https://github.com/emvi/hide) - ID type with marshalling to/from hash to prevent sending IDs to clients.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> ![](https://img.shields.io/github/last-commit/hyfather/pipeline) [pipeline](https://github.com/hyfather/pipeline) - An implementation of pipelines with fan-in and fan-out.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/gurukami/typ) [typ](https://github.com/gurukami/typ) - Null Types, Safe primitive type conversion and fetching value from complex structures.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/edwingeng/deque) [deque](https://github.com/edwingeng/deque) - A highly optimized double-ended queue.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/zekroTJA/timedmap) [timedmap](https://github.com/zekroTJA/timedmap) - Map with expiring key-value pairs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> ![](https://img.shields.io/github/last-commit/srfrog/dict) [dict](https://github.com/srfrog/dict) - Python-like dictionaries (dict) for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> ![](https://img.shields.io/github/last-commit/emvi/null) [null](https://github.com/emvi/null) - Nullable Go types that can be marshalled/unmarshalled to/from JSON.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> ![](https://img.shields.io/github/last-commit/amallia/go-ef) [go-ef](https://github.com/amallia/go-ef) - A Go implementation of the Elias-Fano encoding.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> ![](https://img.shields.io/github/last-commit/BlackRabbitt/mspm) [mspm](https://github.com/BlackRabbitt/mspm) - Multi-String Pattern Matching Algorithm for information retrieval.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/viant/ptrie) [ptrie](https://github.com/viant/ptrie) - An implementation of prefix tree.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/StudioSol/set) [set](https://github.com/StudioSol/set) - Simple set data structure implementation in Go using LinkedHashMap.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/lrita/cmap) [cmap](https://github.com/lrita/cmap) - a thread-safe concurrent map for go, support using `interface{}` as key and auto scale up shards.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/perdata/treap) [treap](https://github.com/perdata/treap) - Persistent, fast ordered map using tree heaps.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/nazar256/parapipe) [parapipe](https://github.com/nazar256/parapipe) - FIFO Pipeline which parallels execution on each stage while maintaining the order of messages and results.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/xxjwxc/gofal) [gofal](https://github.com/xxjwxc/gofal) - fractional api for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/MonaxGT/parsefields) [parsefields](https://github.com/MonaxGT/parsefields) - Tools for parse JSON-like logs for collecting unique fields and events.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/tejzpr/ordered-concurrently) [ordered-concurrently](https://github.com/tejzpr/ordered-concurrently) - Go module that processes work concurrently and returns output in a channel in the order of input.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/ihebu/dsu) [dsu](https://github.com/ihebu/dsu) - Disjoint Set data structure implementation in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/yaa110/goterator) [goterator](https://github.com/yaa110/goterator) - Iterator implementation to provide map and reduce functionalities.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/OldPanda/bloomfilter) [bloomfilter](https://github.com/OldPanda/bloomfilter) - Yet another Bloomfilter implementation in Go, compatible with Java's Guava library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> ![](https://img.shields.io/github/last-commit/srfrog/slices) [slices](https://github.com/srfrog/slices) - Functions that operate on slices; like `package strings` but adapted to work with slices.

## Database

*Databases implemented in Go.*

* <code>&nbsp;37971</code> ![](https://img.shields.io/github/last-commit/prometheus/prometheus) [prometheus](https://github.com/prometheus/prometheus) - Monitoring system and time series database.
* <code>&nbsp;28633</code> ![](https://img.shields.io/github/last-commit/pingcap/tidb) [tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1.
* <code>&nbsp;21877</code> ![](https://img.shields.io/github/last-commit/influxdb/influxdb) [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
* <code>&nbsp;21344</code> ![](https://img.shields.io/github/last-commit/cockroachdb/cockroach) [cockroach](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore.
* <code>&nbsp;16424</code> ![](https://img.shields.io/github/last-commit/dgraph-io/dgraph) [dgraph](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database.
* <code>&nbsp;10502</code> ![](https://img.shields.io/github/last-commit/golang/groupcache) [groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
* <code>&nbsp;&nbsp;9538</code> ![](https://img.shields.io/github/last-commit/dgraph-io/badger) [badger](https://github.com/dgraph-io/badger) - Fast key-value store in Go.
* <code>&nbsp;&nbsp;8649</code> ![](https://img.shields.io/github/last-commit/rqlite/rqlite) [rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite.
* <code>&nbsp;&nbsp;5227</code> ![](https://img.shields.io/github/last-commit/pmylund/go-cache) [go-cache](https://github.com/pmylund/go-cache) - In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
* <code>&nbsp;&nbsp;5022</code> ![](https://img.shields.io/github/last-commit/allegro/bigcache) [BigCache](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data.
* <code>&nbsp;&nbsp;4662</code> ![](https://img.shields.io/github/last-commit/etcd-io/bbolt) [bbolt](https://github.com/etcd-io/bbolt) - An embedded key/value database for Go.
* <code>&nbsp;&nbsp;4662</code> ![](https://img.shields.io/github/last-commit/VictoriaMetrics/VictoriaMetrics) [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL.
* <code>&nbsp;&nbsp;4467</code> ![](https://img.shields.io/github/last-commit/syndtr/goleveldb) [goleveldb](https://github.com/syndtr/goleveldb) - Implementation of the <code>&nbsp;26028</code> ![](https://img.shields.io/github/last-commit/google/leveldb) [LevelDB](https://github.com/google/leveldb) key/value database in Go.
* <code>&nbsp;&nbsp;3675</code> ![](https://img.shields.io/github/last-commit/siddontang/ledisdb) [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
* <code>&nbsp;&nbsp;3383</code> ![](https://img.shields.io/github/last-commit/tidwall/buntdb) [buntdb](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.
* <code>&nbsp;&nbsp;3032</code> ![](https://img.shields.io/github/last-commit/codenotary/immudb) [immudb](https://github.com/codenotary/immudb) - immudb is a lightweight, high-speed immutable database for systems and applications written in Go.
* <code>&nbsp;&nbsp;2607</code> ![](https://img.shields.io/github/last-commit/HouzuoGuo/tiedot) [tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang.
* <code>&nbsp;&nbsp;1698</code> ![](https://img.shields.io/github/last-commit/xujiajun/nutsdb) [nutsdb](https://github.com/xujiajun/nutsdb) - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as list, set, sorted set.
* <code>&nbsp;&nbsp;1628</code> ![](https://img.shields.io/github/last-commit/bluele/gcache) [GCache](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC.
* <code>&nbsp;&nbsp;1577</code> ![](https://img.shields.io/github/last-commit/muesli/cache2go) [cache2go](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts.
* <code>&nbsp;&nbsp;1570</code> ![](https://img.shields.io/github/last-commit/roseduan/rosedb) [rosedb](https://github.com/roseduan/rosedb) - An embedded k-v database based on LSM+WAL, supports string, list, hash, set, zset.
* <code>&nbsp;&nbsp;1284</code> ![](https://img.shields.io/github/last-commit/yedf/dtm) [dtm](https://github.com/yedf/dtm) - A distributed transaction manager. Support XA, TCC, SAGA, Reliable Messages.
* <code>&nbsp;&nbsp;1209</code> ![](https://img.shields.io/github/last-commit/VictoriaMetrics/fastcache) [fastcache](https://github.com/VictoriaMetrics/fastcache) - fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead.
* <code>&nbsp;&nbsp;1200</code> ![](https://img.shields.io/github/last-commit/CovenantSQL/CovenantSQL) [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) - CovenantSQL is a SQL database on blockchain.
* <code>&nbsp;&nbsp;1133</code> ![](https://img.shields.io/github/last-commit/hdt3213/godis) [godis](https://github.com/hdt3213/godis) - A Golang implemented high-performance Redis server and cluster.
* <code>&nbsp;&nbsp;1076</code> ![](https://img.shields.io/github/last-commit/peterbourgon/diskv) [diskv](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store.
* <code>&nbsp;&nbsp;&nbsp;875</code> ![](https://img.shields.io/github/last-commit/paranoidguy/databunker) [Databunker](https://github.com/paranoidguy/databunker) - Personally identifiable information (PII) storage service built to comply with GDPR and CCPA.
* <code>&nbsp;&nbsp;&nbsp;822</code> ![](https://img.shields.io/github/last-commit/krotik/eliasdb) [eliasdb](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.
* <code>&nbsp;&nbsp;&nbsp;819</code> ![](https://img.shields.io/github/last-commit/couchbase/moss) [moss](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go.
* <code>&nbsp;&nbsp;&nbsp;801</code> ![](https://img.shields.io/github/last-commit/akrylysov/pogreb) [pogreb](https://github.com/akrylysov/pogreb) - Embedded key-value store for read-heavy workloads.
* <code>&nbsp;&nbsp;&nbsp;764</code> ![](https://img.shields.io/github/last-commit/kelindar/column) [column](https://github.com/kelindar/column) - High-performance, columnar, embeddable in-memory store with bitmap indexing and transactions.
* <code>&nbsp;&nbsp;&nbsp;399</code> ![](https://img.shields.io/github/last-commit/jmhodges/levigo) [levigo](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB.
* <code>&nbsp;&nbsp;&nbsp;293</code> ![](https://img.shields.io/github/last-commit/recoilme/pudge) [pudge](https://github.com/recoilme/pudge) - Fast and simple key/value store written using Go's standard library.
* <code>&nbsp;&nbsp;&nbsp;214</code> ![](https://img.shields.io/github/last-commit/chrislusf/vasto) [Vasto](https://github.com/chrislusf/vasto) - A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption.
* <code>&nbsp;&nbsp;&nbsp;213</code> ![](https://img.shields.io/github/last-commit/go-kivik/kivik) [Kivik](https://github.com/go-kivik/kivik) - Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases.
* <code>&nbsp;&nbsp;&nbsp;188</code> ![](https://img.shields.io/github/last-commit/fern4lvarez/piladb) [piladb](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures.
* <code>&nbsp;&nbsp;&nbsp;128</code> ![](https://img.shields.io/github/last-commit/nanobox-io/golang-scribble) [Scribble](https://github.com/nanobox-io/golang-scribble) - Tiny flat file JSON store.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;97</code> ![](https://img.shields.io/github/last-commit/recoilme/slowpoke) [slowpoke](https://github.com/recoilme/slowpoke) - Key-value store with persistence.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;90</code> ![](https://img.shields.io/github/last-commit/akyoto/cache) [cache](https://github.com/akyoto/cache) - In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;68</code> ![](https://img.shields.io/github/last-commit/unit-io/unitdb) [unitdb](https://github.com/unit-io/unitdb) - Fast timeseries database for IoT, realtime messaging applications. Access unitdb with pubsub over tcp or websocket using github.com/unit-io/unitd application.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> ![](https://img.shields.io/github/last-commit/iwanbk/bcache) [bcache](https://github.com/iwanbk/bcache) - Eventually consistent distributed in-memory cache Go library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> ![](https://img.shields.io/github/last-commit/codingsince1985/couchcache) [couchcache](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> ![](https://img.shields.io/github/last-commit/jameycribbs/hare) [hare](https://github.com/jameycribbs/hare) - A simple database management system that stores each table as a text file of line-delimited JSON.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> ![](https://img.shields.io/github/last-commit/oaStuff/clusteredBigCache) [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) - BigCache with clustering support and individual item expiration.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> ![](https://img.shields.io/github/last-commit/claygod/coffer) [Coffer](https://github.com/claygod/coffer) - Simple ACID key-value database that supports transactions.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/rafaeljesus/tempdb) [tempdb](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> ![](https://img.shields.io/github/last-commit/cheshir/ttlcache) [ttlcache](https://github.com/cheshir/ttlcache) - In-memory key value storage with TTL for each record.
* [Bitcask](https://git.mills.io/prologic/bitcask) - Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL).

*Database schema migration.*

* <code>&nbsp;&nbsp;6864</code> ![](https://img.shields.io/github/last-commit/golang-migrate/migrate) [migrate](https://github.com/golang-migrate/migrate) - Database migrations. CLI and Golang library.
* <code>&nbsp;&nbsp;2190</code> ![](https://img.shields.io/github/last-commit/rubenv/sql-migrate) [sql-migrate](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata.
* <code>&nbsp;&nbsp;1778</code> ![](https://img.shields.io/github/last-commit/pressly/goose) [goose](https://github.com/pressly/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.
* <code>&nbsp;&nbsp;1100</code> ![](https://img.shields.io/github/last-commit/gobuffalo/pop) [soda](https://github.com/gobuffalo/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* <code>&nbsp;&nbsp;&nbsp;925</code> ![](https://img.shields.io/github/last-commit/skeema/skeema) [skeema](https://github.com/skeema/skeema) - Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools.
* <code>&nbsp;&nbsp;&nbsp;643</code> ![](https://img.shields.io/github/last-commit/go-gormigrate/gormigrate) [gormigrate](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM.
* <code>&nbsp;&nbsp;&nbsp;120</code> ![](https://img.shields.io/github/last-commit/GuiaBolso/darwin) [darwin](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go.
* <code>&nbsp;&nbsp;&nbsp;116</code> ![](https://img.shields.io/github/last-commit/lopezator/migrator) [migrator](https://github.com/lopezator/migrator) - Dead simple Go database migration library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;79</code> ![](https://img.shields.io/github/last-commit/robinjoseph08/go-pg-migrations) [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) - A Go package to help write migrations with go-pg/pg.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> ![](https://img.shields.io/github/last-commit/RichardKnop/go-fixtures) [go-fixtures](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang's excellent built-in database/sql library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> ![](https://img.shields.io/github/last-commit/khezen/avro) [avro](https://github.com/khezen/avro) - Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/pravasan/pravasan) [pravasan](https://github.com/pravasan/pravasan) - Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> ![](https://img.shields.io/github/last-commit/larapulse/migrator) [migrator](https://github.com/larapulse/migrator) - MySQL database migrator designed to run migrations to your features and manage database schema update with intuitive go code.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/adlio/schema) [schema](https://github.com/adlio/schema) - Library to embed schema migrations for database/sql-compatible databases inside your Go binaries.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/lawzava/go-pg-migrate) [go-pg-migrate](https://github.com/lawzava/go-pg-migrate) - CLI-friendly package for go-pg migrations management.

*Database tools.*

* <code>&nbsp;12307</code> ![](https://img.shields.io/github/last-commit/youtube/vitess) [vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.
* <code>&nbsp;&nbsp;6953</code> ![](https://img.shields.io/github/last-commit/sosedoff/pgweb) [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser.
* <code>&nbsp;&nbsp;5763</code> ![](https://img.shields.io/github/last-commit/flike/kingshard) [kingshard](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang.
* <code>&nbsp;&nbsp;4183</code> ![](https://img.shields.io/github/last-commit/github/orchestrator) [orchestrator](https://github.com/github/orchestrator) - MySQL replication topology manager & visualizer.
* <code>&nbsp;&nbsp;3549</code> ![](https://img.shields.io/github/last-commit/siddontang/go-mysql-elasticsearch) [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically.
* <code>&nbsp;&nbsp;3170</code> ![](https://img.shields.io/github/last-commit/siddontang/go-mysql) [go-mysql](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication.
* <code>&nbsp;&nbsp;2750</code> ![](https://img.shields.io/github/last-commit/prest/prest) [pREST](https://github.com/prest/prest) - Simplify and accelerate development, ⚡ instant, realtime, high-performance on any Postgres application, existing or new.
* <code>&nbsp;&nbsp;&nbsp;667</code> ![](https://img.shields.io/github/last-commit/Vertamedia/chproxy) [chproxy](https://github.com/Vertamedia/chproxy) - HTTP proxy for ClickHouse database.
* <code>&nbsp;&nbsp;&nbsp;459</code> ![](https://img.shields.io/github/last-commit/cybertec-postgresql/pg_timetable) [pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) - Advanced scheduling for PostgreSQL.
* <code>&nbsp;&nbsp;&nbsp;291</code> ![](https://img.shields.io/github/last-commit/nikepan/clickhouse-bulk) [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) - Collects small insterts and sends big requests to ClickHouse servers.
* <code>&nbsp;&nbsp;&nbsp;174</code> ![](https://img.shields.io/github/last-commit/2tvenom/myreplication) [myreplication](https://github.com/2tvenom/myreplication) - MySql binary log replication listener. Supports statement and row based replication.
* <code>&nbsp;&nbsp;&nbsp;141</code> ![](https://img.shields.io/github/last-commit/knocknote/octillery) [octillery](https://github.com/knocknote/octillery) - Go package for sharding databases ( Supports every ORM or raw SQL ).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> ![](https://img.shields.io/github/last-commit/sj14/dbbench) [dbbench](https://github.com/sj14/dbbench) - Database benchmarking tool with support for several databases and scripts.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> ![](https://img.shields.io/github/last-commit/codingconcepts/datagen) [datagen](https://github.com/codingconcepts/datagen) - A fast data generator that's multi-table aware and supports multi-row DML.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/hexdigest/prep) [prep](https://github.com/hexdigest/prep) - Use prepared SQL statements without changing your code.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/andizzle/rwdb) [rwdb](https://github.com/andizzle/rwdb) - rwdb provides read replica capability for multiple database servers setup.

*SQL query builder, libraries for building and using SQL.*

* <code>&nbsp;&nbsp;4098</code> ![](https://img.shields.io/github/last-commit/Masterminds/squirrel) [Squirrel](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries.
* <code>&nbsp;&nbsp;2830</code> ![](https://img.shields.io/github/last-commit/knq/xo) [xo](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.
* <code>&nbsp;&nbsp;1246</code> ![](https://img.shields.io/github/last-commit/didi/gendry) [gendry](https://github.com/didi/gendry) - Non-invasive SQL builder and powerful data binder.
* <code>&nbsp;&nbsp;1219</code> ![](https://img.shields.io/github/last-commit/doug-martin/goqu) [goqu](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library.
* <code>&nbsp;&nbsp;&nbsp;591</code> ![](https://img.shields.io/github/last-commit/gchaincl/dotsql) [Dotsql](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use them with ease.
* <code>&nbsp;&nbsp;&nbsp;535</code> ![](https://img.shields.io/github/last-commit/go-ozzo/ozzo-dbx) [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities.
* <code>&nbsp;&nbsp;&nbsp;448</code> ![](https://img.shields.io/github/last-commit/go-jet/jet) [jet](https://github.com/go-jet/jet) - Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure.
* <code>&nbsp;&nbsp;&nbsp;307</code> ![](https://img.shields.io/github/last-commit/rocketlaunchr/dbq) [dbq](https://github.com/rocketlaunchr/dbq) - Zero boilerplate database operations for Go.
* <code>&nbsp;&nbsp;&nbsp;228</code> ![](https://img.shields.io/github/last-commit/elgris/sqrl) [sqrl](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance.
* <code>&nbsp;&nbsp;&nbsp;154</code> ![](https://img.shields.io/github/last-commit/lqs/sqlingo) [sqlingo](https://github.com/lqs/sqlingo) - A lightweight DSL to build SQL in Go.
* <code>&nbsp;&nbsp;&nbsp;115</code> ![](https://img.shields.io/github/last-commit/bokwoon95/go-structured-query) [sq](https://github.com/bokwoon95/go-structured-query) - Type-safe SQL builder and struct mapper for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;84</code> ![](https://img.shields.io/github/last-commit/galeone/igor) [igor](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;52</code> ![](https://img.shields.io/github/last-commit/xujiajun/godbal) [godbal](https://github.com/xujiajun/godbal) - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> ![](https://img.shields.io/github/last-commit/arthurkushman/buildsqlx) [buildsqlx](https://github.com/arthurkushman/buildsqlx) - Go database query builder library for PostgreSQL.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> ![](https://img.shields.io/github/last-commit/HnH/qry) [qry](https://github.com/HnH/qry) - Tool that generates constants from files with raw SQL queries.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> ![](https://img.shields.io/github/last-commit/leporo/sqlf) [sqlf](https://github.com/leporo/sqlf) - Fast SQL query builder.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> ![](https://img.shields.io/github/last-commit/twharmon/gosql) [gosql](https://github.com/twharmon/gosql) - SQL Query builder with better null values support.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> ![](https://img.shields.io/github/last-commit/spacetab-io/mpath-go) [mpath](https://github.com/spacetab-io/mpath-go) - MPTT (Modified Preorder Tree Traversal) package for SQL records - materialized path realisation.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code> ![](https://img.shields.io/github/last-commit/pupizoid/ormlite) [ormlite](https://github.com/pupizoid/ormlite) - Lightweight package containing some ORM-like features and helpers for sqlite databases.
* [hasql](https://golang.yandex/hasql) - Library for accessing multi-host SQL database installations.
* [Squalus](https://gitlab.com/qosenergy/squalus) - Thin layer over the Go SQL package that makes it easier to perform queries.

## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
  * <code>&nbsp;11127</code> ![](https://img.shields.io/github/last-commit/go-sql-driver/mysql) [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go.
  * <code>&nbsp;&nbsp;6699</code> ![](https://img.shields.io/github/last-commit/lib/pq) [pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql.
  * <code>&nbsp;&nbsp;4993</code> ![](https://img.shields.io/github/last-commit/mattn/go-sqlite3) [go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that uses database/sql.
  * <code>&nbsp;&nbsp;4335</code> ![](https://img.shields.io/github/last-commit/jackc/pgx) [pgx](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql.
  * <code>&nbsp;&nbsp;1422</code> ![](https://img.shields.io/github/last-commit/denisenkom/go-mssqldb) [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go.
  * <code>&nbsp;&nbsp;&nbsp;553</code> ![](https://img.shields.io/github/last-commit/mattn/go-oci8) [go-oci8](https://github.com/mattn/go-oci8) - Oracle driver for go that uses database/sql.
  * <code>&nbsp;&nbsp;&nbsp;275</code> ![](https://img.shields.io/github/last-commit/godror/godror) [godror](https://github.com/godror/godror) - Oracle driver for Go, using the ODPI-C driver.
  * <code>&nbsp;&nbsp;&nbsp;151</code> ![](https://img.shields.io/github/last-commit/nakagami/firebirdsql) [firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go.
  * <code>&nbsp;&nbsp;&nbsp;120</code> ![](https://img.shields.io/github/last-commit/mattn/go-adodb) [go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that uses database/sql.
  * <code>&nbsp;&nbsp;&nbsp;104</code> ![](https://img.shields.io/github/last-commit/minus5/gofreetds) [gofreetds](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org).
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;76</code> ![](https://img.shields.io/github/last-commit/apache/calcite-avatica-go) [avatica](https://github.com/apache/calcite-avatica-go) - Apache Avatica/Phoenix SQL driver for database/sql.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;68</code> ![](https://img.shields.io/github/last-commit/cvilsmeier/sqinn-go) [Sqinn-Go](https://github.com/cvilsmeier/sqinn-go) - SQLite with pure Go.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/viant/bgc) [bgc](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/alexeyco/pig) [pig](https://github.com/alexeyco/pig) - Simple <code>&nbsp;&nbsp;4335</code> ![](https://img.shields.io/github/last-commit/jackc/pgx) [pgx](https://github.com/jackc/pgx) wrapper to execute and <code>&nbsp;&nbsp;&nbsp;330</code> ![](https://img.shields.io/github/last-commit/georgysavva/scany) [scan](https://github.com/georgysavva/scany) query results easily.
* NoSQL Databases
  * <code>&nbsp;12141</code> ![](https://img.shields.io/github/last-commit/go-redis/redis) [redis](https://github.com/go-redis/redis) - Redis client for Golang.
  * <code>&nbsp;&nbsp;8564</code> ![](https://img.shields.io/github/last-commit/gomodule/redigo) [redigo](https://github.com/gomodule/redigo) - Redigo is a Go client for the Redis database.
  * <code>&nbsp;&nbsp;5958</code> ![](https://img.shields.io/github/last-commit/mongodb/mongo-go-driver) [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - Official MongoDB driver for the Go language.
  * <code>&nbsp;&nbsp;1906</code> ![](https://img.shields.io/github/last-commit/globalsign/mgo) [mgo](https://github.com/globalsign/mgo) - (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.
  * <code>&nbsp;&nbsp;1565</code> ![](https://img.shields.io/github/last-commit/dancannon/gorethink) [gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB.
  * <code>&nbsp;&nbsp;1368</code> ![](https://img.shields.io/github/last-commit/bradfitz/gomemcache) [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language.
  * <code>&nbsp;&nbsp;&nbsp;538</code> ![](https://img.shields.io/github/last-commit/qiniu/qmgo) [qmgo](https://github.com/qiniu/qmgo) - The MongoDB driver for Go. It‘s based on official MongoDB driver but easier to use like Mgo.
  * <code>&nbsp;&nbsp;&nbsp;397</code> ![](https://img.shields.io/github/last-commit/bsm/redeo) [redeo](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services.
  * <code>&nbsp;&nbsp;&nbsp;377</code> ![](https://img.shields.io/github/last-commit/jmcvetta/neoism) [neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang.
  * <code>&nbsp;&nbsp;&nbsp;368</code> ![](https://img.shields.io/github/last-commit/aerospike/aerospike-client-go) [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language.
  * <code>&nbsp;&nbsp;&nbsp;346</code> ![](https://img.shields.io/github/last-commit/kamva/mgm) [mgm](https://github.com/kamva/mgm) - MongoDB model-based ODM for Go (based on official MongoDB driver).
  * <code>&nbsp;&nbsp;&nbsp;327</code> ![](https://img.shields.io/github/last-commit/couchbase/gocb) [gocb](https://github.com/couchbase/gocb) - Official Couchbase Go SDK.
  * <code>&nbsp;&nbsp;&nbsp;313</code> ![](https://img.shields.io/github/last-commit/couchbase/go-couchbase) [go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go.
  * <code>&nbsp;&nbsp;&nbsp;175</code> ![](https://img.shields.io/github/last-commit/nitishm/go-rejson) [go-rejson](https://github.com/nitishm/go-rejson) - Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;93</code> ![](https://img.shields.io/github/last-commit/piaohao/godis) [godis](https://github.com/piaohao/godis) - redis client implement by golang, inspired by jedis.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;76</code> ![](https://img.shields.io/github/last-commit/davemeehan/Neo4j-GO) [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;69</code> ![](https://img.shields.io/github/last-commit/solher/arangolite) [arangolite](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;46</code> ![](https://img.shields.io/github/last-commit/pilosa/go-pilosa) [go-pilosa](https://github.com/pilosa/go-pilosa) - Go client library for Pilosa.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> ![](https://img.shields.io/github/last-commit/couchbase/goforestdb) [forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> ![](https://img.shields.io/github/last-commit/cihangir/neo4j) [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> ![](https://img.shields.io/github/last-commit/zegl/goriak) [goriak](https://github.com/zegl/goriak) - Go language driver for Riak KV.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/shomali11/xredis) [xredis](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/defcronyke/godscache) [godscache](https://github.com/defcronyke/godscache) - A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/viant/asc) [asc](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/btnguyen2k/gocosmos) [gocosmos](https://github.com/btnguyen2k/gocosmos) - REST client and standard `database/sql` driver for Azure Cosmos DB.
  * [gocql](http://gocql.github.io) - Go language driver for Apache Cassandra.
* Search and Analytic Databases.
  * <code>&nbsp;&nbsp;7666</code> ![](https://img.shields.io/github/last-commit/blevesearch/bleve) [bleve](https://github.com/blevesearch/bleve) - Modern text indexing library for go.
  * <code>&nbsp;&nbsp;6105</code> ![](https://img.shields.io/github/last-commit/olivere/elastic) [elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go.
  * <code>&nbsp;&nbsp;5919</code> ![](https://img.shields.io/github/last-commit/go-ego/riot) [riot](https://github.com/go-ego/riot) - Go Open Source, Distributed, Simple and efficient Search Engine.
  * <code>&nbsp;&nbsp;3519</code> ![](https://img.shields.io/github/last-commit/elastic/go-elasticsearch) [go-elasticsearch](https://github.com/elastic/go-elasticsearch) - Official Elasticsearch client for Go.
  * <code>&nbsp;&nbsp;&nbsp;949</code> ![](https://img.shields.io/github/last-commit/mattbaird/elastigo) [elastigo](https://github.com/mattbaird/elastigo) - Elasticsearch client library.
  * <code>&nbsp;&nbsp;&nbsp;763</code> ![](https://img.shields.io/github/last-commit/cch123/elasticsql) [elasticsql](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;79</code> ![](https://img.shields.io/github/last-commit/seiflotfy/skizze) [skizze](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/OwnLocal/goes) [goes](https://github.com/OwnLocal/goes) - Library to interact with Elasticsearch.
* Multiple Backends.
  * <code>&nbsp;13889</code> ![](https://img.shields.io/github/last-commit/google/cayley) [cayley](https://github.com/google/cayley) - Graph database with support for multiple backends.
  * <code>&nbsp;&nbsp;&nbsp;352</code> ![](https://img.shields.io/github/last-commit/philippgille/gokv) [gokv](https://github.com/philippgille/gokv) - Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more).
  * <code>&nbsp;&nbsp;&nbsp;155</code> ![](https://img.shields.io/github/last-commit/fabiorphp/cachego) [cachego](https://github.com/fabiorphp/cachego) - Golang Cache component for multiple drivers.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> ![](https://img.shields.io/github/last-commit/viant/dsc) [dsc](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files.

## Date and Time

*Libraries for working with dates and times.*

* <code>&nbsp;&nbsp;3191</code> ![](https://img.shields.io/github/last-commit/jinzhu/now) [now](https://github.com/jinzhu/now) - Now is a time toolkit for golang.
* <code>&nbsp;&nbsp;1484</code> ![](https://img.shields.io/github/last-commit/araddon/dateparse) [dateparse](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance.
* <code>&nbsp;&nbsp;1150</code> ![](https://img.shields.io/github/last-commit/golang-module/carbon) [carbon](https://github.com/golang-module/carbon) - A simple, semantic and developer-friendly golang package for datetime.
* <code>&nbsp;&nbsp;&nbsp;615</code> ![](https://img.shields.io/github/last-commit/uniplaces/carbon) [carbon](https://github.com/uniplaces/carbon) - Simple Time extension with a lot of util methods, ported from PHP Carbon library.
* <code>&nbsp;&nbsp;&nbsp;395</code> ![](https://img.shields.io/github/last-commit/hako/durafmt) [durafmt](https://github.com/hako/durafmt) - Time duration formatting library for Go.
* <code>&nbsp;&nbsp;&nbsp;186</code> ![](https://img.shields.io/github/last-commit/leekchan/timeutil) [timeutil](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package.
* <code>&nbsp;&nbsp;&nbsp;155</code> ![](https://img.shields.io/github/last-commit/bykof/gostradamus) [gostradamus](https://github.com/bykof/gostradamus) - A Go package for working with dates.
* <code>&nbsp;&nbsp;&nbsp;100</code> ![](https://img.shields.io/github/last-commit/yaa110/go-persian-calendar) [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;93</code> ![](https://img.shields.io/github/last-commit/relvacode/iso8601) [iso8601](https://github.com/relvacode/iso8601) - Efficiently parse ISO8601 date-times without regex.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;74</code> ![](https://img.shields.io/github/last-commit/rickb777/date) [date](https://github.com/rickb777/date) - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;74</code> ![](https://img.shields.io/github/last-commit/SaidinWoT/timespan) [timespan](https://github.com/SaidinWoT/timespan) - For interacting with intervals of time, defined as a start time and a duration.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> ![](https://img.shields.io/github/last-commit/wlbr/feiertage) [feiertage](https://github.com/wlbr/feiertage) - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving...
* <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> ![](https://img.shields.io/github/last-commit/nathan-osman/go-sunrise) [go-sunrise](https://github.com/nathan-osman/go-sunrise) - Calculate the sunrise and sunset times for a given location.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/xhit/go-str2duration) [go-str2duration](https://github.com/xhit/go-str2duration) - Convert string to duration. Support time.Duration returned string and more.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> ![](https://img.shields.io/github/last-commit/GuilhermeCaruso/kair) [kair](https://github.com/GuilhermeCaruso/kair) - Date and Time - Golang Formatting Library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/kirillDanshin/nulltime) [NullTime](https://github.com/kirillDanshin/nulltime) - Nullable `time.Time`.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/1set/cronrange) [cronrange](https://github.com/1set/cronrange) - Parses Cron-style time range expressions, checks if the given time is within any ranges.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/osteele/tuesday) [tuesday](https://github.com/osteele/tuesday) - Ruby-compatible Strftime function.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/awoodbeck/strftime) [strftime](https://github.com/awoodbeck/strftime) - C99-compatible strftime formatter.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/stoewer/go-week) [go-week](https://github.com/stoewer/go-week) - An efficient package to work with ISO8601 week dates.

## Distributed Systems

*Packages that help with building Distributed Systems.*

* <code>&nbsp;36793</code> ![](https://img.shields.io/github/last-commit/coreos/etcd) [raft](https://github.com/coreos/etcd/tree/master/raft) - Go implementation of the Raft consensus protocol, by CoreOS.
* <code>&nbsp;20928</code> ![](https://img.shields.io/github/last-commit/go-kit/kit) [go-kit](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.
* <code>&nbsp;16455</code> ![](https://img.shields.io/github/last-commit/micro/go-micro) [go-micro](https://github.com/micro/go-micro) - A distributed systems development framework.
* <code>&nbsp;14212</code> ![](https://img.shields.io/github/last-commit/grpc/grpc-go) [grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC.
* <code>&nbsp;10268</code> ![](https://img.shields.io/github/last-commit/micro/micro) [micro](https://github.com/micro/micro) - A distributed systems runtime for the cloud and beyond.
* <code>&nbsp;10191</code> ![](https://img.shields.io/github/last-commit/tal-tech/go-zero) [go-zero](https://github.com/tal-tech/go-zero) - A web and rpc framework. It's born to ensure the stability of the busy sites with resilient design. Builtin goctl greatly improves the development productivity.
* <code>&nbsp;&nbsp;9646</code> ![](https://img.shields.io/github/last-commit/nats-io/gnatsd) [NATS](https://github.com/nats-io/gnatsd) - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems.
* <code>&nbsp;&nbsp;5862</code> ![](https://img.shields.io/github/last-commit/smallnest/rpcx) [rpcx](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo.
* <code>&nbsp;&nbsp;4917</code> ![](https://img.shields.io/github/last-commit/hashicorp/raft) [raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp.
* <code>&nbsp;&nbsp;4377</code> ![](https://img.shields.io/github/last-commit/devopsfaith/krakend) [KrakenD](https://github.com/devopsfaith/krakend) - Ultra performant API Gateway framework with middlewares.
* <code>&nbsp;&nbsp;4230</code> ![](https://img.shields.io/github/last-commit/tendermint/tendermint) [tendermint](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.
* <code>&nbsp;&nbsp;3954</code> ![](https://img.shields.io/github/last-commit/anacrolix/torrent) [torrent](https://github.com/anacrolix/torrent) - BitTorrent client package.
* <code>&nbsp;&nbsp;3753</code> ![](https://img.shields.io/github/last-commit/lni/dragonboat) [dragonboat](https://github.com/lni/dragonboat) - A feature complete and high performance multi-group Raft library in Go.
* <code>&nbsp;&nbsp;2976</code> ![](https://img.shields.io/github/last-commit/emitter-io/emitter) [emitter-io](https://github.com/emitter-io/emitter) - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love.
* <code>&nbsp;&nbsp;2974</code> ![](https://img.shields.io/github/last-commit/chrislusf/glow) [glow](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go.
* <code>&nbsp;&nbsp;2865</code> ![](https://img.shields.io/github/last-commit/chrislusf/gleam) [gleam](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed.
* <code>&nbsp;&nbsp;2118</code> ![](https://img.shields.io/github/last-commit/liftbridge-io/liftbridge) [liftbridge](https://github.com/liftbridge-io/liftbridge) - Lightweight, fault-tolerant message streams for NATS.
* <code>&nbsp;&nbsp;1171</code> ![](https://img.shields.io/github/last-commit/hprose/hprose-golang) [hprose](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now.
* <code>&nbsp;&nbsp;&nbsp;691</code> ![](https://img.shields.io/github/last-commit/uber/ringpop-go) [ringpop-go](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications.
* <code>&nbsp;&nbsp;&nbsp;638</code> ![](https://img.shields.io/github/last-commit/valyala/gorpc) [gorpc](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load.
* <code>&nbsp;&nbsp;&nbsp;619</code> ![](https://img.shields.io/github/last-commit/cenkalti/rain) [rain](https://github.com/cenkalti/rain) - BitTorrent client and library.
* <code>&nbsp;&nbsp;&nbsp;598</code> ![](https://img.shields.io/github/last-commit/InVisionApp/go-health) [go-health](https://github.com/InVisionApp/go-health) - Library for enabling asynchronous dependency health checks in your service.
* <code>&nbsp;&nbsp;&nbsp;463</code> ![](https://img.shields.io/github/last-commit/bsm/redislock) [redis-lock](https://github.com/bsm/redislock) - Simplified distributed locking implementation using Redis.
* <code>&nbsp;&nbsp;&nbsp;424</code> ![](https://img.shields.io/github/last-commit/AppsFlyer/go-sundheit) [go-sundheit](https://github.com/AppsFlyer/go-sundheit) - A library built to provide support for defining async service health checks for golang services.
* <code>&nbsp;&nbsp;&nbsp;397</code> ![](https://img.shields.io/github/last-commit/digota/digota) [digota](https://github.com/digota/digota) - grpc ecommerce microservice.
* <code>&nbsp;&nbsp;&nbsp;396</code> ![](https://img.shields.io/github/last-commit/buraksezer/consistent) [consistent](https://github.com/buraksezer/consistent) - Consistent hashing with bounded loads.
* <code>&nbsp;&nbsp;&nbsp;337</code> ![](https://img.shields.io/github/last-commit/ursiform/sleuth) [sleuth](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using <code>&nbsp;&nbsp;7111</code> ![](https://img.shields.io/github/last-commit/zeromq/libzmq) [ZeroMQ](https://github.com/zeromq/libzmq)).
* <code>&nbsp;&nbsp;&nbsp;330</code> ![](https://img.shields.io/github/last-commit/dgryski/go-jump) [go-jump](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function.
* <code>&nbsp;&nbsp;&nbsp;240</code> ![](https://img.shields.io/github/last-commit/lesismal/arpc) [arpc](https://github.com/lesismal/arpc) - More effective network communication, support two-way-calling, notify, broadcast.
* <code>&nbsp;&nbsp;&nbsp;192</code> ![](https://img.shields.io/github/last-commit/anacrolix/dht) [dht](https://github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation.
* <code>&nbsp;&nbsp;&nbsp;181</code> ![](https://img.shields.io/github/last-commit/ybbus/jsonrpc) [jsonrpc](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation.
* <code>&nbsp;&nbsp;&nbsp;150</code> ![](https://img.shields.io/github/last-commit/osamingo/jsonrpc) [jsonrpc](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> ![](https://img.shields.io/github/last-commit/svcavallar/celeriac.v1) [celeriac](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;64</code> ![](https://img.shields.io/github/last-commit/edwingeng/doublejump) [doublejump](https://github.com/edwingeng/doublejump) - A revamped Google's jump consistent hash.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;58</code> ![](https://img.shields.io/github/last-commit/dotchain/dot) [dot](https://github.com/dotchain/dot/) - distributed sync using operational transformation/OT.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;55</code> ![](https://img.shields.io/github/last-commit/jexia/semaphore) [Semaphore](https://github.com/jexia/semaphore) - A straightforward (micro) service orchestrator.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> ![](https://img.shields.io/github/last-commit/italolelis/outboxer) [outboxer](https://github.com/italolelis/outboxer) - Outboxer is a go library that implements the outbox pattern.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> ![](https://img.shields.io/github/last-commit/vectaport/flowgraph) [flowgraph](https://github.com/vectaport/flowgraph) - flow-based programming package.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/dgruber/drmaa) [drmaa](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/pdupub/go-pdu) [go-pdu](https://github.com/pdupub/go-pdu) - A decentralized identity-based social network.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> ![](https://img.shields.io/github/last-commit/sanketplus/go-mysql-lock) [go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) - MySQL based distributed lock.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/tylfin/dynatomic) [dynatomic](https://github.com/tylfin/dynatomic) - A library for using DynamoDB as an atomic counter.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> ![](https://img.shields.io/github/last-commit/gmsec/micro) [gmsec](https://github.com/gmsec/micro) - A Go distributed systems development framework.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/mbrostami/consistenthash) [consistenthash](https://github.com/mbrostami/consistenthash) - Consistent hashing with configurable replicas.
* [pglock](https://cirello.io/pglock) - PostgreSQL-backed distributed locking implementation.
* [dynamolock](https://cirello.io/dynamolock) - DynamoDB-backed distributed locking implementation.
* [pjrpc](https://gitlab.com/pjrpc/pjrpc) - Golang JSON-RPC Server-Client with Protobuf spec.
* [resgate](https://resgate.io/) - Realtime API Gateway for building REST, real time, and RPC APIs, where all clients are synchronized seamlessly.

## Dynamic DNS

*Tools for updating dynamic DNS records.*

* <code>&nbsp;&nbsp;&nbsp;846</code> ![](https://img.shields.io/github/last-commit/timothyye/godns) [GoDNS](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go.
* <code>&nbsp;&nbsp;&nbsp;193</code> ![](https://img.shields.io/github/last-commit/skibish/ddns) [DDNS](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend.
* [dyndns](https://gitlab.com/alcastle/dyndns) - Background Go process to regularly and automatically check your IP Address and make updates to (one or many) Dynamic DNS records for Google domains whenever your address changes.

## Email

*Libraries and tools that implement email creation and sending.*

* <code>&nbsp;&nbsp;8826</code> ![](https://img.shields.io/github/last-commit/mailhog/MailHog) [MailHog](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface.
* <code>&nbsp;&nbsp;2306</code> ![](https://img.shields.io/github/last-commit/matcornic/hermes) [hermes](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails.
* <code>&nbsp;&nbsp;1788</code> ![](https://img.shields.io/github/last-commit/jordan-wright/email) [email](https://github.com/jordan-wright/email) - A robust and flexible email library for Go.
* <code>&nbsp;&nbsp;1326</code> ![](https://img.shields.io/github/last-commit/emersion/go-imap) [go-imap](https://github.com/emersion/go-imap) - IMAP library for clients and servers.
* <code>&nbsp;&nbsp;&nbsp;743</code> ![](https://img.shields.io/github/last-commit/sendgrid/sendgrid-go) [SendGrid](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email.
* <code>&nbsp;&nbsp;&nbsp;535</code> ![](https://img.shields.io/github/last-commit/mailgun/mailgun-go) [mailgun-go](https://github.com/mailgun/mailgun-go) - Go library for sending mail with the Mailgun API.
* <code>&nbsp;&nbsp;&nbsp;276</code> ![](https://img.shields.io/github/last-commit/AfterShip/email-verifier) [email-verifier](https://github.com/AfterShip/email-verifier) - A Go library for email verification without sending any emails.
* <code>&nbsp;&nbsp;&nbsp;211</code> ![](https://img.shields.io/github/last-commit/emersion/go-message) [go-message](https://github.com/emersion/go-message) - Streaming library for the Internet Message Format and mail messages.
* <code>&nbsp;&nbsp;&nbsp;208</code> ![](https://img.shields.io/github/last-commit/hectane/hectane) [Hectane](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API.
* <code>&nbsp;&nbsp;&nbsp;197</code> ![](https://img.shields.io/github/last-commit/aymerick/douceur) [douceur](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails.
* <code>&nbsp;&nbsp;&nbsp;181</code> ![](https://img.shields.io/github/last-commit/xhit/go-simple-mail) [go-simple-mail](https://github.com/xhit/go-simple-mail) - Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;83</code> ![](https://img.shields.io/github/last-commit/mailchain/mailchain) [mailchain](https://github.com/mailchain/mailchain) - Send encrypted emails to blockchain addresses written in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;71</code> ![](https://img.shields.io/github/last-commit/vanng822/go-premailer) [go-premailer](https://github.com/vanng822/go-premailer) - Inline styling for HTML mail in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;70</code> ![](https://img.shields.io/github/last-commit/toorop/go-dkim) [go-dkim](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;64</code> ![](https://img.shields.io/github/last-commit/mailhog/smtp) [smtp](https://github.com/mailhog/smtp) - SMTP server protocol state machine.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/go-email-validator/go-email-validator) [go-email-validator](https://github.com/go-email-validator/go-email-validator) - Modular email validator for syntax, disposable, smtp, etc... checking.
* [chasquid](https://blitiri.com.ar/p/chasquid) - SMTP server written in Go.

## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

* <code>&nbsp;&nbsp;4218</code> ![](https://img.shields.io/github/last-commit/yuin/gopher-lua) [gopher-lua](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go.
* <code>&nbsp;&nbsp;2359</code> ![](https://img.shields.io/github/last-commit/d5/tengo) [tengo](https://github.com/d5/tengo) - Bytecode compiled script language for Go.
* <code>&nbsp;&nbsp;2308</code> ![](https://img.shields.io/github/last-commit/dop251/goja) [goja](https://github.com/dop251/goja) - ECMAScript 5.1(+) implementation in Go.
* <code>&nbsp;&nbsp;2131</code> ![](https://img.shields.io/github/last-commit/Shopify/go-lua) [go-lua](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go.
* <code>&nbsp;&nbsp;1889</code> ![](https://img.shields.io/github/last-commit/antonmedv/expr) [expr](https://github.com/antonmedv/expr) - Expression evaluation engine for Go: fast, non-Turing complete, dynamic typing, static typing.
* <code>&nbsp;&nbsp;1290</code> ![](https://img.shields.io/github/last-commit/sbinet/go-python) [go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API.
* <code>&nbsp;&nbsp;1151</code> ![](https://img.shields.io/github/last-commit/mattn/anko) [anko](https://github.com/mattn/anko) - Scriptable interpreter written in Go.
* <code>&nbsp;&nbsp;&nbsp;855</code> ![](https://img.shields.io/github/last-commit/google/cel-go) [cel-go](https://github.com/google/cel-go) - Fast, portable, non-Turing complete expression evaluation with gradual typing.
* <code>&nbsp;&nbsp;&nbsp;805</code> ![](https://img.shields.io/github/last-commit/deuill/go-php) [go-php](https://github.com/deuill/go-php) - PHP bindings for Go.
* <code>&nbsp;&nbsp;&nbsp;771</code> ![](https://img.shields.io/github/last-commit/olebedev/go-duktape) [go-duktape](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go.
* <code>&nbsp;&nbsp;&nbsp;549</code> ![](https://img.shields.io/github/last-commit/aarzilli/golua) [golua](https://github.com/aarzilli/golua) - Go bindings for Lua C API.
* <code>&nbsp;&nbsp;&nbsp;464</code> ![](https://img.shields.io/github/last-commit/jcla1/gisp) [gisp](https://github.com/jcla1/gisp) - Simple LISP in Go.
* <code>&nbsp;&nbsp;&nbsp;358</code> ![](https://img.shields.io/github/last-commit/PaesslerAG/gval) [gval](https://github.com/PaesslerAG/gval) - A highly customizable expression language written in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;79</code> ![](https://img.shields.io/github/last-commit/gentee/gentee) [gentee](https://github.com/gentee/gentee) - Embeddable scripting programming language.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;52</code> ![](https://img.shields.io/github/last-commit/alexeyco/binder) [binder](https://github.com/alexeyco/binder) - Go to Lua binding library, based on <code>&nbsp;&nbsp;4218</code> ![](https://img.shields.io/github/last-commit/yuin/gopher-lua) [gopher-lua](https://github.com/yuin/gopher-lua).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/ian-kent/purl) [purl](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> ![](https://img.shields.io/github/last-commit/db47h/ngaro) [ngaro](https://github.com/db47h/ngaro) - Embeddable Ngaro VM implementation enabling scripting in Retro.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/krotik/ecal) [ecal](https://github.com/krotik/ecal) - A simple embeddable scripting language which supports concurrent event processing.

## Error Handling

*Libraries for handling errors.*

* <code>&nbsp;&nbsp;7150</code> ![](https://img.shields.io/github/last-commit/pkg/errors) [errors](https://github.com/pkg/errors) - Package that provides simple error handling primitives.
* <code>&nbsp;&nbsp;1314</code> ![](https://img.shields.io/github/last-commit/hashicorp/go-multierror) [go-multierror](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error.
* <code>&nbsp;&nbsp;&nbsp;827</code> ![](https://img.shields.io/github/last-commit/rotisserie/eris) [eris](https://github.com/rotisserie/eris) - A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors.
* <code>&nbsp;&nbsp;&nbsp;757</code> ![](https://img.shields.io/github/last-commit/joomcode/errorx) [errorx](https://github.com/joomcode/errorx) - A feature rich error package with stack traces, composition of errors and more.
* <code>&nbsp;&nbsp;&nbsp;668</code> ![](https://img.shields.io/github/last-commit/ztrue/tracerr) [tracerr](https://github.com/ztrue/tracerr) - Golang errors with stack trace and source fragments.
* <code>&nbsp;&nbsp;&nbsp;398</code> ![](https://img.shields.io/github/last-commit/snwfdhmp/errlog) [errlog](https://github.com/snwfdhmp/errlog) - Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place.
* <code>&nbsp;&nbsp;&nbsp;218</code> ![](https://img.shields.io/github/last-commit/emperror/emperror) [emperror](https://github.com/emperror/emperror) - Error handling tools and best practices for Go libraries and applications.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;98</code> ![](https://img.shields.io/github/last-commit/emperror/errors) [errors](https://github.com/emperror/errors) - Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> ![](https://img.shields.io/github/last-commit/bnkamalesh/errors) [errors](https://github.com/bnkamalesh/errors) - Drop-in replacement for builting Go errors. This is a minimal error handling package with custom error types, user friendly messages, Unwrap & Is. With very easy to use and straightforward helper functions.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/SonicRoshan/falcon) [Falcon](https://github.com/SonicRoshan/falcon) - A Simple Yet Highly Powerful Package For Error Handling.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> ![](https://img.shields.io/github/last-commit/PumpkinSeed/errors) [errors](https://github.com/PumpkinSeed/errors) - The most simple error wrapper with awesome performance and minimal memory overhead.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> ![](https://img.shields.io/github/last-commit/neuronlabs/errors) [errors](https://github.com/neuronlabs/errors) - Simple golang error handling with classification primitives.

## File Handling

*Libraries for handling files and file systems.*

* <code>&nbsp;&nbsp;3897</code> ![](https://img.shields.io/github/last-commit/spf13/afero) [afero](https://github.com/spf13/afero) - FileSystem Abstraction System for Go.
* <code>&nbsp;&nbsp;2492</code> ![](https://img.shields.io/github/last-commit/pdfcpu/pdfcpu) [pdfcpu](https://github.com/pdfcpu/pdfcpu) - PDF processor.
* <code>&nbsp;&nbsp;1249</code> ![](https://img.shields.io/github/last-commit/dundee/gdu) [gdu](https://github.com/dundee/gdu) - Disk usage analyzer with console interface
* <code>&nbsp;&nbsp;&nbsp;674</code> ![](https://img.shields.io/github/last-commit/rjeczalik/notify) [notify](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal.
* <code>&nbsp;&nbsp;&nbsp;328</code> ![](https://img.shields.io/github/last-commit/otiai10/copy) [copy](https://github.com/otiai10/copy) - Copy directory recursively.
* <code>&nbsp;&nbsp;&nbsp;203</code> ![](https://img.shields.io/github/last-commit/bigfile/bigfile) [bigfile](https://github.com/bigfile/bigfile) - A file transfer system, support to manage files with http api, rpc call and ftp client.
* <code>&nbsp;&nbsp;&nbsp;152</code> ![](https://img.shields.io/github/last-commit/viant/afs) [afs](https://github.com/viant/afs) - Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go.
* <code>&nbsp;&nbsp;&nbsp;118</code> ![](https://img.shields.io/github/last-commit/C2FO/vfs) [vfs](https://github.com/C2FO/vfs) - A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;88</code> ![](https://img.shields.io/github/last-commit/artonge/go-csv-tag) [go-csv-tag](https://github.com/artonge/go-csv-tag) - Load csv file using tag.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;74</code> ![](https://img.shields.io/github/last-commit/barasher/go-exiftool) [go-exiftool](https://github.com/barasher/go-exiftool) - Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> ![](https://img.shields.io/github/last-commit/qmuntal/opc) [opc](https://github.com/qmuntal/opc) - Load Open Packaging Conventions (OPC) files for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;64</code> ![](https://img.shields.io/github/last-commit/dixonwille/skywalker) [skywalker](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> ![](https://img.shields.io/github/last-commit/posener/tarfs) [tarfs](https://github.com/posener/tarfs) - Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> ![](https://img.shields.io/github/last-commit/codingsince1985/checksum) [checksum](https://github.com/codingsince1985/checksum) - Compute message digest, like MD5 and SHA256, for large files.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/xis/baraka) [baraka](https://github.com/xis/baraka) - A library to process http file uploads easily.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/parsyl/parquet) [parquet](https://github.com/parsyl/parquet) - Read and write [parquet](https://parquet.apache.org) files.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> ![](https://img.shields.io/github/last-commit/artonge/go-gtfs) [go-gtfs](https://github.com/artonge/go-gtfs) - Load gtfs files in go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> ![](https://img.shields.io/github/last-commit/homedepot/flop) [flop](https://github.com/homedepot/flop) - File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/1set/gut) [gut/yos](https://github.com/1set/gut) - Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/hugocarreira/go-decent-copy) [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) - Copy files for humans.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> ![](https://img.shields.io/github/last-commit/1set/todotxt) [todotxt](https://github.com/1set/todotxt) - Go library for Gina Trapani's [*todo.txt*](http://todotxt.org/) files, supports parsing and manipulating of task lists in the <code>&nbsp;&nbsp;1236</code> ![](https://img.shields.io/github/last-commit/todotxt/todo.txt) [*todo.txt* format](https://github.com/todotxt/todo.txt).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/dastoori/higgs) [higgs](https://github.com/dastoori/higgs) - A tiny cross-platform Go library to hide/unhide files and directories.
* [stl](https://gitlab.com/russoj88/stl) - Modules to read and write STL (stereolithography) files. Concurrent algorithm for reading.

## Financial

*Packages for accounting and finance.*

* <code>&nbsp;&nbsp;3194</code> ![](https://img.shields.io/github/last-commit/shopspring/decimal) [decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers.
* <code>&nbsp;&nbsp;&nbsp;974</code> ![](https://img.shields.io/github/last-commit/rhymond/go-money) [go-money](https://github.com/rhymond/go-money) - Implementation of Fowler's Money pattern.
* <code>&nbsp;&nbsp;&nbsp;663</code> ![](https://img.shields.io/github/last-commit/leekchan/accounting) [accounting](https://github.com/leekchan/accounting) - money and currency formatting for golang.
* <code>&nbsp;&nbsp;&nbsp;534</code> ![](https://img.shields.io/github/last-commit/FlashBoys/go-finance) [go-finance](https://github.com/FlashBoys/go-finance) - Comprehensive financial markets data in Go.
* <code>&nbsp;&nbsp;&nbsp;496</code> ![](https://img.shields.io/github/last-commit/sdcoffey/techan) [techan](https://github.com/sdcoffey/techan) - Technical analysis library with advanced market analysis and trading strategies.
* <code>&nbsp;&nbsp;&nbsp;261</code> ![](https://img.shields.io/github/last-commit/bojanz/currency) [currency](https://github.com/bojanz/currency) - Handles currency amounts, provides currency information and formatting.
* <code>&nbsp;&nbsp;&nbsp;244</code> ![](https://img.shields.io/github/last-commit/moov-io/ach) [ach](https://github.com/moov-io/ach) - A reader, writer, and valdiator for Automated Clearing House (ACH) files.
* <code>&nbsp;&nbsp;&nbsp;211</code> ![](https://img.shields.io/github/last-commit/i25959341/orderbook) [orderbook](https://github.com/i25959341/orderbook) - Matching Engine for Limit Order Book in Golang.
* <code>&nbsp;&nbsp;&nbsp;105</code> ![](https://img.shields.io/github/last-commit/alpeb/go-finance) [go-finance](https://github.com/alpeb/go-finance) - Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;95</code> ![](https://img.shields.io/github/last-commit/claygod/transaction) [transaction](https://github.com/claygod/transaction) - Embedded transactional database of accounts, running in multithreaded mode.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;91</code> ![](https://img.shields.io/github/last-commit/aclindsa/ofxgo) [ofxgo](https://github.com/aclindsa/ofxgo) - Query OFX servers and/or parse the responses (with example command-line client).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;84</code> ![](https://img.shields.io/github/last-commit/dannyvankooten/vat) [vat](https://github.com/dannyvankooten/vat) - VAT number validation & EU VAT rates.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;61</code> ![](https://img.shields.io/github/last-commit/BoltApp/sleet) [sleet](https://github.com/BoltApp/sleet) - One unified interface for multiple Payment Service Providers (PsP) to process online payment.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;60</code> ![](https://img.shields.io/github/last-commit/m1/go-finnhub) [go-finnhub](https://github.com/m1/go-finnhub) - Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> ![](https://img.shields.io/github/last-commit/bnkamalesh/currency) [currency](https://github.com/bnkamalesh/currency) - High performant & accurate currency computation package.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> ![](https://img.shields.io/github/last-commit/newity/fastme) [fastme](https://github.com/newity/fastme) - Fast extensible matching engine Go implementation.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/jovandeginste/payme) [payme](https://github.com/jovandeginste/payme) - QR code generator (ASCII & PNG) for SEPA payments.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/pieterclaerhout/go-finance) [go-finance](https://github.com/pieterclaerhout/go-finance) - Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers.

## Forms

*Libraries for working with forms.*

* <code>&nbsp;&nbsp;1188</code> ![](https://img.shields.io/github/last-commit/justinas/nosurf) [nosurf](https://github.com/justinas/nosurf) - CSRF protection middleware for Go.
* <code>&nbsp;&nbsp;&nbsp;780</code> ![](https://img.shields.io/github/last-commit/mholt/binding) [binding](https://github.com/mholt/binding) - Binds form and JSON data from net/http Request to struct.
* <code>&nbsp;&nbsp;&nbsp;683</code> ![](https://img.shields.io/github/last-commit/gorilla/csrf) [gorilla/csrf](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services.
* <code>&nbsp;&nbsp;&nbsp;488</code> ![](https://img.shields.io/github/last-commit/go-playground/form) [form](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support.
* <code>&nbsp;&nbsp;&nbsp;225</code> ![](https://img.shields.io/github/last-commit/leebenson/conform) [conform](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags.
* <code>&nbsp;&nbsp;&nbsp;163</code> ![](https://img.shields.io/github/last-commit/monoculum/formam) [formam](https://github.com/monoculum/formam) - decode form's values into a struct.
* <code>&nbsp;&nbsp;&nbsp;122</code> ![](https://img.shields.io/github/last-commit/albrow/forms) [forms](https://github.com/albrow/forms) - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;57</code> ![](https://img.shields.io/github/last-commit/sonh/qs) [qs](https://github.com/sonh/qs) - Go module for encoding structs into URL query parameters.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> ![](https://img.shields.io/github/last-commit/robfig/bind) [bind](https://github.com/robfig/bind) - Bind form data to any Go values.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/tomwright/queryparam) [queryparam](https://github.com/tomwright/queryparam) - Decode `url.Values` into usable struct values of standard or custom types.

## Functional

*Packages to support functional programming in Go.*

* <code>&nbsp;&nbsp;1204</code> ![](https://img.shields.io/github/last-commit/tobyhede/go-underscore) [go-underscore](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities.
* <code>&nbsp;&nbsp;&nbsp;187</code> ![](https://img.shields.io/github/last-commit/TeaEntityLab/fpGo) [fpGo](https://github.com/TeaEntityLab/fpGo) - Monad, Functional Programming features for Golang.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;93</code> ![](https://img.shields.io/github/last-commit/seborama/fuego) [fuego](https://github.com/seborama/fuego) - Functional Experiment in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;84</code> ![](https://img.shields.io/github/last-commit/rbrahul/gofp) [gofp](https://github.com/rbrahul/gofp) - A lodash like powerful utility library for Golang.

## Game Development

*Awesome game development libraries.*

* <code>&nbsp;&nbsp;4877</code> ![](https://img.shields.io/github/last-commit/hajimehoshi/ebiten) [Ebiten](https://github.com/hajimehoshi/ebiten) - dead simple 2D game library in Go.
* <code>&nbsp;&nbsp;4088</code> ![](https://img.shields.io/github/last-commit/name5566/leaf) [Leaf](https://github.com/name5566/leaf) - Lightweight game server framework.
* <code>&nbsp;&nbsp;3583</code> ![](https://img.shields.io/github/last-commit/faiface/pixel) [Pixel](https://github.com/faiface/pixel) - Hand-crafted 2D game library in Go.
* <code>&nbsp;&nbsp;1910</code> ![](https://img.shields.io/github/last-commit/xiaonanln/goworld) [goworld](https://github.com/xiaonanln/goworld) - Scalable game server engine, featuring space-entity framework and hot-swapping.
* <code>&nbsp;&nbsp;1766</code> ![](https://img.shields.io/github/last-commit/lonng/nano) [nano](https://github.com/lonng/nano) - Lightweight, facility, high performance golang based game server framework.
* <code>&nbsp;&nbsp;1586</code> ![](https://img.shields.io/github/last-commit/veandco/go-sdl2) [go-sdl2](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/).
* <code>&nbsp;&nbsp;1514</code> ![](https://img.shields.io/github/last-commit/g3n/engine) [g3n](https://github.com/g3n/engine) - Go 3D Game Engine.
* <code>&nbsp;&nbsp;1400</code> ![](https://img.shields.io/github/last-commit/EngoEngine/engo) [engo](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm.
* <code>&nbsp;&nbsp;1219</code> ![](https://img.shields.io/github/last-commit/JoelOtter/termloop) [termloop](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox.
* <code>&nbsp;&nbsp;1146</code> ![](https://img.shields.io/github/last-commit/xtaci/gonet) [gonet](https://github.com/xtaci/gonet) - Game server skeleton implemented with golang.
* <code>&nbsp;&nbsp;1111</code> ![](https://img.shields.io/github/last-commit/topfreegames/pitaya) [Pitaya](https://github.com/topfreegames/pitaya) - Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK.
* <code>&nbsp;&nbsp;&nbsp;911</code> ![](https://img.shields.io/github/last-commit/oakmound/oak) [Oak](https://github.com/oakmound/oak) - Pure Go game engine.
* <code>&nbsp;&nbsp;&nbsp;631</code> ![](https://img.shields.io/github/last-commit/gen2brain/raylib-go) [raylib-go](https://github.com/gen2brain/raylib-go) - Go bindings for [raylib](http://www.raylib.com/), a simple and easy-to-use library to learn videogames programming.
* <code>&nbsp;&nbsp;&nbsp;496</code> ![](https://img.shields.io/github/last-commit/azul3d/engine) [Azul3D](https://github.com/azul3d/engine) - 3D game engine written in Go.
* <code>&nbsp;&nbsp;&nbsp;440</code> ![](https://img.shields.io/github/last-commit/beefsack/go-astar) [go-astar](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm.
* <code>&nbsp;&nbsp;&nbsp;203</code> ![](https://img.shields.io/github/last-commit/ungerik/go3d) [go3d](https://github.com/ungerik/go3d) - Performance oriented 2D/3D math package for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> ![](https://img.shields.io/github/last-commit/gonutz/prototype) [prototype](https://github.com/gonutz/prototype) - Cross-platform (Windows/Linux/Mac) library for creating desktop games using a minimal API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/kelindar/tile) [tile](https://github.com/kelindar/tile) - Data-oriented and cache-friendly 2D Grid library (TileMap), includes pathfinding, observers and import/export.

## Generation and Generics

*Tools to enhance the language with features like generics via code generation.*

* <code>&nbsp;&nbsp;2620</code> ![](https://img.shields.io/github/last-commit/ahmetalpbalkan/go-linq) [go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go.
* <code>&nbsp;&nbsp;2102</code> ![](https://img.shields.io/github/last-commit/dave/jennifer) [jennifer](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates.
* <code>&nbsp;&nbsp;1306</code> ![](https://img.shields.io/github/last-commit/clipperhouse/gen) [gen](https://github.com/clipperhouse/gen) - Code generation tool for ‘generics’-like functionality.
* <code>&nbsp;&nbsp;&nbsp;903</code> ![](https://img.shields.io/github/last-commit/awalterschulze/goderive) [goderive](https://github.com/awalterschulze/goderive) - Derives functions from input types.
* <code>&nbsp;&nbsp;&nbsp;527</code> ![](https://img.shields.io/github/last-commit/hexdigest/gowrap) [GoWrap](https://github.com/hexdigest/gowrap) - Generate decorators for Go interfaces using simple templates.
* <code>&nbsp;&nbsp;&nbsp;305</code> ![](https://img.shields.io/github/last-commit/rjeczalik/interfaces) [interfaces](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions.
* <code>&nbsp;&nbsp;&nbsp;219</code> ![](https://img.shields.io/github/last-commit/abice/go-enum) [go-enum](https://github.com/abice/go-enum) - Code generation for enums from code comments.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;97</code> ![](https://img.shields.io/github/last-commit/ungerik/pkgreflect) [pkgreflect](https://github.com/ungerik/pkgreflect) - Go preprocessor for package scoped reflection.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> ![](https://img.shields.io/github/last-commit/t0pep0/efaceconv) [efaceconv](https://github.com/t0pep0/efaceconv) - Code generation tool for high performance conversion from interface{} to immutable type without allocations.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> ![](https://img.shields.io/github/last-commit/wzshiming/gotype) [gotype](https://github.com/wzshiming/gotype) - Golang source code parsing, usage like reflect package.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/senselogic/GENERIS) [generis](https://github.com/senselogic/GENERIS) - Code generation tool providing generics, free-form macros, conditional compilation and HTML templating.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> ![](https://img.shields.io/github/last-commit/pieterclaerhout/go-xray) [go-xray](https://github.com/pieterclaerhout/go-xray) - Helpers for making the use of reflection easier.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/xiaoxin01/typeregistry) [typeregistry](https://github.com/xiaoxin01/typeregistry) - A library to create type dynamically.

## Geographic

*Geographic tools and servers*

* <code>&nbsp;&nbsp;7565</code> ![](https://img.shields.io/github/last-commit/tidwall/tile38) [Tile38](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing.
* <code>&nbsp;&nbsp;1248</code> ![](https://img.shields.io/github/last-commit/golang/geo) [S2 geometry](https://github.com/golang/geo) - S2 geometry library in Go.
* <code>&nbsp;&nbsp;&nbsp;255</code> ![](https://img.shields.io/github/last-commit/consbio/mbtileserver) [mbtileserver](https://github.com/consbio/mbtileserver) - A simple Go-based server for map tiles stored in mbtiles format.
* <code>&nbsp;&nbsp;&nbsp;170</code> ![](https://img.shields.io/github/last-commit/paulmach/osm) [osm](https://github.com/paulmach/osm) - Library for reading, writing and working with OpenStreetMap data and APIs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;63</code> ![](https://img.shields.io/github/last-commit/wroge/wgs84) [WGS84](https://github.com/wroge/wgs84) - Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;57</code> ![](https://img.shields.io/github/last-commit/hishamkaram/geoserver) [geoserver](https://github.com/hishamkaram/geoserver) - geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> ![](https://img.shields.io/github/last-commit/hishamkaram/gismanager) [gismanager](https://github.com/hishamkaram/gismanager) - Publish Your GIS Data(Vector Data) to PostGIS and Geoserver.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> ![](https://img.shields.io/github/last-commit/peterstace/simplefeatures) [simplefeatures](https://github.com/peterstace/simplefeatures) - simplesfeatures is a 2D geometry library that provides Go types that model geometries, as well as algorithms that operate on them.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> ![](https://img.shields.io/github/last-commit/maguro/pbf) [pbf](https://github.com/maguro/pbf) - OpenStreetMap PBF golang encoder/decoder.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> ![](https://img.shields.io/github/last-commit/pantrif/s2-geojson) [S2 geojson](https://github.com/pantrif/s2-geojson) - Convert geojson to s2 cells & demonstrating some S2 geometry features on map.

## Go Compilers

*Tools for compiling Go to other languages.*

* <code>&nbsp;10365</code> ![](https://img.shields.io/github/last-commit/gopherjs/gopherjs) [gopherjs](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript.
* <code>&nbsp;&nbsp;&nbsp;411</code> ![](https://img.shields.io/github/last-commit/tardisgo/tardisgo) [tardisgo](https://github.com/tardisgo/tardisgo) - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler.
* <code>&nbsp;&nbsp;&nbsp;276</code> ![](https://img.shields.io/github/last-commit/Konstantin8105/c4go) [c4go](https://github.com/Konstantin8105/c4go) - Transpile C code to Go code.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> ![](https://img.shields.io/github/last-commit/Konstantin8105/f4go) [f4go](https://github.com/Konstantin8105/f4go) - Transpile FORTRAN 77 code to Go code.

## Goroutines

*Tools for managing and working with Goroutines.*

* <code>&nbsp;&nbsp;6138</code> ![](https://img.shields.io/github/last-commit/panjf2000/ants) [ants](https://github.com/panjf2000/ants) - A high-performance and low-cost goroutine pool in Go.
* <code>&nbsp;&nbsp;2592</code> ![](https://img.shields.io/github/last-commit/benmanns/goworker) [goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker.
* <code>&nbsp;&nbsp;2539</code> ![](https://img.shields.io/github/last-commit/Jeffail/tunny) [tunny](https://github.com/Jeffail/tunny) - Goroutine pool for golang.
* <code>&nbsp;&nbsp;&nbsp;646</code> ![](https://img.shields.io/github/last-commit/ivpusic/grpool) [grpool](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool.
* <code>&nbsp;&nbsp;&nbsp;628</code> ![](https://img.shields.io/github/last-commit/go-playground/pool) [pool](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation.
* <code>&nbsp;&nbsp;&nbsp;595</code> ![](https://img.shields.io/github/last-commit/gammazero/workerpool) [workerpool](https://github.com/gammazero/workerpool) - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued.
* <code>&nbsp;&nbsp;&nbsp;313</code> ![](https://img.shields.io/github/last-commit/xxjwxc/gowp) [gowp](https://github.com/xxjwxc/gowp) - gowp is concurrency limiting goroutine pool.
* <code>&nbsp;&nbsp;&nbsp;257</code> ![](https://img.shields.io/github/last-commit/alitto/pond) [pond](https://github.com/alitto/pond) - Minimalistic and High-performance goroutine worker pool written in Go.
* <code>&nbsp;&nbsp;&nbsp;203</code> ![](https://img.shields.io/github/last-commit/workanator/go-floc) [go-floc](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease.
* <code>&nbsp;&nbsp;&nbsp;171</code> ![](https://img.shields.io/github/last-commit/kamildrazkiewicz/go-flow) [go-flow](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order.
* <code>&nbsp;&nbsp;&nbsp;120</code> ![](https://img.shields.io/github/last-commit/marusama/semaphore) [semaphore](https://github.com/marusama/semaphore) - Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations).
* <code>&nbsp;&nbsp;&nbsp;116</code> ![](https://img.shields.io/github/last-commit/borderstech/artifex) [artifex](https://github.com/borderstech/artifex) - Simple in-memory job queue for Golang using worker-based dispatching.
* <code>&nbsp;&nbsp;&nbsp;112</code> ![](https://img.shields.io/github/last-commit/catmullet/go-workers) [go-workers](https://github.com/catmullet/go-workers) - Easily and safely run workers for large data processing pipelines.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;89</code> ![](https://img.shields.io/github/last-commit/studiosol/async) [async](https://github.com/studiosol/async) - A safe way to execute functions asynchronously, recovering them in case of panic.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> ![](https://img.shields.io/github/last-commit/kamilsk/semaphore) [semaphore](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;84</code> ![](https://img.shields.io/github/last-commit/neilotoole/errgroup) [neilotoole/errgroup](https://github.com/neilotoole/errgroup) - Drop-in alternative to `sync/errgroup`, limited to a pool of N worker goroutines.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;80</code> ![](https://img.shields.io/github/last-commit/Sherifabdlnaby/gpool) [gpool](https://github.com/Sherifabdlnaby/gpool) - manages a resizeable pool of context-aware goroutines to bound concurrency.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;79</code> ![](https://img.shields.io/github/last-commit/vardius/worker-pool) [worker-pool](https://github.com/vardius/worker-pool) - goworker is a Go simple async worker pool.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;71</code> ![](https://img.shields.io/github/last-commit/marusama/cyclicbarrier) [cyclicbarrier](https://github.com/marusama/cyclicbarrier) - CyclicBarrier for golang.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;60</code> ![](https://img.shields.io/github/last-commit/vardius/gollback) [gollback](https://github.com/vardius/gollback) - asynchronous simple function utilities, for managing execution of closures and callbacks.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;60</code> ![](https://img.shields.io/github/last-commit/shettyh/threadpool) [threadpool](https://github.com/shettyh/threadpool) - Golang threadpool implementation.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;56</code> ![](https://img.shields.io/github/last-commit/AaronJan/Hunch) [Hunch](https://github.com/AaronJan/Hunch) - Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> ![](https://img.shields.io/github/last-commit/x-mod/routine) [routine](https://github.com/x-mod/routine) - go routine control with context, support: Main, Go, Pool and some useful Executors.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/arunsworld/nursery) [nursery](https://github.com/arunsworld/nursery) - Structured concurrency in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/dirkaholic/kyoo) [kyoo](https://github.com/dirkaholic/kyoo) - Provides an unlimited job queue and concurrent worker pools.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> ![](https://img.shields.io/github/last-commit/rafaeljesus/parallel-fn) [parallel-fn](https://github.com/rafaeljesus/parallel-fn) - Run functions in parallel.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/reugn/async) [async](https://github.com/reugn/async) - An alternative sync library for Go (Future, Promise, Locks).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/zenthangplus/goccm) [goccm](https://github.com/zenthangplus/goccm) - Go Concurrency Manager package limits the number of goroutines that allowed to run concurrently.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> ![](https://img.shields.io/github/last-commit/subchen/go-trylock) [go-trylock](https://github.com/subchen/go-trylock) - TryLock support on read-write lock for Golang.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> ![](https://img.shields.io/github/last-commit/pieterclaerhout/go-waitgroup) [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) - Like `sync.WaitGroup` with error handling and concurrency control.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> ![](https://img.shields.io/github/last-commit/ssgreg/stl) [stl](https://github.com/ssgreg/stl) - Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/ddelizia/channelify) [channelify](https://github.com/ddelizia/channelify) - Transform your function to return channels for easy and powerful parallel processing.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> ![](https://img.shields.io/github/last-commit/loveleshsharma/gohive) [gohive](https://github.com/loveleshsharma/gohive) - A highly performant and easy to use Goroutine pool for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/ITcathyh/conexec) [conexec](https://github.com/ITcathyh/conexec) - A concurrent toolkit to help execute funcs concurrently in an efficient and safe way. It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/hamed-yousefi/gowl) [gowl](https://github.com/hamed-yousefi/gowl) - Gowl is a process management and process monitoring tool at once. An infinite worker pool gives you the ability to control the pool and processes and monitor their status.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/AnikHasibul/queue) [queue](https://github.com/AnikHasibul/queue) - Gives you a `sync.WaitGroup` like queue group accessibility. Helps you to throttle and limit goroutines, wait for the end of the all goroutines and much more.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/duanckham/hands) [hands](https://github.com/duanckham/hands) - A process controller used to control the execution and return strategies of multiple goroutines.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/nikhilsaraf/go-tools) [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) - Manage a pool of goroutines using this lightweight library with a simple API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/hexdigest/execpool) [execpool](https://github.com/hexdigest/execpool) - A pool built around exec.Cmd that spins up a given number of processes in advance and attaches stdin and stdout to them when needed. Very similar to FastCGI or Apache Prefork MPM but works for any command.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/vivek-ng/concurrency-limiter) [concurrency-limiter](https://github.com/vivek-ng/concurrency-limiter) - Concurrency limiter with support for timeouts , dynamic priority and context cancellation of goroutines.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code> ![](https://img.shields.io/github/last-commit/kamilsk/breaker) [breaker](https://github.com/kamilsk/breaker) - Flexible mechanism to make execution flow interruptible.
* [oversight](https://cirello.io/oversight) - Oversight is a complete implementation of the Erlang supervision trees.

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

* <code>&nbsp;13650</code> ![](https://img.shields.io/github/last-commit/fyne-io/fyne) [fyne](https://github.com/fyne-io/fyne) - Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android.
* <code>&nbsp;&nbsp;8677</code> ![](https://img.shields.io/github/last-commit/therecipe/qt) [qt](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi).
* <code>&nbsp;&nbsp;8670</code> ![](https://img.shields.io/github/last-commit/zserge/webview) [webview](https://github.com/zserge/webview) - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux).
* <code>&nbsp;&nbsp;7923</code> ![](https://img.shields.io/github/last-commit/andlabs/ui) [ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform.
* <code>&nbsp;&nbsp;5577</code> ![](https://img.shields.io/github/last-commit/lxn/walk) [walk](https://github.com/lxn/walk) - Windows application library kit for Go.
* <code>&nbsp;&nbsp;4990</code> ![](https://img.shields.io/github/last-commit/murlokswarm/app) [app](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress.
* <code>&nbsp;&nbsp;3924</code> ![](https://img.shields.io/github/last-commit/asticode/go-astilectron) [go-astilectron](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron).
* <code>&nbsp;&nbsp;2147</code> ![](https://img.shields.io/github/last-commit/sciter-sdk/go-sciter) [go-sciter](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform.
* <code>&nbsp;&nbsp;1538</code> ![](https://img.shields.io/github/last-commit/gotk3/gotk3) [gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3.
* <code>&nbsp;&nbsp;&nbsp;322</code> ![](https://img.shields.io/github/last-commit/dtylman/gowd) [gowd](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform.
* [go-gtk](http://mattn.github.io/go-gtk/) - Go bindings for GTK.
* [Wails](https://wails.app) - Mac, Windows, Linux desktop apps with HTML UI using built-in OS HTML renderer.

*Interaction*

* <code>&nbsp;&nbsp;6783</code> ![](https://img.shields.io/github/last-commit/go-vgo/robotgo) [robotgo](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other.
* <code>&nbsp;&nbsp;1896</code> ![](https://img.shields.io/github/last-commit/getlantern/systray) [systray](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area.
* <code>&nbsp;&nbsp;&nbsp;543</code> ![](https://img.shields.io/github/last-commit/deckarep/gosx-notifier) [gosx-notifier](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go.
* <code>&nbsp;&nbsp;&nbsp;213</code> ![](https://img.shields.io/github/last-commit/shurcooL/trayhost) [trayhost](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar.
* <code>&nbsp;&nbsp;&nbsp;150</code> ![](https://img.shields.io/github/last-commit/ncruces/zenity) [zenity](https://github.com/ncruces/zenity) - Cross-platform Go library and CLI to create simple dialogs that interact graphically with the user.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/dawidd6/go-appindicator) [go-appindicator](https://github.com/dawidd6/go-appindicator) - Go bindings for libappindicator3 C library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/prashantgupta24/activity-tracker) [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) - OSX library to notify about any (pluggable) activity on your machine.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/prashantgupta24/mac-sleep-notifier) [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) - OSX Sleep/Wake notifications in golang.

## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See <code>&nbsp;&nbsp;1185</code> ![](https://img.shields.io/github/last-commit/rakyll/go-hardware) [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

## Images

*Libraries for manipulating images.*

* <code>&nbsp;&nbsp;4244</code> ![](https://img.shields.io/github/last-commit/hybridgroup/gocv) [gocv](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3.3+.
* <code>&nbsp;&nbsp;3856</code> ![](https://img.shields.io/github/last-commit/disintegration/imaging) [imaging](https://github.com/disintegration/imaging) - Simple Go image processing package.
* <code>&nbsp;&nbsp;3773</code> ![](https://img.shields.io/github/last-commit/h2non/imaginary) [imaginary](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing.
* <code>&nbsp;&nbsp;3249</code> ![](https://img.shields.io/github/last-commit/anthonynsimon/bild) [bild](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go.
* <code>&nbsp;&nbsp;2964</code> ![](https://img.shields.io/github/last-commit/fogleman/gg) [gg](https://github.com/fogleman/gg) - 2D rendering in pure Go.
* <code>&nbsp;&nbsp;2934</code> ![](https://img.shields.io/github/last-commit/fogleman/ln) [ln](https://github.com/fogleman/ln) - 3D line art rendering in Go.
* <code>&nbsp;&nbsp;2690</code> ![](https://img.shields.io/github/last-commit/nfnt/resize) [resize](https://github.com/nfnt/resize) - Image resizing for Go with common interpolation methods.
* <code>&nbsp;&nbsp;1958</code> ![](https://img.shields.io/github/last-commit/fogleman/pt) [pt](https://github.com/fogleman/pt) - Path tracing engine written in Go.
* <code>&nbsp;&nbsp;1697</code> ![](https://img.shields.io/github/last-commit/ajstarks/svgo) [svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation.
* <code>&nbsp;&nbsp;1532</code> ![](https://img.shields.io/github/last-commit/muesli/smartcrop) [smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes.
* <code>&nbsp;&nbsp;1516</code> ![](https://img.shields.io/github/last-commit/h2non/bimg) [bimg](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips.
* <code>&nbsp;&nbsp;1503</code> ![](https://img.shields.io/github/last-commit/thoas/picfit) [picfit](https://github.com/thoas/picfit) - An image resizing server written in Go.
* <code>&nbsp;&nbsp;1458</code> ![](https://img.shields.io/github/last-commit/disintegration/gift) [gift](https://github.com/disintegration/gift) - Package of image processing filters.
* <code>&nbsp;&nbsp;1334</code> ![](https://img.shields.io/github/last-commit/gographics/imagick) [imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API.
* <code>&nbsp;&nbsp;1245</code> ![](https://img.shields.io/github/last-commit/lazywei/go-opencv) [go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV.
* <code>&nbsp;&nbsp;1129</code> ![](https://img.shields.io/github/last-commit/pravj/geopattern) [geopattern](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string.
* <code>&nbsp;&nbsp;&nbsp;938</code> ![](https://img.shields.io/github/last-commit/DimitarPetrov/stegify) [stegify](https://github.com/DimitarPetrov/stegify) - Go tool for LSB steganography, capable of hiding any file within an image.
* <code>&nbsp;&nbsp;&nbsp;761</code> ![](https://img.shields.io/github/last-commit/tdewolff/canvas) [canvas](https://github.com/tdewolff/canvas) - Vector graphics to PDF, SVG or rasterized image.
* <code>&nbsp;&nbsp;&nbsp;565</code> ![](https://img.shields.io/github/last-commit/qeesung/image2ascii) [image2ascii](https://github.com/qeesung/image2ascii) - Convert image to ASCII.
* <code>&nbsp;&nbsp;&nbsp;496</code> ![](https://img.shields.io/github/last-commit/lucasepe/draft) [draft](https://github.com/lucasepe/draft) - Generate High Level Microservice Architecture diagrams for GraphViz using simple YAML syntax.
* <code>&nbsp;&nbsp;&nbsp;493</code> ![](https://img.shields.io/github/last-commit/davidbyttow/govips) [govips](https://github.com/davidbyttow/govips) - A lightning fast image processing and resizing library for Go.
* <code>&nbsp;&nbsp;&nbsp;449</code> ![](https://img.shields.io/github/last-commit/o1egl/govatar) [govatar](https://github.com/o1egl/govatar) - Library and CMD tool for generating funny avatars.
* <code>&nbsp;&nbsp;&nbsp;436</code> ![](https://img.shields.io/github/last-commit/aldor007/mort) [mort](https://github.com/aldor007/mort) - Storage and image processing server written in Go.
* <code>&nbsp;&nbsp;&nbsp;418</code> ![](https://img.shields.io/github/last-commit/corona10/goimagehash) [goimagehash](https://github.com/corona10/goimagehash) - Go Perceptual image hashing package.
* <code>&nbsp;&nbsp;&nbsp;334</code> ![](https://img.shields.io/github/last-commit/koyachi/go-nude) [go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go.
* <code>&nbsp;&nbsp;&nbsp;200</code> ![](https://img.shields.io/github/last-commit/bamiaux/rez) [rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD.
* <code>&nbsp;&nbsp;&nbsp;169</code> ![](https://img.shields.io/github/last-commit/gojek/darkroom) [darkroom](https://github.com/gojek/darkroom) - An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency.
* <code>&nbsp;&nbsp;&nbsp;143</code> ![](https://img.shields.io/github/last-commit/noelyahan/mergi) [mergi](https://github.com/noelyahan/mergi) - Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate).
* <code>&nbsp;&nbsp;&nbsp;138</code> ![](https://img.shields.io/github/last-commit/hawx/img) [img](https://github.com/hawx/img) - Selection of image manipulation tools.
* <code>&nbsp;&nbsp;&nbsp;115</code> ![](https://img.shields.io/github/last-commit/qmuntal/gltf) [gltf](https://github.com/qmuntal/gltf) - Efficient and robust glTF 2.0 reader, writer and validator.
* <code>&nbsp;&nbsp;&nbsp;110</code> ![](https://img.shields.io/github/last-commit/ungerik/go-cairo) [go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library.
* <code>&nbsp;&nbsp;&nbsp;109</code> ![](https://img.shields.io/github/last-commit/auyer/steganography) [steganography](https://github.com/auyer/steganography) - Pure Go Library for LSB steganography.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;69</code> ![](https://img.shields.io/github/last-commit/aofei/cameron) [cameron](https://github.com/aofei/cameron) - An avatar generator for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> ![](https://img.shields.io/github/last-commit/bolknote/go-gd) [go-gd](https://github.com/bolknote/go-gd) - Go binding for GD library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;43</code> ![](https://img.shields.io/github/last-commit/shomali11/gridder) [gridder](https://github.com/shomali11/gridder) - A Grid based 2D Graphics library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> ![](https://img.shields.io/github/last-commit/corona10/goimghdr) [goimghdr](https://github.com/corona10/goimghdr) - The imghdr module determines the type of image contained in a file for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/ftrvxmtrx/tga) [tga](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> ![](https://img.shields.io/github/last-commit/jyotiska/go-webcolors) [go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> ![](https://img.shields.io/github/last-commit/mehdipourfar/webp-server) [webp-server](https://github.com/mehdipourfar/webp-server) - Simple and minimal image server capable of storing, resizing, converting and caching images.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/donatj/mpo) [mpo](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos.

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

* <code>&nbsp;&nbsp;7265</code> ![](https://img.shields.io/github/last-commit/hybridgroup/gobot) [gobot](https://github.com/hybridgroup/gobot/) - Gobot is a framework for robotics, physical computing, and the Internet of Things.
* <code>&nbsp;&nbsp;1816</code> ![](https://img.shields.io/github/last-commit/tibcosoftware/flogo) [flogo](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration.
* <code>&nbsp;&nbsp;1494</code> ![](https://img.shields.io/github/last-commit/Mainflux/mainflux) [mainflux](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server.
* <code>&nbsp;&nbsp;&nbsp;985</code> ![](https://img.shields.io/github/last-commit/paypal/gatt) [gatt](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals.
* <code>&nbsp;&nbsp;&nbsp;281</code> ![](https://img.shields.io/github/last-commit/connectordb/connectordb) [connectordb](https://github.com/connectordb/connectordb) - Open-Source Platform for Quantified Self & IoT.
* <code>&nbsp;&nbsp;&nbsp;241</code> ![](https://img.shields.io/github/last-commit/goiot/devices) [devices](https://github.com/goiot/devices) - Suite of libraries for IoT devices, experimental for x/exp/io.
* <code>&nbsp;&nbsp;&nbsp;204</code> ![](https://img.shields.io/github/last-commit/sensorbee/sensorbee) [sensorbee](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT.
* <code>&nbsp;&nbsp;&nbsp;184</code> ![](https://img.shields.io/github/last-commit/amimof/huego) [huego](https://github.com/amimof/huego) - An extensive Philips Hue client library for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;52</code> ![](https://img.shields.io/github/last-commit/vaelen/iot) [iot](https://github.com/vaelen/iot/) - IoT is a simple framework for implementing a Google IoT Core device.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> ![](https://img.shields.io/github/last-commit/xcodersun/eywa) [eywa](https://github.com/xcodersun/eywa) - Project Eywa is essentially a connection manager that keeps track of connected devices.
* [periph](https://periph.io/) - Peripherals I/O to interface with low-level board facilities.

## Job Scheduler

*Libraries for scheduling jobs.*

* <code>&nbsp;&nbsp;1003</code> ![](https://img.shields.io/github/last-commit/go-co-op/gocron) [gocron](https://github.com/go-co-op/gocron) - Easy and fluent Go job scheduling. This is an actively maintained fork of <code>&nbsp;&nbsp;2636</code> ![](https://img.shields.io/github/last-commit/jasonlvhit/gocron) [jasonlvhit/gocron](https://github.com/jasonlvhit/gocron).
* <code>&nbsp;&nbsp;&nbsp;866</code> ![](https://img.shields.io/github/last-commit/bamzi/jobrunner) [JobRunner](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in.
* <code>&nbsp;&nbsp;&nbsp;866</code> ![](https://img.shields.io/github/last-commit/roylee0704/gron) [gron](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.
* <code>&nbsp;&nbsp;&nbsp;482</code> ![](https://img.shields.io/github/last-commit/albrow/jobs) [jobs](https://github.com/albrow/jobs) - Persistent and flexible background jobs library.
* <code>&nbsp;&nbsp;&nbsp;368</code> ![](https://img.shields.io/github/last-commit/carlescere/scheduler) [scheduler](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy.
* <code>&nbsp;&nbsp;&nbsp;202</code> ![](https://img.shields.io/github/last-commit/rk/go-cron) [go-cron](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.
* <code>&nbsp;&nbsp;&nbsp;146</code> ![](https://img.shields.io/github/last-commit/reugn/go-quartz) [go-quartz](https://github.com/reugn/go-quartz) - Simple, zero-dependency scheduling library for Go.
* <code>&nbsp;&nbsp;&nbsp;108</code> ![](https://img.shields.io/github/last-commit/onatm/clockwerk) [clockwerk](http://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;83</code> ![](https://img.shields.io/github/last-commit/kilgaloon/leprechaun) [leprechaun](https://github.com/kilgaloon/leprechaun) - Job scheduler that supports webhooks, crons and classic scheduling.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> ![](https://img.shields.io/github/last-commit/madflojo/tasks) [tasks](https://github.com/madflojo/tasks) - An easy to use in-process scheduler for recurring tasks in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code> ![](https://img.shields.io/github/last-commit/krayzpipes/cronticker) [cronticker](https://github.com/krayzpipes/cronticker) - A ticker implementation to support cron schedules.

## JSON

*Libraries for working with JSON.*

* <code>&nbsp;&nbsp;8712</code> ![](https://img.shields.io/github/last-commit/tidwall/gjson) [GJSON](https://github.com/tidwall/gjson) - Get a JSON value with one line of code.
* <code>&nbsp;&nbsp;2385</code> ![](https://img.shields.io/github/last-commit/ChimeraCoder/gojson) [gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON.
* <code>&nbsp;&nbsp;1279</code> ![](https://img.shields.io/github/last-commit/valyala/fastjson) [fastjson](https://github.com/valyala/fastjson) - Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection.
* <code>&nbsp;&nbsp;&nbsp;202</code> ![](https://img.shields.io/github/last-commit/Qntfy/kazaam) [kazaam](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents.
* <code>&nbsp;&nbsp;&nbsp;172</code> ![](https://img.shields.io/github/last-commit/elgs/gojq) [gojq](https://github.com/elgs/gojq) - JSON query in Golang.
* <code>&nbsp;&nbsp;&nbsp;121</code> ![](https://img.shields.io/github/last-commit/wI2L/jsondiff) [jsondiff](https://github.com/wI2L/jsondiff) - JSON diff library for Go based on RFC6902 (JSON Patch).
* <code>&nbsp;&nbsp;&nbsp;110</code> ![](https://img.shields.io/github/last-commit/wI2L/jettison) [jettison](https://github.com/wI2L/jettison) - Fast and flexible JSON encoder for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;96</code> ![](https://img.shields.io/github/last-commit/ricardolonga/jsongo) [jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;94</code> ![](https://img.shields.io/github/last-commit/skanehira/gjo) [gjo](https://github.com/skanehira/gjo) - Small utility to create JSON objects.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> ![](https://img.shields.io/github/last-commit/yazgazan/jaydiff) [JayDiff](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;83</code> ![](https://img.shields.io/github/last-commit/m-zajac/json2go) [json2go](https://github.com/m-zajac/json2go) - Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;64</code> ![](https://img.shields.io/github/last-commit/spyzhov/ajson) [ajson](https://github.com/spyzhov/ajson) - Abstract JSON for golang with JSONPath support.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;62</code> ![](https://img.shields.io/github/last-commit/miolini/jsonf) [jsonf](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> ![](https://img.shields.io/github/last-commit/olvrng/ujson) [ujson](https://github.com/olvrng/ujson) - Fast and minimal JSON parser and transformer that works on unstructured JSON.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;44</code> ![](https://img.shields.io/github/last-commit/sanbornm/mp) [mp](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> ![](https://img.shields.io/github/last-commit/nicklaw5/go-respond) [go-respond](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/miladibra10/vjson) [vjson](https://github.com/miladibra10/vjson) - Go package for validating JSON objects with declaring a JSON schema with fluent API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/ddymko/go-jsonerror) [go-jsonerror](https://github.com/ddymko/go-jsonerror) - Go-JsonError is ment to allow us to easily create json response errors that follow the JsonApi spec.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/AmuzaTkts/jsonapi-errors) [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/RichardKnop/jsonhal) [jsonhal](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/lucassscaravelli/ej) [ej](https://github.com/lucassscaravelli/ej) - Write and read JSON from different sources succinctly.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/simonnilsson/ask) [ask](https://github.com/simonnilsson/ask) - Easy access to nested values in maps and slices. Works in combination with encoding/json and other packages that "Unmarshal" arbitrary data into Go data-types.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/vtopc/epoch) [epoch](https://github.com/vtopc/epoch) - Contains primitives for marshaling/unmarshaling Unix timestamp/epoch to/from build-in time.Time type in JSON.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/cocoonspace/dynjson) [dynjson](https://github.com/cocoonspace/dynjson) - Client-customizable JSON formats for dynamic APIs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/mickep76/mapslice-json) [mapslice-json](https://github.com/mickep76/mapslice-json) - Go MapSlice for ordered marshal/ unmarshal of maps in JSON.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/zerosnake0/jzon) [jzon](https://github.com/zerosnake0/jzon) - JSON library with standard compatible API/behavior.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> ![](https://img.shields.io/github/last-commit/sinhashubham95/jsonic) [jsonic](https://github.com/sinhashubham95/jsonic) - Utilities to handle and query JSON without defining structs in a type safe manner.
* [JSON-to-Proto](https://json-to-proto.github.io/) - Convert JSON to Protobuf online.
* [JSON-to-Go](https://mholt.github.io/json-to-go/) - Convert JSON to Go struct.

## Logging

*Libraries for generating and working with log files.*

* <code>&nbsp;18409</code> ![](https://img.shields.io/github/last-commit/Sirupsen/logrus) [logrus](https://github.com/Sirupsen/logrus) - Structured logger for Go.
* <code>&nbsp;13280</code> ![](https://img.shields.io/github/last-commit/uber-go/zap) [zap](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go.
* <code>&nbsp;&nbsp;5029</code> ![](https://img.shields.io/github/last-commit/rs/zerolog) [zerolog](https://github.com/rs/zerolog) - Zero-allocation JSON logger.
* <code>&nbsp;&nbsp;4516</code> ![](https://img.shields.io/github/last-commit/davecgh/go-spew) [spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging.
* <code>&nbsp;&nbsp;2772</code> ![](https://img.shields.io/github/last-commit/golang/glog) [glog](https://github.com/golang/glog) - Leveled execution logs for Go.
* <code>&nbsp;&nbsp;2684</code> ![](https://img.shields.io/github/last-commit/natefinch/lumberjack) [lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser.
* <code>&nbsp;&nbsp;2143</code> ![](https://img.shields.io/github/last-commit/hpcloud/tail) [tail](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program.
* <code>&nbsp;&nbsp;1555</code> ![](https://img.shields.io/github/last-commit/cihub/seelog) [seelog](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting.
* <code>&nbsp;&nbsp;1153</code> ![](https://img.shields.io/github/last-commit/apex/log) [log](https://github.com/apex/log) - Structured logging package for Go.
* <code>&nbsp;&nbsp;1013</code> ![](https://img.shields.io/github/last-commit/inconshreveable/log15) [log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go.
* <code>&nbsp;&nbsp;&nbsp;396</code> ![](https://img.shields.io/github/last-commit/francoispqt/onelog) [onelog](https://github.com/francoispqt/onelog) - Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenarios. Also, it is one of the logger with the lowest allocation.
* <code>&nbsp;&nbsp;&nbsp;389</code> ![](https://img.shields.io/github/last-commit/phuslu/log) [phuslu/log](https://github.com/phuslu/log) - Structured Logging Made Easy.
* <code>&nbsp;&nbsp;&nbsp;347</code> ![](https://img.shields.io/github/last-commit/mgutz/logxi) [logxi](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy.
* <code>&nbsp;&nbsp;&nbsp;295</code> ![](https://img.shields.io/github/last-commit/hashicorp/logutils) [logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger.
* <code>&nbsp;&nbsp;&nbsp;275</code> ![](https://img.shields.io/github/last-commit/go-playground/log) [log](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go.
* <code>&nbsp;&nbsp;&nbsp;266</code> ![](https://img.shields.io/github/last-commit/apsdehal/go-logger) [go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers.
* <code>&nbsp;&nbsp;&nbsp;234</code> ![](https://img.shields.io/github/last-commit/henvic/httpretty) [httpretty](https://github.com/henvic/httpretty) - Pretty-prints your regular HTTP requests on your terminal for debugging (similar to http.DumpRequest).
* <code>&nbsp;&nbsp;&nbsp;183</code> ![](https://img.shields.io/github/last-commit/simukti/sqldb-logger) [sqldb-logger](https://github.com/simukti/sqldb-logger) - A logger for Go SQL database driver without modify existing *sql.DB stdlib usage.
* <code>&nbsp;&nbsp;&nbsp;177</code> ![](https://img.shields.io/github/last-commit/arthurkiller/rollingWriter) [rollingwriter](https://github.com/arthurkiller/rollingWriter) - RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation.
* <code>&nbsp;&nbsp;&nbsp;148</code> ![](https://img.shields.io/github/last-commit/azer/logger) [logger](https://github.com/azer/logger) - Minimalistic logging library for Go.
* <code>&nbsp;&nbsp;&nbsp;135</code> ![](https://img.shields.io/github/last-commit/logur/logur) [logur](https://github.com/logur/logur) - An opinionated logger interface and collection of logging best practices with adapters and integrations for well-known libraries (<code>&nbsp;18409</code> ![](https://img.shields.io/github/last-commit/sirupsen/logrus) [logrus](https://github.com/sirupsen/logrus), <code>&nbsp;20928</code> ![](https://img.shields.io/github/last-commit/go-kit/kit) [go-kit log](https://github.com/go-kit/kit/tree/master/log), <code>&nbsp;13280</code> ![](https://img.shields.io/github/last-commit/uber-go/zap) [zap](https://github.com/uber-go/zap), <code>&nbsp;&nbsp;5029</code> ![](https://img.shields.io/github/last-commit/rs/zerolog) [zerolog](https://github.com/rs/zerolog), etc).
* <code>&nbsp;&nbsp;&nbsp;135</code> ![](https://img.shields.io/github/last-commit/rs/xlog) [xlog](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching.
* <code>&nbsp;&nbsp;&nbsp;116</code> ![](https://img.shields.io/github/last-commit/kpango/glg) [glg](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go.
* <code>&nbsp;&nbsp;&nbsp;114</code> ![](https://img.shields.io/github/last-commit/go-ozzo/ozzo-log) [ozzo-log](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;88</code> ![](https://img.shields.io/github/last-commit/firstrow/logvoyage) [log-voyage](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> ![](https://img.shields.io/github/last-commit/alexcesaro/log) [stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;42</code> ![](https://img.shields.io/github/last-commit/utahta/go-cronowriter) [go-cronowriter](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> ![](https://img.shields.io/github/last-commit/sadlil/gologger) [gologger](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> ![](https://img.shields.io/github/last-commit/chzyer/logex) [logex](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> ![](https://img.shields.io/github/last-commit/ian-kent/go-log) [go-log](https://github.com/ian-kent/go-log) - Log4j implementation in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> ![](https://img.shields.io/github/last-commit/One-com/gone) [gone/log](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/siddontang/go-log) [go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> ![](https://img.shields.io/github/last-commit/sebest/logrusly) [logrusly](https://github.com/sebest/logrusly) - <code>&nbsp;18409</code> ![](https://img.shields.io/github/last-commit/sirupsen/logrus) [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> ![](https://img.shields.io/github/last-commit/ssgreg/journald) [journald](https://github.com/ssgreg/journald) - Go implementation of systemd Journal's native API for logging.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> ![](https://img.shields.io/github/last-commit/amoghe/distillog) [distillog](https://github.com/amoghe/distillog) - distilled levelled logging (think of it as stdlib + log levels).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/jbrodriguez/mlog) [mlog](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/teris-io/log) [log](https://github.com/teris-io/log) - Structured log interface for Go cleanly separates logging facade from its implementation.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/aphistic/gomol) [gomol](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/edoger/zkits-logger) [zkits-logger](https://github.com/edoger/zkits-logger) - A powerful zero-dependency JSON logger.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/lajosbencz/glo) [glo](https://github.com/lajosbencz/glo) - PHP Monolog inspired logging facility with identical severity levels.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/cabify/logrusiowriter) [logrusiowriter](https://github.com/cabify/logrusiowriter) - `io.Writer` implementation using <code>&nbsp;18409</code> ![](https://img.shields.io/github/last-commit/sirupsen/logrus) [logrus](https://github.com/sirupsen/logrus) logger.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/subchen/go-log) [go-log](https://github.com/subchen/go-log) - Simple and configurable Logging in Go, with level, formatters and writers.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/borderstech/logmatic) [logmatic](https://github.com/borderstech/logmatic) - Colorized logger for Golang with dynamic log level configuration.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/ewwwwwqm/logdump) [logdump](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/mbndr/logo) [logo](https://github.com/mbndr/logo) - Golang logger to different configurable writers.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> ![](https://img.shields.io/github/last-commit/aerogo/log) [log](https://github.com/aerogo/log) - An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> ![](https://img.shields.io/github/last-commit/pieterclaerhout/go-log) [go-log](https://github.com/pieterclaerhout/go-log) - A logging library with strack traces, object dumping and optional timestamps.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/xfxdev/xlog) [xlog](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/clok/kemba) [kemba](https://github.com/clok/kemba) - A tiny debug logging tool inspired by <code>&nbsp;&nbsp;9691</code> ![](https://img.shields.io/github/last-commit/visionmedia/debug) [debug](https://github.com/visionmedia/debug), great for CLI tools and applications.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code> ![](https://img.shields.io/github/last-commit/jfcg/yell) [yell](https://github.com/jfcg/yell) - Yet another minimalistic logging library.

## Machine Learning

*Libraries for Machine Learning.*

* <code>&nbsp;&nbsp;7950</code> ![](https://img.shields.io/github/last-commit/sjwhitworth/golearn) [GoLearn](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go.
* <code>&nbsp;&nbsp;4135</code> ![](https://img.shields.io/github/last-commit/gorgonia/gorgonia) [gorgonia](https://github.com/gorgonia/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms.
* <code>&nbsp;&nbsp;4067</code> ![](https://img.shields.io/github/last-commit/zhenghaoz/gorse) [gorse](https://github.com/zhenghaoz/gorse) - An offline recommender system backend based on collaborative filtering written in Go.
* <code>&nbsp;&nbsp;1759</code> ![](https://img.shields.io/github/last-commit/galeone/tfgo) [tfgo](https://github.com/galeone/tfgo) - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python.
* <code>&nbsp;&nbsp;1526</code> ![](https://img.shields.io/github/last-commit/otiai10/gosseract) [gosseract](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library.
* <code>&nbsp;&nbsp;1209</code> ![](https://img.shields.io/github/last-commit/cdipaolo/goml) [goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go.
* <code>&nbsp;&nbsp;&nbsp;741</code> ![](https://img.shields.io/github/last-commit/MaxHalford/eaopt) [eaopt](https://github.com/MaxHalford/eaopt) - An evolutionary optimization library.
* <code>&nbsp;&nbsp;&nbsp;712</code> ![](https://img.shields.io/github/last-commit/jbrukh/bayesian) [bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang.
* <code>&nbsp;&nbsp;&nbsp;686</code> ![](https://img.shields.io/github/last-commit/ryanbressler/CloudForest) [CloudForest](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go.
* <code>&nbsp;&nbsp;&nbsp;484</code> ![](https://img.shields.io/github/last-commit/goml/gobrain) [gobrain](https://github.com/goml/gobrain) - Neural Networks written in go.
* <code>&nbsp;&nbsp;&nbsp;390</code> ![](https://img.shields.io/github/last-commit/otiai10/ocrserver) [ocrserver](https://github.com/otiai10/ocrserver) - A simple OCR API server, seriously easy to be deployed by Docker and Heroku.
* <code>&nbsp;&nbsp;&nbsp;339</code> ![](https://img.shields.io/github/last-commit/owulveryck/onnx-go) [onnx-go](https://github.com/owulveryck/onnx-go) - Go Interface to Open Neural Network Exchange (ONNX).
* <code>&nbsp;&nbsp;&nbsp;324</code> ![](https://img.shields.io/github/last-commit/patrikeh/go-deep) [go-deep](https://github.com/patrikeh/go-deep) - A feature-rich neural network library in Go.
* <code>&nbsp;&nbsp;&nbsp;291</code> ![](https://img.shields.io/github/last-commit/muesli/regommend) [regommend](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine.
* <code>&nbsp;&nbsp;&nbsp;186</code> ![](https://img.shields.io/github/last-commit/thoj/go-galib) [go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang.
* <code>&nbsp;&nbsp;&nbsp;185</code> ![](https://img.shields.io/github/last-commit/c-bata/goptuna) [Goptuna](https://github.com/c-bata/goptuna) - Bayesian optimization framework for black-box functions written in Go. Everything will be optimized.
* <code>&nbsp;&nbsp;&nbsp;175</code> ![](https://img.shields.io/github/last-commit/timkaye11/goRecommend) [goRecommend](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go.
* <code>&nbsp;&nbsp;&nbsp;142</code> ![](https://img.shields.io/github/last-commit/eaigner/shield) [shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go.
* <code>&nbsp;&nbsp;&nbsp;110</code> ![](https://img.shields.io/github/last-commit/tomcraven/goga) [goga](https://github.com/tomcraven/goga) - Genetic algorithm library for Go.
* <code>&nbsp;&nbsp;&nbsp;103</code> ![](https://img.shields.io/github/last-commit/white-pony/go-fann) [go-fann](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;68</code> ![](https://img.shields.io/github/last-commit/dathoangnd/gonet) [gonet](https://github.com/dathoangnd/gonet) - Neural Network for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> ![](https://img.shields.io/github/last-commit/datastream/libsvm) [libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;65</code> ![](https://img.shields.io/github/last-commit/asafschers/goscore) [goscore](https://github.com/asafschers/goscore) - Go Scoring API for PMML.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;61</code> ![](https://img.shields.io/github/last-commit/schuyler/neural-go) [neural-go](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> ![](https://img.shields.io/github/last-commit/daviddengcn/go-pr) [go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> ![](https://img.shields.io/github/last-commit/nikolaydubina/go-featureprocessing) [go-featureprocessing](https://github.com/nikolaydubina/go-featureprocessing) - Fast and convenient feature processing for low latency machine leraning in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;58</code> ![](https://img.shields.io/github/last-commit/jinyeom/neat) [neat](https://github.com/jinyeom/neat) - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> ![](https://img.shields.io/github/last-commit/Fontinalis/fonet) [fonet](https://github.com/Fontinalis/fonet) - A Deep Neural Network library written in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;42</code> ![](https://img.shields.io/github/last-commit/danieldk/golinear) [golinear](https://github.com/danieldk/golinear) - liblinear bindings for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> ![](https://img.shields.io/github/last-commit/Xamber/Varis) [Varis](https://github.com/Xamber/Varis) - Golang Neural Network.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> ![](https://img.shields.io/github/last-commit/e-dard/godist) [godist](https://github.com/e-dard/godist) - Various probability distributions, and associated methods.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/e-XpertSolutions/go-cluster) [go-cluster](https://github.com/e-XpertSolutions/go-cluster) - Go implementation of the k-modes and k-prototypes clustering algorithms.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> ![](https://img.shields.io/github/last-commit/ThePaw/probab) [probab](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/khezen/evoli) [evoli](https://github.com/khezen/evoli) - Genetic Algorithm and Particle Swarm Optimization library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/surenderthakran/gomind) [GoMind](https://github.com/surenderthakran/gomind) - A simplistic Neural Network Library in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> ![](https://img.shields.io/github/last-commit/malaschitz/randomForest) [randomforest](https://github.com/malaschitz/randomForest) - Easy to use Random Forest library for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/sgrodriguez/ddt) [ddt](https://github.com/sgrodriguez/ddt) - Dynamic decision tree, create trees defining customizable rules.

## Messaging

*Libraries that implement messaging systems.*

* <code>&nbsp;&nbsp;7495</code> ![](https://img.shields.io/github/last-commit/Shopify/sarama) [sarama](https://github.com/Shopify/sarama) - Go library for Apache Kafka.
* <code>&nbsp;&nbsp;5640</code> ![](https://img.shields.io/github/last-commit/appleboy/gorush) [gorush](https://github.com/appleboy/gorush) - Push notification server using <code>&nbsp;&nbsp;2533</code> ![](https://img.shields.io/github/last-commit/sideshow/apns2) [APNs2](https://github.com/sideshow/apns2) and google <code>&nbsp;&nbsp;&nbsp;104</code> ![](https://img.shields.io/github/last-commit/google/go-gcm) [GCM](https://github.com/google/go-gcm).
* <code>&nbsp;&nbsp;5462</code> ![](https://img.shields.io/github/last-commit/RichardKnop/machinery) [machinery](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing.
* <code>&nbsp;&nbsp;5180</code> ![](https://img.shields.io/github/last-commit/centrifugal/centrifugo) [Centrifugo](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go.
* <code>&nbsp;&nbsp;4192</code> ![](https://img.shields.io/github/last-commit/googollee/go-socket.io) [go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework.
* <code>&nbsp;&nbsp;3474</code> ![](https://img.shields.io/github/last-commit/nats-io/nats) [NATS Go Client](https://github.com/nats-io/nats) - Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library.
* <code>&nbsp;&nbsp;3282</code> ![](https://img.shields.io/github/last-commit/Jeffail/benthos) [Benthos](https://github.com/Jeffail/benthos) - A message streaming bridge between a range of protocols.
* <code>&nbsp;&nbsp;2823</code> ![](https://img.shields.io/github/last-commit/confluentinc/confluent-kafka-go) [Confluent Kafka Golang Client](https://github.com/confluentinc/confluent-kafka-go) - confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform.
* <code>&nbsp;&nbsp;2533</code> ![](https://img.shields.io/github/last-commit/sideshow/apns2) [APNs2](https://github.com/sideshow/apns2) - HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps.
* <code>&nbsp;&nbsp;2504</code> ![](https://img.shields.io/github/last-commit/dunglas/mercure) [Mercure](https://github.com/dunglas/mercure) - Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events).
* <code>&nbsp;&nbsp;2190</code> ![](https://img.shields.io/github/last-commit/olahol/melody) [melody](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling.
* <code>&nbsp;&nbsp;1994</code> ![](https://img.shields.io/github/last-commit/Terry-Mao/gopush-cluster) [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster.
* <code>&nbsp;&nbsp;1955</code> ![](https://img.shields.io/github/last-commit/nsqio/go-nsq) [go-nsq](https://github.com/nsqio/go-nsq) - the official Go package for NSQ.
* <code>&nbsp;&nbsp;1416</code> ![](https://img.shields.io/github/last-commit/hibiken/asynq) [Asynq](https://github.com/hibiken/asynq) - A simple, reliable, and efficient distributed task queue for Go built on top of Redis.
* <code>&nbsp;&nbsp;1265</code> ![](https://img.shields.io/github/last-commit/uniqush/uniqush-push) [Uniqush-Push](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices.
* <code>&nbsp;&nbsp;1116</code> ![](https://img.shields.io/github/last-commit/Clivern/Beaver) [Beaver](https://github.com/Clivern/Beaver) - A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps.
* <code>&nbsp;&nbsp;&nbsp;960</code> ![](https://img.shields.io/github/last-commit/asaskevich/EventBus) [EventBus](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility.
* <code>&nbsp;&nbsp;&nbsp;920</code> ![](https://img.shields.io/github/last-commit/pebbe/zmq4) [zmq4](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for <code>&nbsp;&nbsp;&nbsp;131</code> ![](https://img.shields.io/github/last-commit/pebbe/zmq3) [version 3](https://github.com/pebbe/zmq3) and <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> ![](https://img.shields.io/github/last-commit/pebbe/zmq2) [version 2](https://github.com/pebbe/zmq2).
* <code>&nbsp;&nbsp;&nbsp;902</code> ![](https://img.shields.io/github/last-commit/trivago/gollum) [Gollum](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations.
* <code>&nbsp;&nbsp;&nbsp;607</code> ![](https://img.shields.io/github/last-commit/godbus/dbus) [dbus](https://github.com/godbus/dbus) - Native Go bindings for D-Bus.
* <code>&nbsp;&nbsp;&nbsp;584</code> ![](https://img.shields.io/github/last-commit/chanify/chanify) [Chanify](https://github.com/chanify/chanify) - A push notification server send message to your iOS devices.
* <code>&nbsp;&nbsp;&nbsp;562</code> ![](https://img.shields.io/github/last-commit/jcuga/golongpoll) [golongpoll](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple.
* <code>&nbsp;&nbsp;&nbsp;427</code> ![](https://img.shields.io/github/last-commit/nanomsg/mangos) [mangos](https://github.com/nanomsg/mangos) - Pure go implementation of the Nanomsg ("Scalability Protocols") with transport interoperability.
* <code>&nbsp;&nbsp;&nbsp;407</code> ![](https://img.shields.io/github/last-commit/olebedev/emitter) [emitter](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins.
* <code>&nbsp;&nbsp;&nbsp;382</code> ![](https://img.shields.io/github/last-commit/desertbit/glue) [Glue](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io).
* <code>&nbsp;&nbsp;&nbsp;356</code> ![](https://img.shields.io/github/last-commit/tuxychandru/pubsub) [pubsub](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go.
* <code>&nbsp;&nbsp;&nbsp;217</code> ![](https://img.shields.io/github/last-commit/mustafaturan/bus) [Bus](https://github.com/mustafaturan/bus) - Minimalist message bus implementation for internal communication.
* <code>&nbsp;&nbsp;&nbsp;186</code> ![](https://img.shields.io/github/last-commit/vardius/message-bus) [messagebus](https://github.com/vardius/message-bus) - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD.
* <code>&nbsp;&nbsp;&nbsp;186</code> ![](https://img.shields.io/github/last-commit/jandelgado/rabtap) [rabtap](https://github.com/jandelgado/rabtap) - RabbitMQ swiss army knife cli app.
* <code>&nbsp;&nbsp;&nbsp;149</code> ![](https://img.shields.io/github/last-commit/smancke/guble) [guble](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence.
* <code>&nbsp;&nbsp;&nbsp;108</code> ![](https://img.shields.io/github/last-commit/leandro-lugaresi/hub) [hub](https://github.com/leandro-lugaresi/hub) - A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges.
* <code>&nbsp;&nbsp;&nbsp;107</code> ![](https://img.shields.io/github/last-commit/dailymotion/oplog) [oplog](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;90</code> ![](https://img.shields.io/github/last-commit/rafaeljesus/rabbus) [rabbus](https://github.com/rafaeljesus/rabbus) - A tiny wrapper over amqp exchanges and queues.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;76</code> ![](https://img.shields.io/github/last-commit/appleboy/drone-line) [drone-line](https://github.com/appleboy/drone-line) - Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;68</code> ![](https://img.shields.io/github/last-commit/rafaeljesus/nsq-event-bus) [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> ![](https://img.shields.io/github/last-commit/cheshir/go-mq) [go-mq](https://github.com/cheshir/go-mq) - RabbitMQ client with declarative configuration.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;62</code> ![](https://img.shields.io/github/last-commit/sybrexsys/RapidMQ) [RapidMQ](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;61</code> ![](https://img.shields.io/github/last-commit/robinjoseph08/redisqueue) [redisqueue](https://github.com/robinjoseph08/redisqueue) - redisqueue provides a producer and consumer of a queue that uses Redis streams.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;55</code> ![](https://img.shields.io/github/last-commit/jeroenrinzema/commander) [Commander](https://github.com/jeroenrinzema/commander) - A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> ![](https://img.shields.io/github/last-commit/TheCreeper/go-notify) [go-notify](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> ![](https://img.shields.io/github/last-commit/jirenius/go-res) [go-res](https://github.com/jirenius/go-res) - Package for building REST/real-time services where clients are synchronized seamlessly, using NATS and Resgate.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> ![](https://img.shields.io/github/last-commit/agoalofalife/event) [event](https://github.com/agoalofalife/event) - Implementation of the pattern observer.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> ![](https://img.shields.io/github/last-commit/leozz37/hare) [hare](https://github.com/leozz37/hare) - A user friendly library for sending messages and listening to TCP sockets.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> ![](https://img.shields.io/github/last-commit/kak-tus/ami) [ami](https://github.com/kak-tus/ami) - Go client to reliable queues based on Redis Cluster Streams.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> ![](https://img.shields.io/github/last-commit/alexsniffin/gosd) [gosd](https://github.com/alexsniffin/gosd) - A library for scheduling when to dispatch a message to a channel.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> ![](https://img.shields.io/github/last-commit/maxatome/go-vitotrol) [go-vitotrol](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/sbabiv/rmqconn) [rmqconn](https://github.com/sbabiv/rmqconn) - RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/socifi/jazz) [jazz](https://github.com/socifi/jazz) - A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/osamingo/gaurun-client) [gaurun-client](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go.

## Microsoft Office

* <code>&nbsp;&nbsp;2927</code> ![](https://img.shields.io/github/last-commit/unidoc/unioffice) [unioffice](https://github.com/unidoc/unioffice) - Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents.

### Microsoft Excel

*Libraries for working with Microsoft Excel.*

* <code>&nbsp;&nbsp;9295</code> ![](https://img.shields.io/github/last-commit/xuri/excelize) [excelize](https://github.com/xuri/excelize) - Golang library for reading and writing Microsoft Excel&trade; (XLSX) files.
* <code>&nbsp;&nbsp;5075</code> ![](https://img.shields.io/github/last-commit/tealeg/xlsx) [xlsx](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.
* <code>&nbsp;&nbsp;&nbsp;140</code> ![](https://img.shields.io/github/last-commit/plandem/xlsx) [xlsx](https://github.com/plandem/xlsx) - Fast and safe way to read/update your existing Microsoft Excel files in Go programs.
* <code>&nbsp;&nbsp;&nbsp;128</code> ![](https://img.shields.io/github/last-commit/szyhf/go-excel) [go-excel](https://github.com/szyhf/go-excel) - A simple and light reader to read a relate-db-like excel as a table.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> ![](https://img.shields.io/github/last-commit/fterrag/goxlsxwriter) [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files.

## Miscellaneous

### Dependency Injection

*Libraries for working with dependency injection.*

* <code>&nbsp;&nbsp;2123</code> ![](https://img.shields.io/github/last-commit/uber-go/fx) [fx](https://github.com/uber-go/fx) - A dependency injection based application framework for Go (built on top of dig).
* <code>&nbsp;&nbsp;2016</code> ![](https://img.shields.io/github/last-commit/uber-go/dig) [dig](https://github.com/uber-go/dig) - A reflection based dependency injection toolkit for Go.
* <code>&nbsp;&nbsp;&nbsp;218</code> ![](https://img.shields.io/github/last-commit/golobby/container) [container](https://github.com/golobby/container) - A powerful IoC Container with fluent and easy-to-use interface.
* <code>&nbsp;&nbsp;&nbsp;107</code> ![](https://img.shields.io/github/last-commit/i-love-flamingo/dingo) [dingo](https://github.com/i-love-flamingo/dingo) - A dependency injection toolkit for Go, based on Guice.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;98</code> ![](https://img.shields.io/github/last-commit/goava/di) [di](https://github.com/goava/di) - A dependency injection container for go programming language.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> ![](https://img.shields.io/github/last-commit/goioc/di) [goioc/di](https://github.com/goioc/di) - Spring-inspired Dependency Injection Container.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;44</code> ![](https://img.shields.io/github/last-commit/magic003/alice) [alice](https://github.com/magic003/alice) - Additive dependency injection container for Golang.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/Fs02/wire) [wire](https://github.com/Fs02/wire) - Strict Runtime Dependency Injection for Golang.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;32</code> ![](https://img.shields.io/github/last-commit/logrange/linker) [linker](https://github.com/logrange/linker) - A reflection based dependency injection and inversion of control library with components lifecycle support.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/vardius/gocontainer) [gocontainer](https://github.com/vardius/gocontainer) - Simple Dependency Injection Container.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/go-kata/kinit) [kinit](https://github.com/go-kata/kinit) - Customizable dependency injection container with the global mode, cascade initialization and panic-safe finalization.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> ![](https://img.shields.io/github/last-commit/BlueOwlOpenSource/nject) [nject/npoint](https://github.com/BlueOwlOpenSource/nject) - A type safe, reflective framework based on types for libraries, tests, and endpoints.

### Project Layout

***Unofficial** set of patterns for structuring projects.*

* <code>&nbsp;25560</code> ![](https://img.shields.io/github/last-commit/golang-standards/project-layout) [golang-standards/project-layout](https://github.com/golang-standards/project-layout) - Set of common historical and emerging project layout patterns in the Go ecosystem.
* <code>&nbsp;&nbsp;1032</code> ![](https://img.shields.io/github/last-commit/sagikazarmark/modern-go-application) [modern-go-application](https://github.com/sagikazarmark/modern-go-application) - Go application boilerplate and example applying modern practices.
* <code>&nbsp;&nbsp;&nbsp;467</code> ![](https://img.shields.io/github/last-commit/lacion/cookiecutter-golang) [cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) - A Go application boilerplate template for quick starting projects following production best practices.
* <code>&nbsp;&nbsp;&nbsp;187</code> ![](https://img.shields.io/github/last-commit/golang-templates/seed) [golang-templates/seed](https://github.com/golang-templates/seed) - Go application GitHub repository template.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;98</code> ![](https://img.shields.io/github/last-commit/catchplay/scaffold) [scaffold](https://github.com/catchplay/scaffold) - Scaffold generates a starter Go project layout. Lets you focus on business logic implemented.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;87</code> ![](https://img.shields.io/github/last-commit/zitryss/go-sample) [go-sample](https://github.com/zitryss/go-sample) - A sample layout for Go application projects with the real code.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;82</code> ![](https://img.shields.io/github/last-commit/Fs02/go-todo-backend) [go-todo-backend](https://github.com/Fs02/go-todo-backend) - Go Todo Backend example using modular project layout for product microservice.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/wajox/gobase) [gobase](https://github.com/wajox/gobase) - A simple skeleton for golang application with basic setup for real golang application.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> ![](https://img.shields.io/github/last-commit/insidieux/inizio) [insidieux/inizio](https://github.com/insidieux/inizio) - Golang project layout generator with plugins.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/wangyoucao577/go-project-layout) [wangyoucao577/go-project-layout](https://github.com/wangyoucao577/go-project-layout) - Set of practices and discussions on how to structure Go project layout.

### Strings

*Libraries for working with strings.*

* <code>&nbsp;&nbsp;&nbsp;909</code> ![](https://img.shields.io/github/last-commit/huandu/xstrings) [xstrings](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages.
* <code>&nbsp;&nbsp;&nbsp;123</code> ![](https://img.shields.io/github/last-commit/ozgio/strutil) [strutil](https://github.com/ozgio/strutil) - String utilities.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;66</code> ![](https://img.shields.io/github/last-commit/gobeam/Stringy) [gobeam/Stringy](https://github.com/gobeam/Stringy) - String manipulation library to convert string to camel case, snake case, kebab case / slugify etc.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> ![](https://img.shields.io/github/last-commit/mkungla/bexp) [bexp](https://github.com/mkungla/bexp) - Go implementation of Brace Expansion mechanism to generate arbitrary strings.
* [go-formatter](https://gitlab.com/tymonx/go-formatter) - Implements **replacement fields** surrounded by curly braces `{}` format strings.

### Uncategorized

*These libraries were placed here because none of the other categories seemed to fit.*

* <code>&nbsp;&nbsp;6586</code> ![](https://img.shields.io/github/last-commit/shirou/gopsutil) [gopsutil](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).
* <code>&nbsp;&nbsp;3277</code> ![](https://img.shields.io/github/last-commit/mholt/archiver) [archiver](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives.
* <code>&nbsp;&nbsp;1972</code> ![](https://img.shields.io/github/last-commit/brianvoe/gofakeit) [gofakeit](https://github.com/brianvoe/gofakeit) - Random data generator written in go.
* <code>&nbsp;&nbsp;1647</code> ![](https://img.shields.io/github/last-commit/TwinProduction/gatus) [gatus](https://github.com/TwinProduction/gatus) - Automated service health dashboard.
* <code>&nbsp;&nbsp;1340</code> ![](https://img.shields.io/github/last-commit/haxpax/gosms) [gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS.
* <code>&nbsp;&nbsp;1233</code> ![](https://img.shields.io/github/last-commit/eapache/go-resiliency) [go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang.
* <code>&nbsp;&nbsp;1155</code> ![](https://img.shields.io/github/last-commit/mojocn/base64Captcha) [base64Captcha](https://github.com/mojocn/base64Captcha) - Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha.
* <code>&nbsp;&nbsp;&nbsp;969</code> ![](https://img.shields.io/github/last-commit/jolestar/go-commons-pool) [go-commons-pool](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang.
* <code>&nbsp;&nbsp;&nbsp;765</code> ![](https://img.shields.io/github/last-commit/llir/llvm) [llvm](https://github.com/llir/llvm) - Library for interacting with LLVM IR in pure Go.
* <code>&nbsp;&nbsp;&nbsp;690</code> ![](https://img.shields.io/github/last-commit/teris-io/shortid) [shortid](https://github.com/teris-io/shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs.
* <code>&nbsp;&nbsp;&nbsp;423</code> ![](https://img.shields.io/github/last-commit/dimiro1/health) [health](https://github.com/dimiro1/health) - Easy to use, extensible health check library.
* <code>&nbsp;&nbsp;&nbsp;391</code> ![](https://img.shields.io/github/last-commit/alexliesenfeld/health) [health](https://github.com/alexliesenfeld/health) - A simple and flexible health check library for Go.
* <code>&nbsp;&nbsp;&nbsp;371</code> ![](https://img.shields.io/github/last-commit/cstockton/go-conv) [conv](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types.
* <code>&nbsp;&nbsp;&nbsp;349</code> ![](https://img.shields.io/github/last-commit/dimiro1/banner) [banner](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications.
* <code>&nbsp;&nbsp;&nbsp;313</code> ![](https://img.shields.io/github/last-commit/pariz/gountries) [gountries](https://github.com/pariz/gountries) - Package that exposes country and subdivision data.
* <code>&nbsp;&nbsp;&nbsp;289</code> ![](https://img.shields.io/github/last-commit/qmuntal/stateless) [stateless](https://github.com/qmuntal/stateless) - A fluent library for creating state machines.
* <code>&nbsp;&nbsp;&nbsp;233</code> ![](https://img.shields.io/github/last-commit/go-ffmt/ffmt) [ffmt](https://github.com/go-ffmt/ffmt) - Beautify data display for Humans.
* <code>&nbsp;&nbsp;&nbsp;221</code> ![](https://img.shields.io/github/last-commit/containrrr/shoutrrr) [shoutrrr](https://github.com/containrrr/shoutrrr) - Notification library providing easy access to various messaging services like slack, mattermost, gotify and smtp among others.
* <code>&nbsp;&nbsp;&nbsp;211</code> ![](https://img.shields.io/github/last-commit/hyperboloide/lk) [lk](https://github.com/hyperboloide/lk) - A simple licensing library for golang.
* <code>&nbsp;&nbsp;&nbsp;210</code> ![](https://img.shields.io/github/last-commit/antchfx/antch) [antch](https://github.com/antchfx/antch) - A fast, powerful and extensible web crawling & scraping framework.
* <code>&nbsp;&nbsp;&nbsp;190</code> ![](https://img.shields.io/github/last-commit/etherlabsio/healthcheck) [healthcheck](https://github.com/etherlabsio/healthcheck) - An opinionated and concurrent health-check HTTP handler for RESTful services.
* <code>&nbsp;&nbsp;&nbsp;190</code> ![](https://img.shields.io/github/last-commit/distatus/battery) [battery](https://github.com/distatus/battery) - Cross-platform, normalized battery information library.
* <code>&nbsp;&nbsp;&nbsp;163</code> ![](https://img.shields.io/github/last-commit/icza/bitio) [bitio](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go.
* <code>&nbsp;&nbsp;&nbsp;154</code> ![](https://img.shields.io/github/last-commit/go-playground/stats) [stats](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...
* <code>&nbsp;&nbsp;&nbsp;145</code> ![](https://img.shields.io/github/last-commit/gen2brain/go-unarr) [go-unarr](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives.
* <code>&nbsp;&nbsp;&nbsp;123</code> ![](https://img.shields.io/github/last-commit/hackebrot/turtle) [turtle](https://github.com/hackebrot/turtle) - Emojis for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;94</code> ![](https://img.shields.io/github/last-commit/antham/gommit) [gommit](https://github.com/antham/gommit) - Analyze git commit messages to ensure they follow defined patterns.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;90</code> ![](https://img.shields.io/github/last-commit/cabify/gotoprom) [gotoprom](https://github.com/cabify/gotoprom) - Type-safe metrics builder wrapper library for the official Prometheus client.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;87</code> ![](https://img.shields.io/github/last-commit/osamingo/indigo) [indigo](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;79</code> ![](https://img.shields.io/github/last-commit/steambap/captcha) [captcha](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;68</code> ![](https://img.shields.io/github/last-commit/alwindoss/morse) [morse](https://github.com/alwindoss/morse) - Library to convert to and from morse code.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;56</code> ![](https://img.shields.io/github/last-commit/mavihq/persian) [persian](https://github.com/mavihq/persian) - Some utilities for Persian language in go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;52</code> ![](https://img.shields.io/github/last-commit/hyperboloide/pdfgen) [pdfgen](https://github.com/hyperboloide/pdfgen) - HTTP service to generate PDF from Json requests.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> ![](https://img.shields.io/github/last-commit/go-xkg/xkg) [xkg](https://github.com/go-xkg/xkg) - X Keyboard Grabber.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> ![](https://img.shields.io/github/last-commit/pioz/faker) [faker](https://github.com/pioz/faker) - Random fake data and struct generator for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> ![](https://img.shields.io/github/last-commit/digitalcrab/browscap_go) [browscap_go](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](http://browscap.org/).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> ![](https://img.shields.io/github/last-commit/miolini/datacounter) [datacounter](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> ![](https://img.shields.io/github/last-commit/artyom/autoflags) [autoflags](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> ![](https://img.shields.io/github/last-commit/pantrif/url-shortener) [url-shortener](https://github.com/pantrif/url-shortener) - A modern, powerful, and robust URL shortener microservice with mysql support.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> ![](https://img.shields.io/github/last-commit/aofei/sandid) [sandid](https://github.com/aofei/sandid) - Every grain of sand on earth has its own ID.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> ![](https://img.shields.io/github/last-commit/rkoesters/xdg) [xdg](https://github.com/rkoesters/xdg) - FreeDesktop.org (xdg) Specs implemented in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> ![](https://img.shields.io/github/last-commit/osamingo/gosh) [gosh](https://github.com/osamingo/gosh) - Provide Go Statistics Handler, Struct, Measure Method.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> ![](https://img.shields.io/github/last-commit/pascaldekloe/metrics) [metrics](https://github.com/pascaldekloe/metrics) - Library for metrics instrumentation and Prometheus exposition.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/Wing924/shellwords) [shellwords](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> ![](https://img.shields.io/github/last-commit/mudler/anagent) [anagent](https://github.com/mudler/anagent) - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/kirillDanshin/avgRating) [avgRating](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/Wing924/hostutils) [hostutils](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking FQDNs list.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/lrita/numa) [numa](https://github.com/lrita/numa) - NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/azr/generators) [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and output handling.
* [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.

## Natural Language Processing

*Libraries for working with human languages.*

* <code>&nbsp;&nbsp;2780</code> ![](https://img.shields.io/github/last-commit/jdkato/prose) [prose](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only.
* <code>&nbsp;&nbsp;1720</code> ![](https://img.shields.io/github/last-commit/nicksnyder/go-i18n) [go-i18n](https://github.com/nicksnyder/go-i18n/) - Package and an accompanying tool to work with localized text.
* <code>&nbsp;&nbsp;1615</code> ![](https://img.shields.io/github/last-commit/go-ego/gse) [gse](https://github.com/go-ego/gse) - Go efficient text segmentation; support english, chinese, japanese and other.
* <code>&nbsp;&nbsp;1562</code> ![](https://img.shields.io/github/last-commit/yanyiwu/gojieba) [gojieba](https://github.com/yanyiwu/gojieba) - This is a Go implementation of <code>&nbsp;26753</code> ![](https://img.shields.io/github/last-commit/fxsjy/jieba) [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm.
* <code>&nbsp;&nbsp;1123</code> ![](https://img.shields.io/github/last-commit/olebedev/when) [when](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules.
* <code>&nbsp;&nbsp;&nbsp;993</code> ![](https://img.shields.io/github/last-commit/mozillazg/go-pinyin) [go-pinyin](https://github.com/mozillazg/go-pinyin) - CN Hanzi to Hanyu Pinyin converter.
* <code>&nbsp;&nbsp;&nbsp;948</code> ![](https://img.shields.io/github/last-commit/nlpodyssey/spago) [spaGO](https://github.com/nlpodyssey/spago) - Self-contained Machine Learning and Natural Language Processing library in Go.
* <code>&nbsp;&nbsp;&nbsp;579</code> ![](https://img.shields.io/github/last-commit/ikawaha/kagome) [kagome](https://github.com/ikawaha/kagome) - JP morphological analyzer written in pure Go.
* <code>&nbsp;&nbsp;&nbsp;502</code> ![](https://img.shields.io/github/last-commit/abadojack/whatlanggo) [whatlanggo](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc).
* <code>&nbsp;&nbsp;&nbsp;369</code> ![](https://img.shields.io/github/last-commit/Shixzie/nlp) [nlp](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp.
* <code>&nbsp;&nbsp;&nbsp;334</code> ![](https://img.shields.io/github/last-commit/james-bowman/nlp) [nlp](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis).
* <code>&nbsp;&nbsp;&nbsp;306</code> ![](https://img.shields.io/github/last-commit/neurosnap/sentences) [sentences](https://github.com/neurosnap/sentences) - Sentence tokenizer: converts text into a list of sentences.
* <code>&nbsp;&nbsp;&nbsp;119</code> ![](https://img.shields.io/github/last-commit/rylans/getlang) [getlang](https://github.com/rylans/getlang) - Fast natural language detection package.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;89</code> ![](https://img.shields.io/github/last-commit/mozillazg/go-unidecode) [go-unidecode](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;89</code> ![](https://img.shields.io/github/last-commit/nuance/go-nlp) [go-nlp](https://github.com/nuance/go-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;83</code> ![](https://img.shields.io/github/last-commit/afjoseph/RAKE.Go) [RAKE.go](https://github.com/afjoseph/RAKE.Go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;73</code> ![](https://img.shields.io/github/last-commit/fiam/gounidecode) [gounidecode](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;65</code> ![](https://img.shields.io/github/last-commit/pebbe/textcat) [textcat](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;63</code> ![](https://img.shields.io/github/last-commit/blevesearch/segment) [segment](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/)
* <code>&nbsp;&nbsp;&nbsp;&nbsp;63</code> ![](https://img.shields.io/github/last-commit/agonopol/go-stem) [go-stem](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> ![](https://img.shields.io/github/last-commit/awsong/MMSEGO) [MMSEGO](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> ![](https://img.shields.io/github/last-commit/dchest/stemmer) [stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> ![](https://img.shields.io/github/last-commit/danieldk/go2vec) [go2vec](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> ![](https://img.shields.io/github/last-commit/zhenjl/porter2) [porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> ![](https://img.shields.io/github/last-commit/striker2000/petrovich) [petrovich](https://github.com/striker2000/petrovich) - Petrovich is the library which inflects Russian names to given grammatical case.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> ![](https://img.shields.io/github/last-commit/bojanz/address) [address](https://github.com/bojanz/address) - Handles address representation, validation and formatting.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> ![](https://img.shields.io/github/last-commit/goodsign/snowball) [snowball](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> ![](https://img.shields.io/github/last-commit/rookii/paicehusk) [paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> ![](https://img.shields.io/github/last-commit/dveselov/mystem) [go-mystem](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> ![](https://img.shields.io/github/last-commit/m1/go-localize) [go-localize](https://github.com/m1/go-localize) - Simple and easy to use i18n (Internationalization and localization) engine - used for translating locale strings.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> ![](https://img.shields.io/github/last-commit/mehanizm/iuliia-go) [iuliia-go](https://github.com/mehanizm/iuliia-go) - Transliterate Cyrillic → Latin in every possible way.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> ![](https://img.shields.io/github/last-commit/goodsign/icu) [icu](https://github.com/goodsign/icu) - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> ![](https://img.shields.io/github/last-commit/rjohnsondev/golibstemmer) [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/jonreiter/govader) [govader](https://github.com/jonreiter/govader) - Go implementation of <code>&nbsp;&nbsp;3102</code> ![](https://img.shields.io/github/last-commit/cjhutto/vaderSentiment) [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/alexsergivan/transliterator) [transliterator](https://github.com/alexsergivan/transliterator) - Provides one-way string transliteration with supporting of language-specific transliteration rules.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/osamingo/shamoji) [shamoji](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/xujiajun/gotokenizer) [gotokenizer](https://github.com/xujiajun/gotokenizer) - A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation)
* <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/goodsign/libtextcat) [libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/detectlanguage/detectlanguage-go) [detectlanguage](https://github.com/detectlanguage/detectlanguage-go) - Language Detection API Go Client. Supports batch requests, short phrase or single word language detection.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> ![](https://img.shields.io/github/last-commit/a2800276/porter) [porter](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/dinopuguh/gosentiwordnet) [gosentiwordnet](https://github.com/dinopuguh/gosentiwordnet) - Sentiment analyzer using sentiwordnet lexicon in Go.

## Networking

*Libraries for working with various layers of the network.*

* <code>&nbsp;15698</code> ![](https://img.shields.io/github/last-commit/valyala/fasthttp) [fasthttp](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http.
* <code>&nbsp;12515</code> ![](https://img.shields.io/github/last-commit/xtaci/kcptun) [kcptun](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol.
* <code>&nbsp;&nbsp;7597</code> ![](https://img.shields.io/github/last-commit/pions/webrtc) [webrtc](https://github.com/pions/webrtc) - A pure Go implementation of the WebRTC API.
* <code>&nbsp;&nbsp;5689</code> ![](https://img.shields.io/github/last-commit/miekg/dns) [dns](https://github.com/miekg/dns) - Go library for working with DNS.
* <code>&nbsp;&nbsp;5639</code> ![](https://img.shields.io/github/last-commit/lucas-clemente/quic-go) [quic-go](https://github.com/lucas-clemente/quic-go) - An implementation of the QUIC protocol in pure Go.
* <code>&nbsp;&nbsp;4943</code> ![](https://img.shields.io/github/last-commit/panjf2000/gnet) [gnet](https://github.com/panjf2000/gnet) - `gnet` is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go.
* <code>&nbsp;&nbsp;4275</code> ![](https://img.shields.io/github/last-commit/google/gopacket) [gopacket](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings.
* <code>&nbsp;&nbsp;3710</code> ![](https://img.shields.io/github/last-commit/gchaincl/httplab) [HTTPLab](https://github.com/gchaincl/httplab) - HTTPLabs let you inspect HTTP requests and forge responses.
* <code>&nbsp;&nbsp;3044</code> ![](https://img.shields.io/github/last-commit/xtaci/kcp-go) [kcp-go](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol.
* <code>&nbsp;&nbsp;2252</code> ![](https://img.shields.io/github/last-commit/osrg/gobgp) [gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language.
* <code>&nbsp;&nbsp;2108</code> ![](https://img.shields.io/github/last-commit/gliderlabs/ssh) [ssh](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh).
* <code>&nbsp;&nbsp;1994</code> ![](https://img.shields.io/github/last-commit/fortio/fortio) [fortio](https://github.com/fortio/fortio) - Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC.
* <code>&nbsp;&nbsp;1274</code> ![](https://img.shields.io/github/last-commit/songgao/water) [water](https://github.com/songgao/water) - Simple TUN/TAP library.
* <code>&nbsp;&nbsp;1216</code> ![](https://img.shields.io/github/last-commit/Allenxuxu/gev) [gev](https://github.com/Allenxuxu/gev) - gev is a lightweight, fast non-blocking TCP network library based on Reactor mode.
* <code>&nbsp;&nbsp;1206</code> ![](https://img.shields.io/github/last-commit/hashicorp/go-getter) [go-getter](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL.
* <code>&nbsp;&nbsp;1080</code> ![](https://img.shields.io/github/last-commit/intel-go/nff-go) [NFF-Go](https://github.com/intel-go/nff-go) - Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF).
* <code>&nbsp;&nbsp;1031</code> ![](https://img.shields.io/github/last-commit/pkg/sftp) [sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt.
* <code>&nbsp;&nbsp;&nbsp;886</code> ![](https://img.shields.io/github/last-commit/cavaliercoder/grab) [grab](https://github.com/cavaliercoder/grab) - Go package for managing file downloads.
* <code>&nbsp;&nbsp;&nbsp;823</code> ![](https://img.shields.io/github/last-commit/jlaffaye/ftp) [ftp](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959).
* <code>&nbsp;&nbsp;&nbsp;784</code> ![](https://img.shields.io/github/last-commit/hashicorp/mdns) [mdns](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang.
* <code>&nbsp;&nbsp;&nbsp;744</code> ![](https://img.shields.io/github/last-commit/soniah/gosnmp) [gosnmp](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions.
* <code>&nbsp;&nbsp;&nbsp;729</code> ![](https://img.shields.io/github/last-commit/yahoo/vssh) [vssh](https://github.com/yahoo/vssh) - Go library for building network and server automation over SSH protocol.
* <code>&nbsp;&nbsp;&nbsp;625</code> ![](https://img.shields.io/github/last-commit/fanux/lhttp) [lhttp](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily.
* <code>&nbsp;&nbsp;&nbsp;623</code> ![](https://img.shields.io/github/last-commit/yl2chen/cidranger) [cidranger](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup for Go.
* <code>&nbsp;&nbsp;&nbsp;496</code> ![](https://img.shields.io/github/last-commit/schollz/peerdiscovery) [peerdiscovery](https://github.com/schollz/peerdiscovery) - Pure Go library for cross-platform local peer discovery using UDP multicast.
* <code>&nbsp;&nbsp;&nbsp;486</code> ![](https://img.shields.io/github/last-commit/gansidui/gotcp) [gotcp](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications.
* <code>&nbsp;&nbsp;&nbsp;470</code> ![](https://img.shields.io/github/last-commit/go-rtc/stun) [stun](https://github.com/go-rtc/stun) - Go implementation of RFC 5389 STUN protocol.
* <code>&nbsp;&nbsp;&nbsp;448</code> ![](https://img.shields.io/github/last-commit/ccding/go-stun) [go-stun](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389).
* <code>&nbsp;&nbsp;&nbsp;428</code> ![](https://img.shields.io/github/last-commit/akrennmair/gopcap) [gopcap](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap.
* <code>&nbsp;&nbsp;&nbsp;423</code> ![](https://img.shields.io/github/last-commit/DrmagicE/gmqtt) [gmqtt](https://github.com/DrmagicE/gmqtt) - Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1.
* <code>&nbsp;&nbsp;&nbsp;400</code> ![](https://img.shields.io/github/last-commit/mdlayher/raw) [raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface.
* <code>&nbsp;&nbsp;&nbsp;385</code> ![](https://img.shields.io/github/last-commit/firstrow/tcp_server) [tcp_server](https://github.com/firstrow/tcp_server) - Go library for building tcp servers faster.
* <code>&nbsp;&nbsp;&nbsp;375</code> ![](https://img.shields.io/github/last-commit/xtaci/gaio) [gaio](https://github.com/xtaci/gaio) - High performance async-io networking for Golang in proactor mode.
* <code>&nbsp;&nbsp;&nbsp;319</code> ![](https://img.shields.io/github/last-commit/masterzen/winrm) [winrm](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines.
* <code>&nbsp;&nbsp;&nbsp;259</code> ![](https://img.shields.io/github/last-commit/mdlayher/arp) [arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826.
* <code>&nbsp;&nbsp;&nbsp;254</code> ![](https://img.shields.io/github/last-commit/fclairamb/ftpserverlib) [ftpserverlib](https://github.com/fclairamb/ftpserverlib) - Fully featured FTP server library.
* <code>&nbsp;&nbsp;&nbsp;245</code> ![](https://img.shields.io/github/last-commit/stabbycutyou/buffstreams) [buffstreams](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy.
* <code>&nbsp;&nbsp;&nbsp;243</code> ![](https://img.shields.io/github/last-commit/lesismal/nbio) [nbio](https://github.com/lesismal/nbio) - High-performance, non-blocking, event-driven, easy-to-use, least-dependency networking framework written in Go.
* <code>&nbsp;&nbsp;&nbsp;226</code> ![](https://img.shields.io/github/last-commit/mdlayher/ethernet) [ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags.
* <code>&nbsp;&nbsp;&nbsp;185</code> ![](https://img.shields.io/github/last-commit/google/gnxi) [gNxI](https://github.com/google/gnxi) - A collection of tools for Network Management that use the gNMI and gNOI protocols.
* <code>&nbsp;&nbsp;&nbsp;169</code> ![](https://img.shields.io/github/last-commit/udhos/jazigo) [jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices.
* <code>&nbsp;&nbsp;&nbsp;160</code> ![](https://img.shields.io/github/last-commit/anacrolix/utp) [utp](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation.
* <code>&nbsp;&nbsp;&nbsp;145</code> ![](https://img.shields.io/github/last-commit/zubairhamed/canopus) [canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252).
* <code>&nbsp;&nbsp;&nbsp;130</code> ![](https://img.shields.io/github/last-commit/eduardonunesp/sslb) [sslb](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance.
* <code>&nbsp;&nbsp;&nbsp;122</code> ![](https://img.shields.io/github/last-commit/xfxdev/xtcp) [xtcp](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication, graceful shutdown, and custom protocol.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;70</code> ![](https://img.shields.io/github/last-commit/mdlayher/dhcp6) [dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;69</code> ![](https://img.shields.io/github/last-commit/songgao/ether) [ether](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;56</code> ![](https://img.shields.io/github/last-commit/aerogo/packet) [packet](https://github.com/aerogo/packet) - Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> ![](https://img.shields.io/github/last-commit/ian-kent/linkio) [linkio](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;46</code> ![](https://img.shields.io/github/last-commit/c-robinson/iplib) [iplib](https://github.com/c-robinson/iplib) - Library for working with IP addresses (net.IP, net.IPNet), inspired by python [ipaddress](https://docs.python.org/3/library/ipaddress.html) and ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html)
* <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> ![](https://img.shields.io/github/last-commit/aybabtme/portproxy) [portproxy](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> ![](https://img.shields.io/github/last-commit/joeig/go-powerdns) [go-powerdns](https://github.com/joeig/go-powerdns) - PowerDNS API bindings for Golang.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> ![](https://img.shields.io/github/last-commit/koofr/graval) [graval](https://github.com/koofr/graval) - Experimental FTP server framework.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/yahoo/panoptes-stream) [panoptes-stream](https://github.com/yahoo/panoptes-stream) - A cloud native distributed streaming network telemetry (gNMI, Juniper JTI and Cisco MDT).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> ![](https://img.shields.io/github/last-commit/polera/publicip) [publicip](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> ![](https://img.shields.io/github/last-commit/sunwxg/golibwireshark) [golibwireshark](https://github.com/sunwxg/golibwireshark) - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/averageflow/gohooks) [gohooks](https://github.com/averageflow/gohooks) - GoHooks make it easy to send and consume secured web-hooks from a Go application. Inspired by Spatie's Laravel Webhook Client and Server.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/kirillDanshin/llb) [llb](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/sunwxg/goshark) [goshark](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/two/tspool) [tspool](https://github.com/two/tspool) - A TCP Library use worker pool to improve performance and protect your server.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/wzshiming/httpproxy) [httpproxy](https://github.com/wzshiming/httpproxy) - HTTP proxy handler and dialer.
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.

### HTTP Clients

*Libraries for making HTTP requests.*

* <code>&nbsp;&nbsp;4634</code> ![](https://img.shields.io/github/last-commit/go-resty/resty) [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.
* <code>&nbsp;&nbsp;2004</code> ![](https://img.shields.io/github/last-commit/gojektech/heimdall) [heimdall](https://github.com/gojektech/heimdall) - An enchanced http client with retry and hystrix capabilities.
* <code>&nbsp;&nbsp;1811</code> ![](https://img.shields.io/github/last-commit/levigross/grequests) [grequests](https://github.com/levigross/grequests) - A Go "clone" of the great and famous Requests library.
* <code>&nbsp;&nbsp;1343</code> ![](https://img.shields.io/github/last-commit/dghubble/sling) [sling](https://github.com/dghubble/sling) - Sling is a Go HTTP client library for creating and sending API requests.
* <code>&nbsp;&nbsp;&nbsp;907</code> ![](https://img.shields.io/github/last-commit/h2non/gentleman) [gentleman](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library.
* <code>&nbsp;&nbsp;&nbsp;555</code> ![](https://img.shields.io/github/last-commit/sethgrid/pester) [pester](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency.
* <code>&nbsp;&nbsp;&nbsp;131</code> ![](https://img.shields.io/github/last-commit/monaco-io/request) [request](https://github.com/monaco-io/request) - HTTP client for golang. If you have experience about axios or requests, you will love it. No 3rd dependency.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> ![](https://img.shields.io/github/last-commit/ddo/rq) [rq](https://github.com/ddo/rq) - A nicer interface for golang stdlib HTTP client.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/bozd4g/go-http-client) [go-http-client](https://github.com/bozd4g/go-http-client) - Make http calls simply and easily.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/ybbus/httpretry) [httpretry](https://github.com/ybbus/httpretry) - Enriches the default go HTTP client with retry functionality.

## OpenGL

*Libraries for using OpenGL in Go.*

* <code>&nbsp;&nbsp;1127</code> ![](https://img.shields.io/github/last-commit/go-gl/glfw) [glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3.
* <code>&nbsp;&nbsp;&nbsp;818</code> ![](https://img.shields.io/github/last-commit/go-gl/gl) [gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow).
* <code>&nbsp;&nbsp;&nbsp;387</code> ![](https://img.shields.io/github/last-commit/go-gl/mathgl) [mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM.
* <code>&nbsp;&nbsp;&nbsp;151</code> ![](https://img.shields.io/github/last-commit/goxjs/gl) [goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;70</code> ![](https://img.shields.io/github/last-commit/goxjs/glfw) [goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> ![](https://img.shields.io/github/last-commit/technohippy/go-glmatrix) [go-glmatrix](https://github.com/technohippy/go-glmatrix) - Go port of [glMatrix](http://glmatrix.net/) library.

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* <code>&nbsp;24726</code> ![](https://img.shields.io/github/last-commit/go-gorm/gorm) [GORM](https://github.com/go-gorm/gorm) - The fantastic ORM library for Golang, aims to be developer friendly.
* <code>&nbsp;&nbsp;7872</code> ![](https://img.shields.io/github/last-commit/facebook/ent) [ent](https://github.com/facebook/ent) - An entity framework for Go. Simple, yet powerful ORM for modeling and querying data.
* <code>&nbsp;&nbsp;4745</code> ![](https://img.shields.io/github/last-commit/go-pg/pg) [go-pg](https://github.com/go-pg/pg) - PostgreSQL ORM with focus on PostgreSQL specific features and performance.
* <code>&nbsp;&nbsp;4102</code> ![](https://img.shields.io/github/last-commit/volatiletech/sqlboiler) [SQLBoiler](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema.
* <code>&nbsp;&nbsp;3510</code> ![](https://img.shields.io/github/last-commit/go-gorp/gorp) [gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go.
* <code>&nbsp;&nbsp;2673</code> ![](https://img.shields.io/github/last-commit/upper/db) [upper.io/db](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.
* <code>&nbsp;&nbsp;1332</code> ![](https://img.shields.io/github/last-commit/xxjwxc/gormt) [gormt](https://github.com/xxjwxc/gormt) - Mysql database to golang gorm struct.
* <code>&nbsp;&nbsp;1157</code> ![](https://img.shields.io/github/last-commit/go-reform/reform) [reform](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation.
* <code>&nbsp;&nbsp;1100</code> ![](https://img.shields.io/github/last-commit/gobuffalo/pop) [pop/soda](https://github.com/gobuffalo/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* <code>&nbsp;&nbsp;&nbsp;627</code> ![](https://img.shields.io/github/last-commit/jirfag/go-queryset) [go-queryset](https://github.com/jirfag/go-queryset) - 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM.
* <code>&nbsp;&nbsp;&nbsp;616</code> ![](https://img.shields.io/github/last-commit/huandu/go-sqlbuilder) [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) - A flexible and powerful SQL string builder library plus a zero-config ORM.
* <code>&nbsp;&nbsp;&nbsp;398</code> ![](https://img.shields.io/github/last-commit/go-rel/rel) [rel](https://github.com/go-rel/rel) - Modern Database Access Layer for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API.
* <code>&nbsp;&nbsp;&nbsp;278</code> ![](https://img.shields.io/github/last-commit/albrow/zoom) [Zoom](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis.
* <code>&nbsp;&nbsp;&nbsp;215</code> ![](https://img.shields.io/github/last-commit/astaxie/beego) [beego orm](https://github.com/astaxie/beego/tree/master/orm) - Powerful orm framework for go. Support: pq/mysql/sqlite3.
* <code>&nbsp;&nbsp;&nbsp;151</code> ![](https://img.shields.io/github/last-commit/Fs02/grimoire) [grimoire](https://github.com/Fs02/grimoire) - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3).
* <code>&nbsp;&nbsp;&nbsp;143</code> ![](https://img.shields.io/github/last-commit/rushteam/gosql) [go-sql](https://github.com/rushteam/gosql) - A easy ORM for mysql.
* <code>&nbsp;&nbsp;&nbsp;102</code> ![](https://img.shields.io/github/last-commit/gosuri/go-store) [go-store](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> ![](https://img.shields.io/github/last-commit/jschoedt/go-firestorm) [go-firestorm](https://github.com/jschoedt/go-firestorm) - A simple ORM for Google/Firebase Cloud Firestore.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/abrahambotros/lore) [lore](https://github.com/abrahambotros/lore) - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/marlow/marlow) [marlow](https://github.com/marlow/marlow) - Generated ORM from project structs for compile time safety assurances.
* [XORM](https://gitea.com/xorm/xorm) - Simple and powerful ORM for Go. (Support: MySQL, MyMysql, PostgreSQL, Tidb, SQLite3, MsSql and Oracle).

## Package Management

*Official tooling for dependency and package management*

* [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) - Modules are the unit of source code interchange and versioning. The go command has direct support for working with modules, including recording and resolving dependencies on other modules.

*Official experimental tooling for package management*

* <code>&nbsp;13150</code> ![](https://img.shields.io/github/last-commit/golang/dep) [dep](https://github.com/golang/dep) - Go dependency tool.
* [vgo](https://go.googlesource.com/vgo/) - Versioned Go.

*Unofficial libraries for package and dependency management.*

* <code>&nbsp;&nbsp;8111</code> ![](https://img.shields.io/github/last-commit/Masterminds/glide) [glide](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip.
* <code>&nbsp;&nbsp;5613</code> ![](https://img.shields.io/github/last-commit/tools/godep) [godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.
* <code>&nbsp;&nbsp;5004</code> ![](https://img.shields.io/github/last-commit/kardianos/govendor) [govendor](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file.
* <code>&nbsp;&nbsp;2494</code> ![](https://img.shields.io/github/last-commit/gpmgo/gopm) [gopm](https://github.com/gpmgo/gopm) - Go Package Manager.
* <code>&nbsp;&nbsp;1394</code> ![](https://img.shields.io/github/last-commit/mattn/gom) [gom](https://github.com/mattn/gom) - Go Manager - bundle for go.
* <code>&nbsp;&nbsp;1197</code> ![](https://img.shields.io/github/last-commit/pote/gpm) [gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go.
* <code>&nbsp;&nbsp;&nbsp;778</code> ![](https://img.shields.io/github/last-commit/nitrous-io/goop) [goop](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler.
* <code>&nbsp;&nbsp;&nbsp;382</code> ![](https://img.shields.io/github/last-commit/lucasepe/modgv) [modgv](https://github.com/lucasepe/modgv) - Converts 'go mod graph' output into Graphviz's DOT language.
* <code>&nbsp;&nbsp;&nbsp;239</code> ![](https://img.shields.io/github/last-commit/jingweno/nut) [nut](https://github.com/jingweno/nut) - Vendor Go dependencies.
* <code>&nbsp;&nbsp;&nbsp;215</code> ![](https://img.shields.io/github/last-commit/VividCortex/johnny-deps) [johnny-deps](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git.
* <code>&nbsp;&nbsp;&nbsp;131</code> ![](https://img.shields.io/github/last-commit/raydac/mvn-golang) [mvn-golang](https://github.com/raydac/mvn-golang) - plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure.
* <code>&nbsp;&nbsp;&nbsp;120</code> ![](https://img.shields.io/github/last-commit/DamnWidget/VenGO) [VenGO](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> ![](https://img.shields.io/github/last-commit/lunny/gop) [gop](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH.

## Performance

* <code>&nbsp;14003</code> ![](https://img.shields.io/github/last-commit/jaegertracing/jaeger) [jaeger](https://github.com/jaegertracing/jaeger) - A distributed tracing system.
* <code>&nbsp;&nbsp;1726</code> ![](https://img.shields.io/github/last-commit/pixie-labs/pixie) [pixie](https://github.com/pixie-labs/pixie) - No instrumentation tracing for Golang applications via eBPF.
* <code>&nbsp;&nbsp;1537</code> ![](https://img.shields.io/github/last-commit/pkg/profile) [profile](https://github.com/pkg/profile) - Simple profiling support package for Go.
* <code>&nbsp;&nbsp;1429</code> ![](https://img.shields.io/github/last-commit/arl/statsviz) [statsviz](https://github.com/arl/statsviz) - Live visualization of your Go application runtime statistics.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> ![](https://img.shields.io/github/last-commit/kamilsk/tracer) [tracer](https://github.com/kamilsk/tracer) - Simple, lightweight tracing.

## Query Language

* <code>&nbsp;&nbsp;7861</code> ![](https://img.shields.io/github/last-commit/graphql-go/graphql) [graphql-go](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go.
* <code>&nbsp;&nbsp;6354</code> ![](https://img.shields.io/github/last-commit/99designs/gqlgen) [gqlgen](https://github.com/99designs/gqlgen) - go generate based graphql server library.
* <code>&nbsp;&nbsp;3830</code> ![](https://img.shields.io/github/last-commit/neelance/graphql-go) [graphql](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use.
* <code>&nbsp;&nbsp;1708</code> ![](https://img.shields.io/github/last-commit/thedevsaddam/gojsonq) [gojsonq](https://github.com/thedevsaddam/gojsonq) - A simple Go package to Query over JSON Data.
* <code>&nbsp;&nbsp;1154</code> ![](https://img.shields.io/github/last-commit/tomwright/dasel) [dasel](https://github.com/tomwright/dasel) - Query and update data structures using selectors from the command line. Comparable to jq/yq but supports JSON, YAML, TOML and XML with zero runtime dependencies.
* <code>&nbsp;&nbsp;&nbsp;245</code> ![](https://img.shields.io/github/last-commit/elgs/jsonql) [jsonql](https://github.com/elgs/jsonql) - JSON query expression library in Golang.
* <code>&nbsp;&nbsp;&nbsp;218</code> ![](https://img.shields.io/github/last-commit/a8m/rql) [rql](https://github.com/a8m/rql) - Resource Query Language for REST API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> ![](https://img.shields.io/github/last-commit/tmc/graphql) [graphql](https://github.com/tmc/graphql) - graphql parser + utilities.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> ![](https://img.shields.io/github/last-commit/bhmj/jsonslice) [jsonslice](https://github.com/bhmj/jsonslice) - Jsonpath queries with advanced filters.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> ![](https://img.shields.io/github/last-commit/ccbrown/api-fu) [api-fu](https://github.com/ccbrown/api-fu) - Comprehensive GraphQL implementation.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> ![](https://img.shields.io/github/last-commit/SonicRoshan/straf) [straf](https://github.com/SonicRoshan/straf) - Easily Convert Golang structs to GraphQL objects.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/timsolov/rest-query-parser) [rqp](https://github.com/timsolov/rest-query-parser) - Query Parser for REST API. Filtering, validations, both `AND`, `OR` operations are supported directly in the query.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/AsaiYusuke/jsonpath) [jsonpath](https://github.com/AsaiYusuke/jsonpath) - A query library for retrieving part of JSON based on JSONPath syntax.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/Zaba505/gws) [gws](https://github.com/Zaba505/gws) - Apollos' "GraphQL over Websocket" client and server implementation.

## Resource Embedding

* <code>&nbsp;&nbsp;3252</code> ![](https://img.shields.io/github/last-commit/gobuffalo/packr) [packr](https://github.com/gobuffalo/packr) - The simple and easy way to embed static files into Go binaries.
* <code>&nbsp;&nbsp;3235</code> ![](https://img.shields.io/github/last-commit/rakyll/statik) [statik](https://github.com/rakyll/statik) - Embeds static files into a Go executable.
* <code>&nbsp;&nbsp;2233</code> ![](https://img.shields.io/github/last-commit/GeertJohan/go.rice) [go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as HTML, JS, CSS, images, and templates very easy.
* <code>&nbsp;&nbsp;&nbsp;932</code> ![](https://img.shields.io/github/last-commit/shurcooL/vfsgen) [vfsgen](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem.
* <code>&nbsp;&nbsp;&nbsp;601</code> ![](https://img.shields.io/github/last-commit/mjibson/esc) [esc](https://github.com/mjibson/esc) - Embeds files into Go programs and provides http.FileSystem interfaces to them.
* <code>&nbsp;&nbsp;&nbsp;587</code> ![](https://img.shields.io/github/last-commit/UnnoTed/fileb0x) [fileb0x](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use.
* <code>&nbsp;&nbsp;&nbsp;172</code> ![](https://img.shields.io/github/last-commit/omeid/go-resources) [go-resources](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;63</code> ![](https://img.shields.io/github/last-commit/go-playground/statics) [statics](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> ![](https://img.shields.io/github/last-commit/wlbr/templify) [templify](https://github.com/wlbr/templify) - Embed external template files into Go code to create single file binaries.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/soypat/rebed) [rebed](https://github.com/soypat/rebed) - Recreate folder structures and files from Go 1.16's `embed.FS` type
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/leaanthony/debme) [debme](https://github.com/leaanthony/debme) - Create an `embed.FS` from an existing `embed.FS` subdirectory.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/wlbr/mule) [mule](https://github.com/wlbr/mule) - Embed external resources like images, movies ... into Go source code to create single file binaries using `go generate`. Focussed on simplicity.

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* <code>&nbsp;&nbsp;5071</code> ![](https://img.shields.io/github/last-commit/gonum/gonum) [gonum](https://github.com/gonum/gonum) - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more.
* <code>&nbsp;&nbsp;2027</code> ![](https://img.shields.io/github/last-commit/montanaflynn/stats) [stats](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library.
* <code>&nbsp;&nbsp;1953</code> ![](https://img.shields.io/github/last-commit/gonum/plot) [gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go.
* <code>&nbsp;&nbsp;1596</code> ![](https://img.shields.io/github/last-commit/cpmech/gosl) [gosl](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more.
* <code>&nbsp;&nbsp;1312</code> ![](https://img.shields.io/github/last-commit/nytlabs/streamtools) [streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data.
* <code>&nbsp;&nbsp;&nbsp;741</code> ![](https://img.shields.io/github/last-commit/mjibson/go-dsp) [go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go.
* <code>&nbsp;&nbsp;&nbsp;682</code> ![](https://img.shields.io/github/last-commit/vdobler/chart) [chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types.
* <code>&nbsp;&nbsp;&nbsp;644</code> ![](https://img.shields.io/github/last-commit/gyuho/goraph) [goraph](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorith visualization).
* <code>&nbsp;&nbsp;&nbsp;583</code> ![](https://img.shields.io/github/last-commit/rocketlaunchr/dataframe-go) [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) - Dataframes for machine-learning and statistics (similar to pandas).
* <code>&nbsp;&nbsp;&nbsp;469</code> ![](https://img.shields.io/github/last-commit/yourbasic/graph) [graph](https://github.com/yourbasic/graph) - Library of basic graph algorithms.
* <code>&nbsp;&nbsp;&nbsp;411</code> ![](https://img.shields.io/github/last-commit/paulmach/orb) [orb](https://github.com/paulmach/orb) - 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support.
* <code>&nbsp;&nbsp;&nbsp;336</code> ![](https://img.shields.io/github/last-commit/VividCortex/ewma) [ewma](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages.
* <code>&nbsp;&nbsp;&nbsp;314</code> ![](https://img.shields.io/github/last-commit/nikolaydubina/calendarheatmap) [calendarheatmap](https://github.com/nikolaydubina/calendarheatmap) - Calendar heatmap in plain Go inspired by Github contribution activity.
* <code>&nbsp;&nbsp;&nbsp;156</code> ![](https://img.shields.io/github/last-commit/VividCortex/gohistogram) [gohistogram](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams.
* <code>&nbsp;&nbsp;&nbsp;142</code> ![](https://img.shields.io/github/last-commit/DavidBelicza/TextRank) [TextRank](https://github.com/DavidBelicza/TextRank) - TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support.
* <code>&nbsp;&nbsp;&nbsp;119</code> ![](https://img.shields.io/github/last-commit/james-bowman/sparse) [sparse](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;76</code> ![](https://img.shields.io/github/last-commit/milosgajdos/go-estimate) [go-estimate](https://github.com/milosgajdos/go-estimate) - State estimation and filtering algorithms in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;70</code> ![](https://img.shields.io/github/last-commit/alixaxel/pagerank) [pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> ![](https://img.shields.io/github/last-commit/skelterjohn/geom) [geom](https://github.com/skelterjohn/geom) - 2D geometry for golang.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;44</code> ![](https://img.shields.io/github/last-commit/soniah/evaler) [evaler](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> ![](https://img.shields.io/github/last-commit/kzahedi/goent) [goent](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/tchayen/triangolatte) [triangolatte](https://github.com/tchayen/triangolatte) - 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> ![](https://img.shields.io/github/last-commit/db47h/decimal) [decimal](https://github.com/db47h/decimal) - Package decimal implements arbitrary-precision decimal floating-point arithmetic.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> ![](https://img.shields.io/github/last-commit/sgreben/piecewiselinear) [piecewiselinear](https://github.com/sgreben/piecewiselinear) - Tiny linear interpolation library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> ![](https://img.shields.io/github/last-commit/nikolaydubina/jsonl-graph) [jsonl-graph](https://github.com/nikolaydubina/jsonl-graph) - Tool to manipulate JSONL graphs with graphviz support.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/soypat/godesim) [godesim](https://github.com/soypat/godesim) - Extended/multivariable ODE solver framework for event-based simulations with simple API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/OGFris/GoStats) [GoStats](https://github.com/OGFris/GoStats) - GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/claygod/PiHex) [PiHex](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> ![](https://img.shields.io/github/last-commit/ChristopherRabotin/ode) [ode](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/ndabAP/assocentity) [assocentity](https://github.com/ndabAP/assocentity) - Package assocentity returns the average distance from words to a given entity.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/khezen/rootfinding) [rootfinding](https://github.com/khezen/rootfinding) - root-finding algorithms library for finding roots of quadratic functions.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/ThePaw/go-gt) [go-gt](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/seanhagen/bradleyterry) [bradleyterry](https://github.com/seanhagen/bradleyterry) - Provides a Bradley-Terry Model for pairwise comparisons.

## Security

*Libraries that are used to help make your application more secure.*

* <code>&nbsp;&nbsp;4730</code> ![](https://img.shields.io/github/last-commit/go-acme/lego) [lego](https://github.com/go-acme/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt).
* <code>&nbsp;&nbsp;2641</code> ![](https://img.shields.io/github/last-commit/Ullaakut/cameradar) [Cameradar](https://github.com/Ullaakut/cameradar) - Tool and library to remotely hack RTSP streams from surveillance cameras.
* <code>&nbsp;&nbsp;1969</code> ![](https://img.shields.io/github/last-commit/awnumar/memguard) [memguard](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory.
* <code>&nbsp;&nbsp;1866</code> ![](https://img.shields.io/github/last-commit/hlandau/acme) [acmetool](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal.
* <code>&nbsp;&nbsp;1796</code> ![](https://img.shields.io/github/last-commit/unrolled/secure) [secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins.
* <code>&nbsp;&nbsp;1320</code> ![](https://img.shields.io/github/last-commit/cossacklabs/themis) [themis](https://github.com/cossacklabs/themis) - high-level cryptographic library for solving typical data security tasks (secure data storage, secure messaging, zero-knowledge proof authentication), available for 14 languages, best fit for multi-platform apps.
* <code>&nbsp;&nbsp;&nbsp;782</code> ![](https://img.shields.io/github/last-commit/cossacklabs/acra) [acra](https://github.com/cossacklabs/acra) - Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system.
* <code>&nbsp;&nbsp;&nbsp;507</code> ![](https://img.shields.io/github/last-commit/kevinburke/nacl) [nacl](https://github.com/kevinburke/nacl) - Go implementation of the NaCL set of API's.
* <code>&nbsp;&nbsp;&nbsp;305</code> ![](https://img.shields.io/github/last-commit/prashantgupta24/firewalld-rest) [firewalld-rest](https://github.com/prashantgupta24/firewalld-rest) - A rest application to dynamically update firewalld rules on a linux server.
* <code>&nbsp;&nbsp;&nbsp;302</code> ![](https://img.shields.io/github/last-commit/ssh-vault/ssh-vault) [ssh-vault](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys.
* <code>&nbsp;&nbsp;&nbsp;298</code> ![](https://img.shields.io/github/last-commit/jaredfolkins/badactor) [BadActor](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban.
* <code>&nbsp;&nbsp;&nbsp;285</code> ![](https://img.shields.io/github/last-commit/lane-c-wagner/go-password-validator) [go-password-validator](https://github.com/lane-c-wagner/go-password-validator) - Password validator based on raw cryptographic entropy values.
* <code>&nbsp;&nbsp;&nbsp;280</code> ![](https://img.shields.io/github/last-commit/pjebs/optimus-go) [optimus-go](https://github.com/pjebs/optimus-go) - ID hashing and Obfuscation using Knuth's Algorithm.
* <code>&nbsp;&nbsp;&nbsp;246</code> ![](https://img.shields.io/github/last-commit/hlandau/passlib) [passlib](https://github.com/hlandau/passlib) - Futureproof password hashing library.
* <code>&nbsp;&nbsp;&nbsp;217</code> ![](https://img.shields.io/github/last-commit/hillu/go-yara) [go-yara](https://github.com/hillu/go-yara) - Go Bindings for <code>&nbsp;&nbsp;&nbsp;123</code> ![](https://img.shields.io/github/last-commit/plusvic/yara) [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)".
* <code>&nbsp;&nbsp;&nbsp;172</code> ![](https://img.shields.io/github/last-commit/elithrar/simple-scrypt) [simple-scrypt](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> ![](https://img.shields.io/github/last-commit/raja/argon2pw) [argon2pw](https://github.com/raja/argon2pw) - Argon2 password hash generation with constant-time password comparison.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;43</code> ![](https://img.shields.io/github/last-commit/dwin/goSecretBoxPassword) [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) - A probably paranoid package for securely hashing and encrypting passwords.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> ![](https://img.shields.io/github/last-commit/m1/go-generate-password) [go-generate-password](https://github.com/m1/go-generate-password) - Password generator that can be used on the cli or as a library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> ![](https://img.shields.io/github/last-commit/mvmaasakkers/certificates) [certificates](https://github.com/mvmaasakkers/certificates) - An opinionated tool for generating tls certificates.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> ![](https://img.shields.io/github/last-commit/xaionaro-go/secureio) [secureio](https://github.com/xaionaro-go/secureio) - An keyexchanging+authenticating+encrypting wrapper and multiplexer for `io.ReadWriteCloser` based on XChaCha20-poly1305, ECDH and ED25519.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/dwin/goArgonPass) [goArgonPass](https://github.com/dwin/goArgonPass) - Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> ![](https://img.shields.io/github/last-commit/andskur/argon2-hashing) [argon2-hashing](https://github.com/andskur/argon2-hashing) - light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/adrianosela/sslmgr) [sslmgr](https://github.com/adrianosela/sslmgr) - SSL certificates made easy with a high level wrapper around acme/autocert.
* [Interpol](https://bitbucket.org/vahidi/interpol) - Rule-based data generator for fuzzing and penetration testing.
* [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) - Auto provision Let's Encrypt certificates and start a TLS server.

## Serialization

*Libraries and tools for binary serialization.*

* <code>&nbsp;&nbsp;9635</code> ![](https://img.shields.io/github/last-commit/json-iterator/go) [jsoniter](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json".
* <code>&nbsp;&nbsp;7811</code> ![](https://img.shields.io/github/last-commit/golang/protobuf) [goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.
* <code>&nbsp;&nbsp;4741</code> ![](https://img.shields.io/github/last-commit/gogo/protobuf) [gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets.
* <code>&nbsp;&nbsp;4737</code> ![](https://img.shields.io/github/last-commit/mitchellh/mapstructure) [mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures.
* <code>&nbsp;&nbsp;1564</code> ![](https://img.shields.io/github/last-commit/ugorji/go) [go-codec](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support.
* <code>&nbsp;&nbsp;&nbsp;614</code> ![](https://img.shields.io/github/last-commit/pascaldekloe/colfer) [colfer](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format.
* <code>&nbsp;&nbsp;&nbsp;556</code> ![](https://img.shields.io/github/last-commit/jszwec/csvutil) [csvutil](https://github.com/jszwec/csvutil) - High Performance, idiomatic CSV record encoding and decoding to native Go structures.
* <code>&nbsp;&nbsp;&nbsp;300</code> ![](https://img.shields.io/github/last-commit/fxamacker/cbor) [cbor](https://github.com/fxamacker/cbor) - Small, safe, and easy CBOR encoding and decoding library.
* <code>&nbsp;&nbsp;&nbsp;279</code> ![](https://img.shields.io/github/last-commit/glycerine/go-capnproto) [go-capnproto](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go.
* <code>&nbsp;&nbsp;&nbsp;150</code> ![](https://img.shields.io/github/last-commit/yvasiyarov/php_session_decoder) [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions.
* <code>&nbsp;&nbsp;&nbsp;124</code> ![](https://img.shields.io/github/last-commit/tuvistavie/structomap) [structomap](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;62</code> ![](https://img.shields.io/github/last-commit/glycerine/bambam) [bambam](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> ![](https://img.shields.io/github/last-commit/PromonLogicalis/asn1) [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> ![](https://img.shields.io/github/last-commit/ghostiam/binstruct) [binstruct](https://github.com/ghostiam/binstruct) - Golang binary decoder for mapping data into the structure.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/epiclabs-io/elastic) [elastic](https://github.com/epiclabs-io/elastic) - Convert slices, maps or any other unknown value across different types at run-time, no matter what.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/o1egl/fwencoder) [fwencoder](https://github.com/o1egl/fwencoder) - Fixed width file parser (encoding and decoding library) for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/vimeda/pletter) [pletter](https://github.com/vimeda/pletter) - A standard way to wrap a proto message for message brokers.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> ![](https://img.shields.io/github/last-commit/32leaves/bel) [bel](https://github.com/32leaves/bel) - Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/huydang284/fixedwidth) [fixedwidth](https://github.com/huydang284/fixedwidth) - Fixed-width text formatting (UTF-8 supported).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> ![](https://img.shields.io/github/last-commit/sbourlon/go-lctree) [go-lctree](https://github.com/sbourlon/go-lctree) - Provides a CLI and primitives to serialize and deserialize [LeetCode binary trees](https://support.leetcode.com/hc/en-us/articles/360011883654-What-does-1-null-2-3-mean-in-binary-tree-representation).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> ![](https://img.shields.io/github/last-commit/recolude/unitpacking) [unitpacking](https://github.com/recolude/unitpacking) - Library to pack unit vectors into as fewest bytes as possible.

## Server Applications

* <code>&nbsp;36793</code> ![](https://img.shields.io/github/last-commit/coreos/etcd) [etcd](https://github.com/coreos/etcd) - Highly-available key value store for shared configuration and service discovery.
* <code>&nbsp;34175</code> ![](https://img.shields.io/github/last-commit/caddyserver/caddy) [Caddy](https://github.com/caddyserver/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use.
* <code>&nbsp;28728</code> ![](https://img.shields.io/github/last-commit/minio/minio) [minio](https://github.com/minio/minio) - Minio is a distributed object storage server.
* <code>&nbsp;&nbsp;5757</code> ![](https://img.shields.io/github/last-commit/spiral/roadrunner) [RoadRunner](https://github.com/spiral/roadrunner) - High-performance PHP application server, load-balancer and process manager.
* <code>&nbsp;&nbsp;3147</code> ![](https://img.shields.io/github/last-commit/cortesi/devd) [devd](https://github.com/cortesi/devd) - Local webserver for developers.
* <code>&nbsp;&nbsp;2817</code> ![](https://img.shields.io/github/last-commit/drakkan/sftpgo) [SFTPGo](https://github.com/drakkan/sftpgo) - Fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. It can serve local filesystem and Cloud Storage backends such as S3 and Google Cloud Storage.
* <code>&nbsp;&nbsp;1830</code> ![](https://img.shields.io/github/last-commit/xyproto/algernon) [algernon](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber.
* <code>&nbsp;&nbsp;1651</code> ![](https://img.shields.io/github/last-commit/getfider/fider) [Fider](https://github.com/getfider/fider) - Fider is an open platform to collect and organize customer feedback.
* <code>&nbsp;&nbsp;1632</code> ![](https://img.shields.io/github/last-commit/checkr/flagr) [Flagr](https://github.com/checkr/flagr) - Flagr is an open-source feature flagging and A/B testing service.
* <code>&nbsp;&nbsp;1533</code> ![](https://img.shields.io/github/last-commit/markphelps/flipt) [flipt](https://github.com/markphelps/flipt) - A self contained feature flag solution written in Go and Vue.js
* <code>&nbsp;&nbsp;1479</code> ![](https://img.shields.io/github/last-commit/tricksterproxy/trickster) [Trickster](https://github.com/tricksterproxy/trickster) - HTTP reverse proxy cache and time series accelerator.
* <code>&nbsp;&nbsp;1454</code> ![](https://img.shields.io/github/last-commit/Bilibili/discovery) [discovery](https://github.com/Bilibili/discovery) - A registry for resilient mid-tier load balancing and failover.
* <code>&nbsp;&nbsp;1113</code> ![](https://img.shields.io/github/last-commit/ortuman/jackal) [jackal](https://github.com/ortuman/jackal) - An XMPP server written in Go.
* <code>&nbsp;&nbsp;&nbsp;352</code> ![](https://img.shields.io/github/last-commit/thomaspoignant/go-feature-flag) [go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) - A feature flag solution, with only a YAML file in the backend (S3, GitHub, HTTP, local file ...), no server to install, just add a file in a central system and refer to it.
* <code>&nbsp;&nbsp;&nbsp;129</code> ![](https://img.shields.io/github/last-commit/krotik/dudeldu) [dudeldu](https://github.com/krotik/dudeldu) - A simple SHOUTcast server.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;56</code> ![](https://img.shields.io/github/last-commit/rekby/lets-proxy2) [lets-proxy2](https://github.com/rekby/lets-proxy2) - Reverse proxy for handle https with issue certificates in fly from lets-encrypt.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> ![](https://img.shields.io/github/last-commit/blind-oracle/psql-streamer) [psql-streamer](https://github.com/blind-oracle/psql-streamer) - Stream database events from PostgreSQL to Kafka.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/blind-oracle/nginx-prometheus) [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) - Nginx log parser and exporter to Prometheus.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> ![](https://img.shields.io/github/last-commit/leberKleber/simple-jwt-provider) [simple-jwt-provider](https://github.com/leberKleber/simple-jwt-provider) - Simple and lightweight provider which exhibits JWTs, supports login, password-reset (via mail) and user management.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/blind-oracle/cortex-tenant) [cortex-tenant](https://github.com/blind-oracle/cortex-tenant) - Prometheus remote write proxy that adds add Cortex tenant ID header based on metric labels.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> ![](https://img.shields.io/github/last-commit/camgraff/protoxy) [protoxy](https://github.com/camgraff/protoxy) - A proxy server that converts JSON request bodies to Protocol Buffers.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> ![](https://img.shields.io/github/last-commit/fabiocicerchia/go-proxy-cache) [go-proxy-cache](https://github.com/fabiocicerchia/go-proxy-cache) - Simple Reverse Proxy with Caching, written in Go, using Redis.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code> ![](https://img.shields.io/github/last-commit/blind-oracle/riemann-relay) [riemann-relay](https://github.com/blind-oracle/riemann-relay) - Relay to load-balance Riemann events and/or convert them to Carbon.
* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [nsq](http://nsq.io/) - A realtime distributed messaging platform.

## Stream Processing

*Libraries and tools for stream processing and reactive programming.*

* <code>&nbsp;&nbsp;&nbsp;690</code> ![](https://img.shields.io/github/last-commit/reugn/go-streams) [go-streams](https://github.com/reugn/go-streams) - Go stream processing library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;92</code> ![](https://img.shields.io/github/last-commit/whitaker-io/machine) [machine](https://github.com/whitaker-io/machine) - Go library for writing and generating stream workers with built in metrics and traceability.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> ![](https://img.shields.io/github/last-commit/youthlin/stream) [stream](https://github.com/youthlin/stream) - Go Stream, like Java 8 Stream: Filter/Map/FlatMap/Peek/Sorted/ForEach/Reduce...

## Template Engines

*Libraries and tools for templating and lexing.*

* <code>&nbsp;&nbsp;3830</code> ![](https://img.shields.io/github/last-commit/jung-kurt/gofpdf) [gofpdf](https://github.com/jung-kurt/gofpdf) - PDF document generator with high level support for text, drawing and images.
* <code>&nbsp;&nbsp;2456</code> ![](https://img.shields.io/github/last-commit/Masterminds/sprig) [sprig](https://github.com/Masterminds/sprig) - Useful template functions for Go templates.
* <code>&nbsp;&nbsp;2159</code> ![](https://img.shields.io/github/last-commit/valyala/quicktemplate) [quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.
* <code>&nbsp;&nbsp;2013</code> ![](https://img.shields.io/github/last-commit/flosch/pongo2) [pongo2](https://github.com/flosch/pongo2) - Django-like template-engine for Go.
* <code>&nbsp;&nbsp;1467</code> ![](https://img.shields.io/github/last-commit/shiyanhui/hero) [hero](https://github.com/shiyanhui/hero) - Hero is a handy, fast and powerful go template engine.
* <code>&nbsp;&nbsp;1016</code> ![](https://img.shields.io/github/last-commit/hoisie/mustache) [mustache](https://github.com/hoisie/mustache) - Go implementation of the Mustache template language.
* <code>&nbsp;&nbsp;&nbsp;878</code> ![](https://img.shields.io/github/last-commit/eknkc/amber) [amber](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade.
* <code>&nbsp;&nbsp;&nbsp;809</code> ![](https://img.shields.io/github/last-commit/CloudyKit/jet) [jet](https://github.com/CloudyKit/jet) - Jet template engine.
* <code>&nbsp;&nbsp;&nbsp;802</code> ![](https://img.shields.io/github/last-commit/yosssi/ace) [ace](https://github.com/yosssi/ace) - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold.
* <code>&nbsp;&nbsp;&nbsp;785</code> ![](https://img.shields.io/github/last-commit/sipin/gorazor) [Razor](https://github.com/sipin/gorazor) - Razor view engine for Golang.
* <code>&nbsp;&nbsp;&nbsp;522</code> ![](https://img.shields.io/github/last-commit/valyala/fasttemplate) [fasttemplate](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/).
* <code>&nbsp;&nbsp;&nbsp;495</code> ![](https://img.shields.io/github/last-commit/benbjohnson/ego) [ego](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled.
* <code>&nbsp;&nbsp;&nbsp;435</code> ![](https://img.shields.io/github/last-commit/aymerick/raymond) [raymond](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go.
* <code>&nbsp;&nbsp;&nbsp;417</code> ![](https://img.shields.io/github/last-commit/johnfercher/maroto) [maroto](https://github.com/johnfercher/maroto) - A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple.
* <code>&nbsp;&nbsp;&nbsp;240</code> ![](https://img.shields.io/github/last-commit/foolin/goview) [goview](https://github.com/foolin/goview) - Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application.
* <code>&nbsp;&nbsp;&nbsp;155</code> ![](https://img.shields.io/github/last-commit/robfig/soy) [Soy](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/).
* <code>&nbsp;&nbsp;&nbsp;130</code> ![](https://img.shields.io/github/last-commit/osteele/liquid) [liquid](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;72</code> ![](https://img.shields.io/github/last-commit/ziutek/kasia.go) [kasia.go](https://github.com/ziutek/kasia.go) - Templating system for HTML and other text documents - go implementation.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;72</code> ![](https://img.shields.io/github/last-commit/gobuffalo/velvet) [velvet](https://github.com/gobuffalo/velvet) - Complete handlebars implementation in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> ![](https://img.shields.io/github/last-commit/dannyvankooten/extemplate) [extemplate](https://github.com/dannyvankooten/extemplate) - Tiny wrapper around html/template to allow for easy file-based template inheritance.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> ![](https://img.shields.io/github/last-commit/m1/gospin) [gospin](https://github.com/m1/gospin) - Article spinning and spintax/spinning syntax engine, useful for A/B, testing pieces of text/articles and creating more natural conversations.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/dskinner/damsel) [damsel](https://github.com/dskinner/damsel) - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others.

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
  * <code>&nbsp;13936</code> ![](https://img.shields.io/github/last-commit/stretchr/testify) [Testify](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package.
  * <code>&nbsp;&nbsp;6548</code> ![](https://img.shields.io/github/last-commit/smartystreets/goconvey) [GoConvey](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload.
  * <code>&nbsp;&nbsp;2417</code> ![](https://img.shields.io/github/last-commit/google/go-cmp) [go-cmp](https://github.com/google/go-cmp) - Package for comparing Go values in tests.
  * <code>&nbsp;&nbsp;1741</code> ![](https://img.shields.io/github/last-commit/gavv/httpexpect) [httpexpect](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing.
  * <code>&nbsp;&nbsp;1419</code> ![](https://img.shields.io/github/last-commit/DATA-DOG/godog) [godog](https://github.com/DATA-DOG/godog) - Cucumber or Behat like BDD framework for Go.
  * <code>&nbsp;&nbsp;&nbsp;807</code> ![](https://img.shields.io/github/last-commit/franela/goblin) [goblin](https://github.com/franela/goblin) - Mocha like testing framework fo Go.
  * <code>&nbsp;&nbsp;&nbsp;754</code> ![](https://img.shields.io/github/last-commit/dnaeon/go-vcr) [go-vcr](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests.
  * <code>&nbsp;&nbsp;&nbsp;712</code> ![](https://img.shields.io/github/last-commit/h2non/baloo) [baloo](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy.
  * <code>&nbsp;&nbsp;&nbsp;684</code> ![](https://img.shields.io/github/last-commit/go-testfixtures/testfixtures) [testfixtures](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications.
  * <code>&nbsp;&nbsp;&nbsp;502</code> ![](https://img.shields.io/github/last-commit/orlangure/gnomock) [gnomock](https://github.com/orlangure/gnomock) - integration testing with real dependencies (database, cache, even Kubernetes or AWS) running in Docker, without mocks.
  * <code>&nbsp;&nbsp;&nbsp;408</code> ![](https://img.shields.io/github/last-commit/zimmski/go-mutesting) [go-mutesting](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code.
  * <code>&nbsp;&nbsp;&nbsp;399</code> ![](https://img.shields.io/github/last-commit/qiniu/goc) [goc](https://github.com/qiniu/goc) - Goc is a comprehensive coverage testing system for The Go Programming Language.
  * <code>&nbsp;&nbsp;&nbsp;383</code> ![](https://img.shields.io/github/last-commit/appleboy/gofight) [gofight](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework.
  * <code>&nbsp;&nbsp;&nbsp;272</code> ![](https://img.shields.io/github/last-commit/fergusstrange/embedded-postgres) [embedded-postgres](https://github.com/fergusstrange/embedded-postgres) - Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test.
  * <code>&nbsp;&nbsp;&nbsp;265</code> ![](https://img.shields.io/github/last-commit/verdverm/frisby) [frisby](https://github.com/verdverm/frisby) - REST API testing framework.
  * <code>&nbsp;&nbsp;&nbsp;250</code> ![](https://img.shields.io/github/last-commit/gotestyourself/gotest.tools) [gotest.tools](https://github.com/gotestyourself/gotest.tools) - A collection of packages to augment the go testing package and support common patterns.
  * <code>&nbsp;&nbsp;&nbsp;213</code> ![](https://img.shields.io/github/last-commit/msoap/go-carpet) [go-carpet](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal.
  * <code>&nbsp;&nbsp;&nbsp;197</code> ![](https://img.shields.io/github/last-commit/MarvinJWendt/testza) [testza](https://github.com/MarvinJWendt/testza) - Full-featured test framework with nice colorized output.
  * <code>&nbsp;&nbsp;&nbsp;194</code> ![](https://img.shields.io/github/last-commit/percolate/charlatan) [charlatan](https://github.com/percolate/charlatan) - Tool to generate fake interface implementations for tests.
  * <code>&nbsp;&nbsp;&nbsp;189</code> ![](https://img.shields.io/github/last-commit/viant/endly) [endly](https://github.com/viant/endly) - Declarative end to end functional testing.
  * <code>&nbsp;&nbsp;&nbsp;188</code> ![](https://img.shields.io/github/last-commit/maxatome/go-testdeep) [go-testdeep](https://github.com/maxatome/go-testdeep) - Extremely flexible golang deep comparison, extends the go testing package.
  * <code>&nbsp;&nbsp;&nbsp;187</code> ![](https://img.shields.io/github/last-commit/SimonBaeumer/commander) [commander](https://github.com/SimonBaeumer/commander) - Tool for testing cli applications on windows, linux and osx.
  * <code>&nbsp;&nbsp;&nbsp;167</code> ![](https://img.shields.io/github/last-commit/bradleyjkemp/cupaloy) [cupaloy](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework.
  * <code>&nbsp;&nbsp;&nbsp;130</code> ![](https://img.shields.io/github/last-commit/khaiql/dbcleaner) [dbcleaner](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby.
  * <code>&nbsp;&nbsp;&nbsp;114</code> ![](https://img.shields.io/github/last-commit/orfjackal/gospec) [GoSpec](https://github.com/orfjackal/gospec) - BDD-style testing framework for the Go programming language.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> ![](https://img.shields.io/github/last-commit/posener/wstest) [wstest](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;81</code> ![](https://img.shields.io/github/last-commit/corbym/gocrest) [gocrest](https://github.com/corbym/gocrest) - Composable hamcrest-like matchers for Go assertions.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;69</code> ![](https://img.shields.io/github/last-commit/adamluzsi/testcase) [testcase](https://github.com/adamluzsi/testcase) - Idiomatic testing framework for Behavior Driven Development.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> ![](https://img.shields.io/github/last-commit/kinbiko/jsonassert) [jsonassert](https://github.com/kinbiko/jsonassert) - Package for verifying that your JSON payloads are serialized correctly.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> ![](https://img.shields.io/github/last-commit/yookoala/restit) [restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> ![](https://img.shields.io/github/last-commit/stesla/gospecify) [gospecify](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;42</code> ![](https://img.shields.io/github/last-commit/Eun/go-hit) [go-hit](https://github.com/Eun/go-hit) - Hit is an http integration test framework written in golang.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> ![](https://img.shields.io/github/last-commit/jfilipczyk/gomatch) [gomatch](https://github.com/jfilipczyk/gomatch) - library created for testing JSON against patterns.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> ![](https://img.shields.io/github/last-commit/covergates/covergates) [covergates](https://github.com/covergates/covergates) - Self-hosted code coverage report review and management service.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> ![](https://img.shields.io/github/last-commit/viant/dsunit) [dsunit](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> ![](https://img.shields.io/github/last-commit/go-playground/assert) [assert](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> ![](https://img.shields.io/github/last-commit/rdrdr/hamcrest) [Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> ![](https://img.shields.io/github/last-commit/suzuki-shunsuke/flute) [flute](https://github.com/suzuki-shunsuke/flute) - HTTP client testing framework.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/jgroeneveld/schema) [schema](https://github.com/jgroeneveld/schema) - Quick and easy expression matching for JSON schemas used in requests and responses.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/fulldump/biff) [biff](https://github.com/fulldump/biff) - Bifurcation testing framework, BDD compatible.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/zhulongcheng/testsql) [testsql](https://github.com/zhulongcheng/testsql) - Generate test data from SQL files before testing and clear it after finished.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/corbym/gogiven) [gogiven](https://github.com/corbym/gogiven) - YATSPEC-like BDD testing framework for Go.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/pavlo/gosuite) [gosuite](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/cavaliercoder/badio) [badio](https://github.com/cavaliercoder/badio) - Extensions to Go's `testing/iotest` package.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/elgohr/stop-and-go) [stop-and-go](https://github.com/elgohr/stop-and-go) - Testing helper for concurrency.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/jgroeneveld/trial) [trial](https://github.com/jgroeneveld/trial) - Quick and easy extendable assertions without introducing much boilerplate.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/vcaesar/tt) [Tt](https://github.com/vcaesar/tt) - Simple and colorful test tools.
  * [ginkgo](http://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
  * [testmd](https://godoc.org/github.com/tvastar/test/cmd/testmd) - Convert markdown snippets into testable go code.
  * [gocheck](http://labix.org/gocheck) - More advanced testing framework alternative to gotest.
  * [apitest](https://apitest.dev) - Simple and extensible behavioural testing library for REST based services or HTTP handlers that supports mocking external http calls and rendering of sequence diagrams.
  * [gomega](http://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
* Mock
  * <code>&nbsp;&nbsp;5982</code> ![](https://img.shields.io/github/last-commit/golang/mock) [gomock](https://github.com/golang/mock) - Mocking framework for the Go programming language.
  * <code>&nbsp;&nbsp;3702</code> ![](https://img.shields.io/github/last-commit/DATA-DOG/go-sqlmock) [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions.
  * <code>&nbsp;&nbsp;1766</code> ![](https://img.shields.io/github/last-commit/SpectoLabs/hoverfly) [hoverfly](https://github.com/SpectoLabs/hoverfly) - HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI.
  * <code>&nbsp;&nbsp;1454</code> ![](https://img.shields.io/github/last-commit/h2non/gock) [gock](https://github.com/h2non/gock) - Versatile HTTP mocking made easy.
  * <code>&nbsp;&nbsp;1117</code> ![](https://img.shields.io/github/last-commit/jarcoal/httpmock) [httpmock](https://github.com/jarcoal/httpmock) - Easy mocking of HTTP responses from external resources.
  * <code>&nbsp;&nbsp;&nbsp;555</code> ![](https://img.shields.io/github/last-commit/maxbrunsfeld/counterfeiter) [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects.
  * <code>&nbsp;&nbsp;&nbsp;404</code> ![](https://img.shields.io/github/last-commit/gojuno/minimock) [minimock](https://github.com/gojuno/minimock) - Mock generator for Go interfaces.
  * <code>&nbsp;&nbsp;&nbsp;373</code> ![](https://img.shields.io/github/last-commit/DATA-DOG/go-txdb) [go-txdb](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;98</code> ![](https://img.shields.io/github/last-commit/seborama/govcr) [govcr](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;55</code> ![](https://img.shields.io/github/last-commit/cabify/timex) [timex](https://github.com/cabify/timex) - A test-friendly replacement for the native `time` package.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> ![](https://img.shields.io/github/last-commit/tv42/mockhttp) [mockhttp](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/elgohr/go-localstack) [go-localstack](https://github.com/elgohr/go-localstack) - Tool for using localstack in AWS testing.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> ![](https://img.shields.io/github/last-commit/pasdam/mockit) [mockit](https://github.com/pasdam/mockit) - Allows functions and method easy mocking, without defining new types; it's similar to Mockito for Java.
* Fuzzing and delta-debugging/reducing/shrinking.
  * <code>&nbsp;&nbsp;4095</code> ![](https://img.shields.io/github/last-commit/dvyukov/go-fuzz) [go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing system.
  * <code>&nbsp;&nbsp;1103</code> ![](https://img.shields.io/github/last-commit/google/gofuzz) [gofuzz](https://github.com/google/gofuzz) - Library for populating go objects with random values.
  * <code>&nbsp;&nbsp;&nbsp;232</code> ![](https://img.shields.io/github/last-commit/zimmski/tavor) [Tavor](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework.
* Selenium and browser control tools.
  * <code>&nbsp;&nbsp;6581</code> ![](https://img.shields.io/github/last-commit/knq/chromedp) [chromedp](https://github.com/knq/chromedp) - a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol.
  * <code>&nbsp;&nbsp;1959</code> ![](https://img.shields.io/github/last-commit/aerokube/selenoid) [selenoid](https://github.com/aerokube/selenoid) - alternative Selenium hub server that launches browsers within containers.
  * <code>&nbsp;&nbsp;1696</code> ![](https://img.shields.io/github/last-commit/go-rod/rod) [rod](https://github.com/go-rod/rod) - A Devtools driver to make web automation and scraping easy.
  * <code>&nbsp;&nbsp;&nbsp;565</code> ![](https://img.shields.io/github/last-commit/mafredri/cdp) [cdp](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it.
  * <code>&nbsp;&nbsp;&nbsp;450</code> ![](https://img.shields.io/github/last-commit/mxschmitt/playwright-go) [playwright-go](https://github.com/mxschmitt/playwright-go) - browser automation library to control Chromium, Firefox and WebKit with a single API.
  * <code>&nbsp;&nbsp;&nbsp;272</code> ![](https://img.shields.io/github/last-commit/aerokube/ggr) [ggr](https://github.com/aerokube/ggr) - a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs.
* Fail injection
  * <code>&nbsp;&nbsp;&nbsp;599</code> ![](https://img.shields.io/github/last-commit/pingcap/failpoint) [failpoint](https://github.com/pingcap/failpoint) - An implementation of [failpoints](http://www.freebsd.org/cgi/man.cgi?query=fail) for Golang.

## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats
  * <code>&nbsp;14524</code> ![](https://img.shields.io/github/last-commit/asciimoo/colly) [colly](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers.
  * <code>&nbsp;10453</code> ![](https://img.shields.io/github/last-commit/PuerkitoBio/goquery) [GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.
  * <code>&nbsp;&nbsp;4765</code> ![](https://img.shields.io/github/last-commit/russross/blackfriday) [blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go.
  * <code>&nbsp;&nbsp;3898</code> ![](https://img.shields.io/github/last-commit/mvdan/sh) [sh](https://github.com/mvdan/sh) - Shell parser and formatter.
  * <code>&nbsp;&nbsp;3544</code> ![](https://img.shields.io/github/last-commit/BurntSushi/toml) [toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection).
  * <code>&nbsp;&nbsp;2756</code> ![](https://img.shields.io/github/last-commit/dustin/go-humanize) [go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format.
  * <code>&nbsp;&nbsp;2009</code> ![](https://img.shields.io/github/last-commit/microcosm-cc/bluemonday) [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer.
  * <code>&nbsp;&nbsp;1685</code> ![](https://img.shields.io/github/last-commit/mmcdole/gofeed) [gofeed](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go.
  * <code>&nbsp;&nbsp;1336</code> ![](https://img.shields.io/github/last-commit/facebookgo/inject) [inject](https://github.com/facebookgo/inject) - Package inject provides a reflect based injector.
  * <code>&nbsp;&nbsp;1063</code> ![](https://img.shields.io/github/last-commit/pelletier/go-toml) [go-toml](https://github.com/pelletier/go-toml) - Go library for the TOML format with query support and handy cli tools.
  * <code>&nbsp;&nbsp;&nbsp;780</code> ![](https://img.shields.io/github/last-commit/mingrammer/commonregex) [commonregex](https://github.com/mingrammer/commonregex) - A collection of common regular expressions for Go.
  * <code>&nbsp;&nbsp;&nbsp;659</code> ![](https://img.shields.io/github/last-commit/gosimple/slug) [slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support.
  * <code>&nbsp;&nbsp;&nbsp;476</code> ![](https://img.shields.io/github/last-commit/clbanning/mxj) [mxj](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.
  * <code>&nbsp;&nbsp;&nbsp;474</code> ![](https://img.shields.io/github/last-commit/slotix/dataflowkit) [dataflowkit](https://github.com/slotix/dataflowkit) - Web scraping Framework to turn websites into structured data.
  * <code>&nbsp;&nbsp;&nbsp;441</code> ![](https://img.shields.io/github/last-commit/awalterschulze/gographviz) [gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language.
  * <code>&nbsp;&nbsp;&nbsp;403</code> ![](https://img.shields.io/github/last-commit/labstack/gommon) [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - Format bytes to string.
  * <code>&nbsp;&nbsp;&nbsp;387</code> ![](https://img.shields.io/github/last-commit/antchfx/htmlquery) [htmlquery](https://github.com/antchfx/htmlquery) - An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression.
  * <code>&nbsp;&nbsp;&nbsp;375</code> ![](https://img.shields.io/github/last-commit/mattn/go-runewidth) [go-runewidth](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string.
  * <code>&nbsp;&nbsp;&nbsp;362</code> ![](https://img.shields.io/github/last-commit/jf-tech/omniparser) [omniparser](https://github.com/jf-tech/omniparser) - A versatile ETL library that parses text input (CSV/txt/JSON/XML/EDI/X12/EDIFACT/etc) in streaming fashion and transforms data into JSON output using data-driven schema.
  * <code>&nbsp;&nbsp;&nbsp;303</code> ![](https://img.shields.io/github/last-commit/leonelquinteros/gotext) [gotext](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go.
  * <code>&nbsp;&nbsp;&nbsp;234</code> ![](https://img.shields.io/github/last-commit/JohannesKaufmann/html-to-markdown) [html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) - Convert HTML to Markdown. Even works with entire websites and can be extended through rules.
  * <code>&nbsp;&nbsp;&nbsp;198</code> ![](https://img.shields.io/github/last-commit/andrewstuart/goq) [goq](https://github.com/andrewstuart/goq) - Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery).
  * <code>&nbsp;&nbsp;&nbsp;196</code> ![](https://img.shields.io/github/last-commit/zhshch2002/goribot) [goribot](https://github.com/zhshch2002/goribot) - A simple golang spider/scraping framework,build a spider in 3 lines.
  * <code>&nbsp;&nbsp;&nbsp;153</code> ![](https://img.shields.io/github/last-commit/adrianmo/go-nmea) [go-nmea](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language.
  * <code>&nbsp;&nbsp;&nbsp;111</code> ![](https://img.shields.io/github/last-commit/gortc/sdp) [sdp](https://github.com/gortc/sdp) - SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)].
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;95</code> ![](https://img.shields.io/github/last-commit/trubitsyn/go-zero-width) [go-zero-width](https://github.com/trubitsyn/go-zero-width) - Zero-width character detection and removal for Go.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;94</code> ![](https://img.shields.io/github/last-commit/eduncan911/podcast) [podcast](https://github.com/eduncan911/podcast) - iTunes Compliant and RSS 2.0 Podcast Generator in Golang
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;86</code> ![](https://img.shields.io/github/last-commit/editorconfig/editorconfig-core-go) [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;70</code> ![](https://img.shields.io/github/last-commit/Guitarbum722/align) [align](https://github.com/Guitarbum722/align) - A general purpose application that aligns text.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> ![](https://img.shields.io/github/last-commit/mozillazg/go-slugify) [go-slugify](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;60</code> ![](https://img.shields.io/github/last-commit/alixaxel/genex) [genex](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> ![](https://img.shields.io/github/last-commit/emersion/go-vcard) [go-vcard](https://github.com/emersion/go-vcard) - Parse and format vCard.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;58</code> ![](https://img.shields.io/github/last-commit/zach-klippenstein/goregen) [goregen](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> ![](https://img.shields.io/github/last-commit/ianlopshire/go-fixedwidth) [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) - Fixed-width text formatting (encoder/decoder with reflection).
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> ![](https://img.shields.io/github/last-commit/endeveit/guesslanguage) [guesslanguage](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;52</code> ![](https://img.shields.io/github/last-commit/ockam-network/did) [did](https://github.com/ockam-network/did) - DID (Decentralized Identifiers) Parser and Stringer in Go.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> ![](https://img.shields.io/github/last-commit/sbstjn/allot) [allot](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> ![](https://img.shields.io/github/last-commit/foolin/pagser) [pagser](https://github.com/foolin/pagser) - Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/polera/gonameparts) [gonameparts](https://github.com/polera/gonameparts) - Parses human names into individual name parts.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> ![](https://img.shields.io/github/last-commit/avelino/slugify) [Slugify](https://github.com/avelino/slugify) - Go slugify application that handles string.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> ![](https://img.shields.io/github/last-commit/avito-tech/normalize) [normalize](https://github.com/avito-tech/normalize) - Sanitize, normalize and compare fuzzy text.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/aerogo/codetree) [codetree](https://github.com/aerogo/codetree) - Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/endeveit/enca) [enca](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](http://cihar.com/software/enca/).
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/zhengchun/syndfeed) [syndfeed](https://github.com/zhengchun/syndfeed) - A syndication feed for Atom 1.0 and RSS 2.0.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/CalebQ42/bbConvert) [bbConvert](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/hscells/doi) [doi](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/Wing924/ltsv) [ltsv](https://github.com/Wing924/ltsv) - High performance [LTSV (Labeled Tab Separated Value)](http://ltsv.org/) reader for Go.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/mickep76/encdec) [encdec](https://github.com/mickep76/encdec) - Package provides a generic interface to encoders and decodersa.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> ![](https://img.shields.io/github/last-commit/IGLOU-EU/go-wildcard) [go-wildcard](https://github.com/IGLOU-EU/go-wildcard) - Simple and lightweight wildcard pattern matching.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code> ![](https://img.shields.io/github/last-commit/drewstinnett/go-output-format) [go-output-format](https://github.com/drewstinnett/go-output-format) - Output go structures into multiple formats (YAML/JSON/etc) in your command line app.
  * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.
* Utility
  * <code>&nbsp;&nbsp;&nbsp;815</code> ![](https://img.shields.io/github/last-commit/mvdan/xurls) [xurls](https://github.com/mvdan/xurls) - Extract urls from text.
  * <code>&nbsp;&nbsp;&nbsp;267</code> ![](https://img.shields.io/github/last-commit/bndr/gotabulate) [gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go.
  * <code>&nbsp;&nbsp;&nbsp;173</code> ![](https://img.shields.io/github/last-commit/yourbasic/radix) [radix](https://github.com/yourbasic/radix) - fast string sorting algorithm.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;89</code> ![](https://img.shields.io/github/last-commit/oriser/regroup) [regroup](https://github.com/oriser/regroup) - Match regex expression named groups into go struct using struct tags and automatic parsing.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> ![](https://img.shields.io/github/last-commit/codemodus/parth) [parth](https://github.com/codemodus/parth) - URL path segmentation parsing.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> ![](https://img.shields.io/github/last-commit/JoshuaDoes/gofuckyourself) [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) - A sanitization-based swear filter for Go.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> ![](https://img.shields.io/github/last-commit/stackerzzq/xj2go) [xj2go](https://github.com/stackerzzq/xj2go) - Convert xml or json to go struct.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/codemodus/kace) [kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/zoomio/tagify) [Tagify](https://github.com/zoomio/tagify) - Produces a set of tags from given source.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/Dynom/TySug) [TySug](https://github.com/Dynom/TySug) - Alternative suggestions with respect to keyboard layouts.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> ![](https://img.shields.io/github/last-commit/nproc/parseargs-go) [parseargs-go](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes.
  * <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> ![](https://img.shields.io/github/last-commit/isbm/textwrap) [textwrap](https://github.com/isbm/textwrap) - Implementation of `textwrap` module from Python.

## Third-party APIs

*Libraries for accessing third party APIs.*

* <code>&nbsp;&nbsp;7644</code> ![](https://img.shields.io/github/last-commit/google/go-github) [github](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3.
* <code>&nbsp;&nbsp;7044</code> ![](https://img.shields.io/github/last-commit/aws/aws-sdk-go) [aws-sdk-go](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language.
* <code>&nbsp;&nbsp;3597</code> ![](https://img.shields.io/github/last-commit/slack-go/slack) [slack](https://github.com/slack-go/slack) - Slack API in Go.
* <code>&nbsp;&nbsp;2729</code> ![](https://img.shields.io/github/last-commit/google/google-api-go-client) [google](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go.
* <code>&nbsp;&nbsp;2608</code> ![](https://img.shields.io/github/last-commit/GoogleCloudPlatform/gcloud-golang) [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library.
* <code>&nbsp;&nbsp;2218</code> ![](https://img.shields.io/github/last-commit/bwmarrin/discordgo) [discordgo](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API.
* <code>&nbsp;&nbsp;1398</code> ![](https://img.shields.io/github/last-commit/stripe/stripe-go) [stripe](https://github.com/stripe/stripe-go) - Go client for the Stripe API.
* <code>&nbsp;&nbsp;1350</code> ![](https://img.shields.io/github/last-commit/minio/minio-go) [minio-go](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage.
* <code>&nbsp;&nbsp;1285</code> ![](https://img.shields.io/github/last-commit/dghubble/go-twitter) [go-twitter](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs.
* <code>&nbsp;&nbsp;1100</code> ![](https://img.shields.io/github/last-commit/ChimeraCoder/anaconda) [anaconda](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API.
* <code>&nbsp;&nbsp;&nbsp;988</code> ![](https://img.shields.io/github/last-commit/huandu/facebook) [facebook](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API.
* <code>&nbsp;&nbsp;&nbsp;940</code> ![](https://img.shields.io/github/last-commit/andygrunwald/go-jira) [go-jira](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira)
* <code>&nbsp;&nbsp;&nbsp;792</code> ![](https://img.shields.io/github/last-commit/shurcooL/githubql) [githubql](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4.
* <code>&nbsp;&nbsp;&nbsp;640</code> ![](https://img.shields.io/github/last-commit/go-playground/webhooks) [webhooks](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket.
* <code>&nbsp;&nbsp;&nbsp;436</code> ![](https://img.shields.io/github/last-commit/logpacker/PayPal-Go-SDK) [paypal](https://github.com/logpacker/PayPal-Go-SDK) - Wrapper for PayPal payment API.
* <code>&nbsp;&nbsp;&nbsp;407</code> ![](https://img.shields.io/github/last-commit/codingsince1985/geo-golang) [geo-golang](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](https://opencagedata.com/api), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs.
* <code>&nbsp;&nbsp;&nbsp;212</code> ![](https://img.shields.io/github/last-commit/onrik/ethrpc) [ethrpc](https://github.com/onrik/ethrpc) - Go bindings for Ethereum JSON RPC API.
* <code>&nbsp;&nbsp;&nbsp;196</code> ![](https://img.shields.io/github/last-commit/gambol99/go-marathon) [go-marathon](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS.
* <code>&nbsp;&nbsp;&nbsp;180</code> ![](https://img.shields.io/github/last-commit/adlio/trello) [Trello](https://github.com/adlio/trello) - Go wrapper for the Trello API.
* <code>&nbsp;&nbsp;&nbsp;130</code> ![](https://img.shields.io/github/last-commit/Medium/medium-sdk-go) [Medium](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API.
* <code>&nbsp;&nbsp;&nbsp;130</code> ![](https://img.shields.io/github/last-commit/n0madic/twitter-scraper) [twitter-scraper](https://github.com/n0madic/twitter-scraper) - Scrape the Twitter Frontend API without authentication and limits.
* <code>&nbsp;&nbsp;&nbsp;127</code> ![](https://img.shields.io/github/last-commit/jsgilmore/gostorm) [gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.
* <code>&nbsp;&nbsp;&nbsp;116</code> ![](https://img.shields.io/github/last-commit/andygrunwald/go-trending) [go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github.
* <code>&nbsp;&nbsp;&nbsp;111</code> ![](https://img.shields.io/github/last-commit/daneharrigan/hipchat) [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP.
* <code>&nbsp;&nbsp;&nbsp;108</code> ![](https://img.shields.io/github/last-commit/wit-ai/wit-go) [wit-go](https://github.com/wit-ai/wit-go) - Go client for wit.ai HTTP API.
* <code>&nbsp;&nbsp;&nbsp;105</code> ![](https://img.shields.io/github/last-commit/andybons/hipchat) [hipchat](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API.
* <code>&nbsp;&nbsp;&nbsp;102</code> ![](https://img.shields.io/github/last-commit/gregdel/pushover) [pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;88</code> ![](https://img.shields.io/github/last-commit/andygrunwald/cachet) [cachet](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;68</code> ![](https://img.shields.io/github/last-commit/Henry-Sarabia/igdb) [igdb](https://github.com/Henry-Sarabia/igdb) - Go client for the [Internet Game Database API](https://api.igdb.com/).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;62</code> ![](https://img.shields.io/github/last-commit/koltyakov/gosip) [gosip](https://github.com/koltyakov/gosip) - Go client library SharePoint API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> ![](https://img.shields.io/github/last-commit/jszwedko/go-circleci) [circleci](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> ![](https://img.shields.io/github/last-commit/rhnvrm/simples3) [simples3](https://github.com/rhnvrm/simples3) - Simple no frills AWS S3 Library using REST with V4 Signing written in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;55</code> ![](https://img.shields.io/github/last-commit/hbagdi/go-unsplash) [go-unsplash](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;55</code> ![](https://img.shields.io/github/last-commit/samuelcouch/clarifai) [clarifai](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;55</code> ![](https://img.shields.io/github/last-commit/groovili/gogtrends) [gogtrends](https://github.com/groovili/gogtrends) - Google Trends Unofficial API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> ![](https://img.shields.io/github/last-commit/andygrunwald/megos) [megos](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> ![](https://img.shields.io/github/last-commit/ngs/go-amazon-product-advertising-api) [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) - Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> ![](https://img.shields.io/github/last-commit/emiddleton/gads) [gads](https://github.com/emiddleton/gads) - Google Adwords Unofficial API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> ![](https://img.shields.io/github/last-commit/brunomvsouza/ynab.go) [ynab](https://github.com/brunomvsouza/ynab.go) - Go wrapper for the YNAB API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;46</code> ![](https://img.shields.io/github/last-commit/bitfield/uptimerobot) [uptimerobot](https://github.com/bitfield/uptimerobot) - Go wrapper and command-line client for the Uptime Robot v2 API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> ![](https://img.shields.io/github/last-commit/nishanths/go-xkcd) [go-xkcd](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;43</code> ![](https://img.shields.io/github/last-commit/michiwend/gomusicbrainz) [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;43</code> ![](https://img.shields.io/github/last-commit/cyruzin/golang-tmdb) [golang-tmdb](https://github.com/cyruzin/golang-tmdb) - Golang wrapper for The Movie Database API v3.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> ![](https://img.shields.io/github/last-commit/maddevsio/fcm) [fcm](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> ![](https://img.shields.io/github/last-commit/dukex/mixpanel) [mixpanel](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> ![](https://img.shields.io/github/last-commit/rapito/go-spotify) [spotify](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> ![](https://img.shields.io/github/last-commit/mamal72/golyrics) [golyrics](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> ![](https://img.shields.io/github/last-commit/poorny/translate) [translate](https://github.com/poorny/translate) - Go online translation package.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> ![](https://img.shields.io/github/last-commit/bit4bit/gami) [gami](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> ![](https://img.shields.io/github/last-commit/rbretecher/go-postman-collection) [go-postman-collection](https://github.com/rbretecher/go-postman-collection) - Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) (compatible with Insomnia).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> ![](https://img.shields.io/github/last-commit/Aorioli/gcm) [gcm](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> ![](https://img.shields.io/github/last-commit/mxpv/patreon-go) [patreon-go](https://github.com/mxpv/patreon-go) - Go library for Patreon API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> ![](https://img.shields.io/github/last-commit/mehanizm/airtable) [airtable](https://github.com/mehanizm/airtable) - Go client library for the [Airtable API](https://airtable.com/api).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/nstratos/go-myanimelist) [go-myanimelist](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](https://myanimelist.net/apiconfig/references/api/v2).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/sostronk/go-steam) [steam](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> ![](https://img.shields.io/github/last-commit/ansd/lastpass-go) [lastpass-go](https://github.com/ansd/lastpass-go) - Go client library for the [LastPass](https://www.lastpass.com/) API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> ![](https://img.shields.io/github/last-commit/knspriggs/go-twitch) [go-twitch](https://github.com/knspriggs/go-twitch) - Go client for interacting with the Twitch v3 API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> ![](https://img.shields.io/github/last-commit/koffeinsource/go-imgur) [go-imgur](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com)
* <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> ![](https://img.shields.io/github/last-commit/rapito/go-shopify) [shopify](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/naegelejd/brewerydb) [brewerydb](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/codeship/codeship-go) [codeship-go](https://github.com/codeship/codeship-go) - Go client library for interacting with Codeship's API v2.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/dietsche/textbelt) [textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/n0madic/google-play-scraper) [google-play-scraper](https://github.com/n0madic/google-play-scraper) - Get data from Google Play Store.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> ![](https://img.shields.io/github/last-commit/PaulRosset/go-hacknews) [go-hacknews](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/coinpaprika/coinpaprika-api-go-client) [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) - Go client library for interacting with Coinpaprika's API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/circa10a/go-aws-news) [go-aws-news](https://github.com/circa10a/go-aws-news) - Go application and library to fetch what's new from AWS.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/chonthu/go-google-analytics) [google-analytics](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/rinchsan/device-check-go) [device-check-go](https://github.com/rinchsan/device-check-go) - Go client library for interacting with [iOS DeviceCheck API](https://developer.apple.com/documentation/devicecheck) v1.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/utekaravinash/gopaapi5) [gopaapi5](https://github.com/utekaravinash/gopaapi5) - Go Client Library for [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/sergiotapia/smitego) [smite](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/abdullahselek/go-here) [go-here](https://github.com/abdullahselek/go-here) - Go client library around the HERE location based APIs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/MonaxGT/gomalshare) [gomalshare](https://github.com/MonaxGT/gomalshare) - Go library MalShare API [malshare.com](http://www.malshare.com/)
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> ![](https://img.shields.io/github/last-commit/esurdam/go-sophos) [go-sophos](https://github.com/esurdam/go-sophos) - Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> ![](https://img.shields.io/github/last-commit/Omie/rrdaclient) [rrdaclient](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/ngs/go-google-email-audit-api) [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/manuelbcd/go-openproject) [go-openproject](https://github.com/manuelbcd/go-openproject) - Go client library for interacting with [OpenProject](https://docs.openproject.org/api/) API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/sergioaugrod/go-sptrans) [go-sptrans](https://github.com/sergioaugrod/go-sptrans) - Go client library for the SPTrans Olho Vivo API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/mattcunningham/gumblr) [tumblr](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/gojuno/go-zooz) [zooz](https://github.com/gojuno/go-zooz) - Go client for the Zooz API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/axelspringer/go-chronos) [go-chronos](https://github.com/axelspringer/go-chronos) - Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> ![](https://img.shields.io/github/last-commit/Henry-Sarabia/kanka) [kanka](https://github.com/Henry-Sarabia/kanka) - Go client for the [Kanka API](https://kanka.io/en-US/docs/1.0).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> ![](https://img.shields.io/github/last-commit/clevabit/libgoffi) [libgoffi](https://github.com/clevabit/libgoffi) - Library adapter toolbox for native [libffi](http://sourceware.org/libffi/) integration
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> ![](https://img.shields.io/github/last-commit/dimuska139/rawg-sdk-go) [rawg-sdk-go](https://github.com/dimuska139/rawg-sdk-go) - Go library for the [RAWG Video Games Database](https://rawg.io/) API
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> ![](https://img.shields.io/github/last-commit/Kachit/appstore-sdk-go) [appstore-sdk-go](https://github.com/Kachit/appstore-sdk-go) - Unofficial Golang SDK for AppStore Connect API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code> ![](https://img.shields.io/github/last-commit/verifid/vl-go) [vl-go](https://github.com/verifid/vl-go) - Go client library around the VerifID identity verification layer API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code> ![](https://img.shields.io/github/last-commit/playlyfe/playlyfe-go-sdk) [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code> ![](https://img.shields.io/github/last-commit/esurdam/go-swagger-ui) [go-swagger-ui](https://github.com/esurdam/go-swagger-ui) - Go library containing precompiled [Swagger UI](https://swagger.io/tools/swagger-ui/) for serving swagger json.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code> ![](https://img.shields.io/github/last-commit/mrbenosborne/tripadvisor-golang) [TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) - Go wrapper for the TripAdvisor API.
* [go-yapla](https://git.iglou.eu/Production/go-yapla) - Go client library for the Yapla v2.0 API.
* [go-telegraph](https://gitlab.com/toby3d/telegraph) - Telegraph publishing platform API client.

## Utilities

*General utilities and tools to make your life easier.*

* <code>&nbsp;38314</code> ![](https://img.shields.io/github/last-commit/junegunn/fzf) [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go.
* <code>&nbsp;21072</code> ![](https://img.shields.io/github/last-commit/github/hub) [hub](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal.
* <code>&nbsp;11806</code> ![](https://img.shields.io/github/last-commit/bcicen/ctop) [ctop](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics.
* <code>&nbsp;10579</code> ![](https://img.shields.io/github/last-commit/jmoiron/sqlx) [sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package.
* <code>&nbsp;&nbsp;9722</code> ![](https://img.shields.io/github/last-commit/asciimoo/wuzz) [wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection.
* <code>&nbsp;&nbsp;8413</code> ![](https://img.shields.io/github/last-commit/goreleaser/goreleaser) [goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible.
* <code>&nbsp;&nbsp;6624</code> ![](https://img.shields.io/github/last-commit/knq/usql) [usql](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases.
* <code>&nbsp;&nbsp;6467</code> ![](https://img.shields.io/github/last-commit/peco/peco) [peco](https://github.com/peco/peco) - Simplistic interactive filtering tool.
* <code>&nbsp;&nbsp;3958</code> ![](https://img.shields.io/github/last-commit/dropbox/godropbox) [godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox.
* <code>&nbsp;&nbsp;3281</code> ![](https://img.shields.io/github/last-commit/afex/hystrix-go) [hystrix-go](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker.
* <code>&nbsp;&nbsp;2896</code> ![](https://img.shields.io/github/last-commit/wgliang/goreporter) [goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report.
* <code>&nbsp;&nbsp;2790</code> ![](https://img.shields.io/github/last-commit/thoas/go-funk) [go-funk](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).
* <code>&nbsp;&nbsp;2733</code> ![](https://img.shields.io/github/last-commit/tdewolff/minify) [minify](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats.
* <code>&nbsp;&nbsp;2676</code> ![](https://img.shields.io/github/last-commit/maruel/panicparse) [panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump.
* <code>&nbsp;&nbsp;1865</code> ![](https://img.shields.io/github/last-commit/minio/mc) [mc](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.
* <code>&nbsp;&nbsp;1752</code> ![](https://img.shields.io/github/last-commit/asdine/storm) [Storm](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB.
* <code>&nbsp;&nbsp;1630</code> ![](https://img.shields.io/github/last-commit/imdario/mergo) [mergo](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.
* <code>&nbsp;&nbsp;1551</code> ![](https://img.shields.io/github/last-commit/briandowns/spinner) [spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options.
* <code>&nbsp;&nbsp;1488</code> ![](https://img.shields.io/github/last-commit/davrodpin/mole) [mole](https://github.com/davrodpin/mole) - cli app to easily create ssh tunnels.
* <code>&nbsp;&nbsp;1369</code> ![](https://img.shields.io/github/last-commit/tmrts/boilr) [boilr](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates.
* <code>&nbsp;&nbsp;1332</code> ![](https://img.shields.io/github/last-commit/h2non/filetype) [filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature.
* <code>&nbsp;&nbsp;1124</code> ![](https://img.shields.io/github/last-commit/gsamokovarov/jump) [jump](https://github.com/gsamokovarov/jump) - Jump helps you navigate faster by learning your habits.
* <code>&nbsp;&nbsp;&nbsp;954</code> ![](https://img.shields.io/github/last-commit/rubyist/circuitbreaker) [circuitbreaker](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go.
* <code>&nbsp;&nbsp;&nbsp;873</code> ![](https://img.shields.io/github/last-commit/git-time-metric/gtm) [git-time-metric](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git.
* <code>&nbsp;&nbsp;&nbsp;712</code> ![](https://img.shields.io/github/last-commit/immortal/immortal) [immortal](https://github.com/immortal/immortal) - \*nix cross-platform (OS agnostic) supervisor.
* <code>&nbsp;&nbsp;&nbsp;668</code> ![](https://img.shields.io/github/last-commit/guumaster/hostctl) [hostctl](https://github.com/guumaster/hostctl) - A CLI tool to manage /etc/hosts with easy commands.
* <code>&nbsp;&nbsp;&nbsp;582</code> ![](https://img.shields.io/github/last-commit/cep21/circuit) [circuit](https://github.com/cep21/circuit) - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern.
* <code>&nbsp;&nbsp;&nbsp;545</code> ![](https://img.shields.io/github/last-commit/gabriel-vasile/mimetype) [mimetype](https://github.com/gabriel-vasile/mimetype) - Package for MIME type detection based on magic numbers.
* <code>&nbsp;&nbsp;&nbsp;533</code> ![](https://img.shields.io/github/last-commit/htcat/htcat) [htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility.
* <code>&nbsp;&nbsp;&nbsp;520</code> ![](https://img.shields.io/github/last-commit/create-go-app/cli) [create-go-app](https://github.com/create-go-app/cli) - A powerful CLI for create a new production-ready project with backend (Golang), frontend (JavaScript, TypeScript) & deploy automation (Ansible, Docker) by running one command.
* <code>&nbsp;&nbsp;&nbsp;477</code> ![](https://img.shields.io/github/last-commit/VividCortex/godaemon) [godaemon](https://github.com/VividCortex/godaemon) - Utility to write daemons.
* <code>&nbsp;&nbsp;&nbsp;473</code> ![](https://img.shields.io/github/last-commit/cristianoliveira/ergo) [ergo](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy.
* <code>&nbsp;&nbsp;&nbsp;467</code> ![](https://img.shields.io/github/last-commit/wesovilabs/koazee) [koazee](https://github.com/wesovilabs/koazee) - Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays.
* <code>&nbsp;&nbsp;&nbsp;467</code> ![](https://img.shields.io/github/last-commit/ungerik/go-dry) [go-dry](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go.
* <code>&nbsp;&nbsp;&nbsp;436</code> ![](https://img.shields.io/github/last-commit/bndr/gopencils) [gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.
* <code>&nbsp;&nbsp;&nbsp;398</code> ![](https://img.shields.io/github/last-commit/mozillazg/request) [request](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™.
* <code>&nbsp;&nbsp;&nbsp;360</code> ![](https://img.shields.io/github/last-commit/novalagung/gubrak) [gubrak](https://github.com/novalagung/gubrak) - Golang utility library with syntactic sugar. It's like lodash, but for golang.
* <code>&nbsp;&nbsp;&nbsp;355</code> ![](https://img.shields.io/github/last-commit/derekparker/delve) [delve](https://github.com/derekparker/delve) - Go debugger.
* <code>&nbsp;&nbsp;&nbsp;354</code> ![](https://img.shields.io/github/last-commit/ulule/deepcopier) [Deepcopier](https://github.com/ulule/deepcopier) - Simple struct copying for Go.
* <code>&nbsp;&nbsp;&nbsp;343</code> ![](https://img.shields.io/github/last-commit/jonboulle/clockwork) [clockwork](https://github.com/jonboulle/clockwork) - A simple fake clock for golang.
* <code>&nbsp;&nbsp;&nbsp;339</code> ![](https://img.shields.io/github/last-commit/beefsack/go-rate) [go-rate](https://github.com/beefsack/go-rate) - Timed rate limiter for Go.
* <code>&nbsp;&nbsp;&nbsp;330</code> ![](https://img.shields.io/github/last-commit/georgysavva/scany) [scany](https://github.com/georgysavva/scany) - Library for scanning data from a database into Go structs and more.
* <code>&nbsp;&nbsp;&nbsp;309</code> ![](https://img.shields.io/github/last-commit/kamilsk/retry) [retry](https://github.com/kamilsk/retry) - The most advanced functional mechanism to perform actions repetitively until successful.
* <code>&nbsp;&nbsp;&nbsp;253</code> ![](https://img.shields.io/github/last-commit/cosiner/gohper) [gohper](https://github.com/cosiner/gohper) - Various tools/modules help for development.
* <code>&nbsp;&nbsp;&nbsp;245</code> ![](https://img.shields.io/github/last-commit/syntaqx/serve) [serve](https://github.com/syntaqx/serve) - A static http server anywhere you need.
* <code>&nbsp;&nbsp;&nbsp;222</code> ![](https://img.shields.io/github/last-commit/blockloop/scan) [scan](https://github.com/blockloop/scan) - Scan golang `sql.Rows` directly to structs, slices, or primitive types.
* <code>&nbsp;&nbsp;&nbsp;217</code> ![](https://img.shields.io/github/last-commit/sadlil/go-trigger) [go-trigger](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.
* <code>&nbsp;&nbsp;&nbsp;215</code> ![](https://img.shields.io/github/last-commit/shomali11/util) [util](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...).
* <code>&nbsp;&nbsp;&nbsp;204</code> ![](https://img.shields.io/github/last-commit/subosito/gotenv) [gotenv](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go.
* <code>&nbsp;&nbsp;&nbsp;172</code> ![](https://img.shields.io/github/last-commit/vrecan/death) [Death](https://github.com/vrecan/death) - Managing go application shutdown with signals.
* <code>&nbsp;&nbsp;&nbsp;169</code> ![](https://img.shields.io/github/last-commit/wendigo/go-bind-plugin) [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only).
* <code>&nbsp;&nbsp;&nbsp;162</code> ![](https://img.shields.io/github/last-commit/viant/toolbox) [toolbox](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer.
* <code>&nbsp;&nbsp;&nbsp;162</code> ![](https://img.shields.io/github/last-commit/ivpusic/rerun) [rerun](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes.
* <code>&nbsp;&nbsp;&nbsp;161</code> ![](https://img.shields.io/github/last-commit/StabbyCutyou/moldova) [moldova](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template.
* <code>&nbsp;&nbsp;&nbsp;158</code> ![](https://img.shields.io/github/last-commit/ikeikeikeike/go-sitemap-generator) [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go.
* <code>&nbsp;&nbsp;&nbsp;153</code> ![](https://img.shields.io/github/last-commit/topfreegames/apm) [apm](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API.
* <code>&nbsp;&nbsp;&nbsp;150</code> ![](https://img.shields.io/github/last-commit/VividCortex/robustly) [robustly](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics.
* <code>&nbsp;&nbsp;&nbsp;137</code> ![](https://img.shields.io/github/last-commit/antham/chyle) [chyle](https://github.com/antham/chyle) - Changelog generator using a git repository with multiple configuration possibilities.
* <code>&nbsp;&nbsp;&nbsp;120</code> ![](https://img.shields.io/github/last-commit/gabstv/go-bsdiff) [go-bsdiff](https://github.com/gabstv/go-bsdiff) - Pure Go bsdiff and bspatch libraries and CLI tools.
* <code>&nbsp;&nbsp;&nbsp;120</code> ![](https://img.shields.io/github/last-commit/adelowo/onecache) [onecache](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc).
* <code>&nbsp;&nbsp;&nbsp;119</code> ![](https://img.shields.io/github/last-commit/jaschaephraim/lrserver) [lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go.
* <code>&nbsp;&nbsp;&nbsp;107</code> ![](https://img.shields.io/github/last-commit/biter777/countries) [countries](https://github.com/biter777/countries) - Full implementation of ISO-3166-1, ISO-4217, ITU-T E.164, Unicode CLDR and IANA ccTLD standarts.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;90</code> ![](https://img.shields.io/github/last-commit/pokanop/nostromo) [nostromo](https://github.com/pokanop/nostromo) - CLI for building powerful aliases.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;87</code> ![](https://img.shields.io/github/last-commit/alexpantyukhin/go-pattern-match) [pattern-match](https://github.com/alexpantyukhin/go-pattern-match) - Pattern matching libray.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;87</code> ![](https://img.shields.io/github/last-commit/linxGnu/mssqlx) [mssqlx](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;87</code> ![](https://img.shields.io/github/last-commit/linxGnu/goseaweedfs) [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;87</code> ![](https://img.shields.io/github/last-commit/monmohan/xferspdy) [xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;86</code> ![](https://img.shields.io/github/last-commit/miniscruff/changie) [changie](https://github.com/miniscruff/changie) - Automated changelog tool for preparing releases with lots of customization options.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;81</code> ![](https://img.shields.io/github/last-commit/Talento90/go-health) [go-health](https://github.com/Talento90/go-health) - Health package simplifies the way you add health check to your services.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;81</code> ![](https://img.shields.io/github/last-commit/jfcg/sorty) [sorty](https://github.com/jfcg/sorty) - Fast Concurrent / Parallel Sorting.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;78</code> ![](https://img.shields.io/github/last-commit/VividCortex/pm) [pm](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;77</code> ![](https://img.shields.io/github/last-commit/ssgreg/repeat) [repeat](https://github.com/ssgreg/repeat) - Go implementation of different backoff strategies useful for retrying operations and heartbeating.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;69</code> ![](https://img.shields.io/github/last-commit/e-dard/netbug) [netbug](https://github.com/e-dard/netbug) - Easy remote profiling of your services.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;69</code> ![](https://img.shields.io/github/last-commit/gobeam/mongo-go-pagination) [mongo-go-pagination](https://github.com/gobeam/mongo-go-pagination) - Mongodb Pagination for official mongodb/mongo-go-driver package which supports both normal queries and Aggregation pipelines.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> ![](https://img.shields.io/github/last-commit/esemplastic/unis) [UNIS](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;65</code> ![](https://img.shields.io/github/last-commit/VividCortex/multitick) [multitick](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;64</code> ![](https://img.shields.io/github/last-commit/miguelpragier/handy) [handy](https://github.com/miguelpragier/handy) - Many utilities and helpers like string handlers/formatters and validators.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;64</code> ![](https://img.shields.io/github/last-commit/SimonBaeumer/cmd) [cmd](https://github.com/SimonBaeumer/cmd) - Library for executing shell commands on osx, windows and linux.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;62</code> ![](https://img.shields.io/github/last-commit/zRedShift/mimemagic) [mimemagic](https://github.com/zRedShift/mimemagic) - Pure Go ultra performant MIME sniffing library/utility.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> ![](https://img.shields.io/github/last-commit/icza/minquery) [minquery](https://github.com/icza/minquery) - MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;58</code> ![](https://img.shields.io/github/last-commit/philipjkim/goreadability) [goreadability](https://github.com/philipjkim/goreadability) - Webpage summary extractor using Facebook Open Graph and arc90's readability.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;57</code> ![](https://img.shields.io/github/last-commit/asticode/go-astitodo) [go-astitodo](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;57</code> ![](https://img.shields.io/github/last-commit/golang-design/clipboard) [clipboard](https://github.com/golang-design/clipboard) - 📋 cross-platform clipboard package in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;55</code> ![](https://img.shields.io/github/last-commit/mlimaloureiro/golog) [golog](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> ![](https://img.shields.io/github/last-commit/arthurkushman/pgo) [pgo](https://github.com/arthurkushman/pgo) - Convenient functions for PHP community.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;52</code> ![](https://img.shields.io/github/last-commit/maja42/goval) [goval](https://github.com/maja42/goval) - Evaluate arbitrary expressions in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> ![](https://img.shields.io/github/last-commit/jutkko/copy-pasta) [copy-pasta](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> ![](https://img.shields.io/github/last-commit/gookit/filter) [filter](https://github.com/gookit/filter) - provide filtering, sanitizing, and conversion of Go data.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> ![](https://img.shields.io/github/last-commit/thedevsaddam/retry) [retry](https://github.com/thedevsaddam/retry) - Simple and easy retry mechanism package for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;46</code> ![](https://img.shields.io/github/last-commit/wesovilabs/beyond) [beyond](https://github.com/wesovilabs/beyond) - The Go tool that will drive you to the AOP world!
* <code>&nbsp;&nbsp;&nbsp;&nbsp;46</code> ![](https://img.shields.io/github/last-commit/viney-shih/go-lock) [go-lock](https://github.com/viney-shih/go-lock) - go-lock is a lock library implementing read-write mutex and read-write trylock without starvation.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> ![](https://img.shields.io/github/last-commit/msempere/golarm) [golarm](https://github.com/msempere/golarm) - Fire alarms with system events.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;44</code> ![](https://img.shields.io/github/last-commit/carlescere/goback) [goback](https://github.com/carlescere/goback) - Go simple exponential backoff package.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;43</code> ![](https://img.shields.io/github/last-commit/psampaz/slice) [slice](https://github.com/psampaz/slice) - Type-safe functions for common Go slice operations.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;42</code> ![](https://img.shields.io/github/last-commit/mengzhuo/intrinsic) [intrinsic](https://github.com/mengzhuo/intrinsic) - Use x86 SIMD without writing any assembly code.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;42</code> ![](https://img.shields.io/github/last-commit/nikogura/dbt) [dbt](https://github.com/nikogura/dbt) - A framework for running self-updating signed binaries from a central, trusted repository.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> ![](https://img.shields.io/github/last-commit/rafaeljesus/retry-go) [retry-go](https://github.com/rafaeljesus/retry-go) - Retrying made simple and easy for golang.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> ![](https://img.shields.io/github/last-commit/tenntenn/gpath) [gpath](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> ![](https://img.shields.io/github/last-commit/mozillazg/go-httpheader) [go-httpheader](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/inancgumus/myhttp) [myhttp](https://github.com/inancgumus/myhttp) - Simple API to make HTTP GET requests with timeout support.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/mennanov/limiters) [limiters](https://github.com/mennanov/limiters) - Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;32</code> ![](https://img.shields.io/github/last-commit/ik5/gostrutils) [gostrutils](https://github.com/ik5/gostrutils) - Collections of string manipulation and conversion functions.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;32</code> ![](https://img.shields.io/github/last-commit/zpatrick/rclient) [rclient](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> ![](https://img.shields.io/github/last-commit/reugn/equalizer) [equalizer](https://github.com/reugn/equalizer) - Quota manager and rate limiter collection for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> ![](https://img.shields.io/github/last-commit/nullne/evaluator) [evaluator](https://github.com/nullne/evaluator) - Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/cyruzin/tome) [tome](https://github.com/cyruzin/tome) - Tome was designed to paginate simple RESTful APIs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> ![](https://img.shields.io/github/last-commit/alxrm/ugo) [ugo](https://github.com/alxrm/ugo) - ugo is slice toolbox with concise syntax for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/go-playground/generate) [generate](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/leaanthony/slicer) [slicer](https://github.com/leaanthony/slicer) - Makes working with slices easier.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> ![](https://img.shields.io/github/last-commit/icza/backscanner) [backscanner](https://github.com/icza/backscanner) - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> ![](https://img.shields.io/github/last-commit/michiwend/goplaceholder) [goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> ![](https://img.shields.io/github/last-commit/abo/rerate) [rerate](https://github.com/abo/rerate) - Redis-based rate counter and rate limiter for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> ![](https://img.shields.io/github/last-commit/ztrue/shutdown) [shutdown](https://github.com/ztrue/shutdown) - App shutdown hooks for `os.Signal` handling.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> ![](https://img.shields.io/github/last-commit/antham/ghokin) [ghokin](https://github.com/antham/ghokin) - Parallelized formatter with no external dependencies for gherkin (cucumber, behat...).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> ![](https://img.shields.io/github/last-commit/posener/ctxutil) [ctxutil](https://github.com/posener/ctxutil) - A collection of utility functions for contexts.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/PumpkinSeed/structs) [structs](https://github.com/PumpkinSeed/structs) - Implement simple functions to manipulate structs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> ![](https://img.shields.io/github/last-commit/yaronsumel/filler) [filler](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> ![](https://img.shields.io/github/last-commit/aofei/mimesniffer) [mimesniffer](https://github.com/aofei/mimesniffer) - A MIME type sniffer for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> ![](https://img.shields.io/github/last-commit/kirillDanshin/dlog) [dlog](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/xta/okrun) [okrun](https://github.com/xta/okrun) - go run error steamroller.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/clevergo/jsend) [jsend](https://github.com/clevergo/jsend) - JSend's implementation writen in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/txgruppi/command) [command](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> ![](https://img.shields.io/github/last-commit/edermanoel94/rest-go) [rest-go](https://github.com/edermanoel94/rest-go) - A package that provide many helpful methods for working with rest api.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/Eun/go-convert) [go-convert](https://github.com/Eun/go-convert) - Package go-convert enbles you to convert a value into another type.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/mikekonan/go-types) [go-type](https://github.com/mikekonan/go-types) - Library providing Go types for store/validation and transfer of ISO-4217, ISO-3166, and other types.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/shafreeck/retry) [retry](https://github.com/shafreeck/retry) - A pretty simple library to ensure your work to be done.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/gotidy/ptr) [ptr](https://github.com/gotidy/ptr) - Package that provide functions for simplified creation of pointers from constants of basic types.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/mvmaasakkers/go-problemdetails) [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) - Go package for working with Problem Details.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/chrispassas/silk) [silk](https://github.com/chrispassas/silk) - Read silk netflow files.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/mikekonan/go-countries) [go-countries](https://github.com/mikekonan/go-countries) - Lightweight lookup over ISO-3166 codes.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> ![](https://img.shields.io/github/last-commit/gotidy/copy) [copy](https://github.com/gotidy/copy) - Package for fast copying structs of different types.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/chrispassas/nfdump) [nfdump](https://github.com/chrispassas/nfdump) - Read nfdump netflow files.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/percolate/retry) [retry](https://github.com/percolate/retry) - A simple but highly configurable retry package for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/prashantgupta24/go-clip) [go-clip](https://github.com/prashantgupta24/go-clip) - A minimalistic clipboard manager for Mac.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/Henry-Sarabia/sliceconv) [sliceconv](https://github.com/Henry-Sarabia/sliceconv) - Slice conversion between primitive types.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/alajmo/mani) [mani](https://github.com/alajmo/mani) - CLI tool to help you manage multiple repositories.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/janiltonmaciel/statiks) [statiks](https://github.com/janiltonmaciel/statiks) - Fast, zero-configuration, static HTTP filer server.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/Henry-Sarabia/blank) [blank](https://github.com/Henry-Sarabia/blank) - Verify or remove blanks and whitespace from strings.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/kenkyu392/go-safe) [go-safe](https://github.com/kenkyu392/go-safe) - Panic-safe sandbox.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> ![](https://img.shields.io/github/last-commit/aplescia-chwy/lets-go) [lets-go](https://github.com/aplescia-chwy/lets-go) - Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> ![](https://img.shields.io/github/last-commit/andy2046/tik) [tik](https://github.com/andy2046/tik) - Simple and easy timing wheel package for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> ![](https://img.shields.io/github/last-commit/zerosnake0/goctx) [goctx](https://github.com/zerosnake0/goctx) - Get your context value with high performance.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> ![](https://img.shields.io/github/last-commit/btnguyen2k/olaf) [olaf](https://github.com/btnguyen2k/olaf) - Twitter Snowflake implemented in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code> ![](https://img.shields.io/github/last-commit/sinhashubham95/go-actuator) [go-actuator](https://github.com/sinhashubham95/go-actuator) - Production ready features for Go based web frameworks.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code> ![](https://img.shields.io/github/last-commit/sinhashubham95/bleep) [bleep](https://github.com/sinhashubham95/bleep) - Perform any number of actions on any set of OS signals in Go.

## UUID

*Libraries for working with UUIDs.*

* <code>&nbsp;&nbsp;2947</code> ![](https://img.shields.io/github/last-commit/google/uuid) [uuid](https://github.com/google/uuid) - Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services.
* <code>&nbsp;&nbsp;2322</code> ![](https://img.shields.io/github/last-commit/oklog/ulid) [ulid](https://github.com/oklog/ulid) - Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier).
* <code>&nbsp;&nbsp;&nbsp;954</code> ![](https://img.shields.io/github/last-commit/gofrs/uuid) [uuid](https://github.com/gofrs/uuid) - Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid.
* <code>&nbsp;&nbsp;&nbsp;424</code> ![](https://img.shields.io/github/last-commit/edwingeng/wuid) [wuid](https://github.com/edwingeng/wuid) - An extremely fast unique number generator, 10-135 times faster than UUID.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> ![](https://img.shields.io/github/last-commit/muyo/sno) [sno](https://github.com/muyo/sno) - Compact, sortable and fast unique IDs with embedded metadata.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/aidarkhanov/nanoid) [nanoid](https://github.com/aidarkhanov/nanoid) - A tiny and efficient Go unique string ID generator.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> ![](https://img.shields.io/github/last-commit/jakehl/goid) [goid](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> ![](https://img.shields.io/github/last-commit/agext/uuid) [uuid](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> ![](https://img.shields.io/github/last-commit/twharmon/gouid) [gouid](https://github.com/twharmon/gouid) - Generate cryptographically secure random string IDs with just one allocation.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/hart87/GoFlake) [goflake](https://github.com/hart87/GoFlake) - A small, scalable, & serverless unique ID generator for use in distributed systems. Inspired by Twitters Snowflake.
* [uniq](https://gitlab.com/skilstak/code/go/uniq) - No hassle safe, fast unique identifiers with commands.

## Validation

*Libraries for validation.*

* <code>&nbsp;&nbsp;8332</code> ![](https://img.shields.io/github/last-commit/go-playground/validator) [validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.
* <code>&nbsp;&nbsp;4859</code> ![](https://img.shields.io/github/last-commit/asaskevich/govalidator) [govalidator](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs.
* <code>&nbsp;&nbsp;2256</code> ![](https://img.shields.io/github/last-commit/go-ozzo/ozzo-validation) [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags.
* <code>&nbsp;&nbsp;1007</code> ![](https://img.shields.io/github/last-commit/thedevsaddam/govalidator) [govalidator](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation.
* <code>&nbsp;&nbsp;&nbsp;454</code> ![](https://img.shields.io/github/last-commit/gookit/validate) [validate](https://github.com/gookit/validate) - Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;80</code> ![](https://img.shields.io/github/last-commit/osamingo/checkdigit) [checkdigit](https://github.com/osamingo/checkdigit) - Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;60</code> ![](https://img.shields.io/github/last-commit/faceair/jio) [jio](https://github.com/faceair/jio) - jio is a json schema validator similar to <code>&nbsp;17420</code> ![](https://img.shields.io/github/last-commit/hapijs/joi) [joi](https://github.com/hapijs/joi).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> ![](https://img.shields.io/github/last-commit/thazelart/terraform-validator) [terraform-validator](https://github.com/thazelart/terraform-validator) - A norms and conventions validator for Terraform.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> ![](https://img.shields.io/github/last-commit/gobuffalo/validate) [validate](https://github.com/gobuffalo/validate) - This package provides a framework for writing validations for Go applications.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> ![](https://img.shields.io/github/last-commit/guiferpa/gody) [gody](https://github.com/guiferpa/gody) - :balloon: A lightweight struct validator for Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> ![](https://img.shields.io/github/last-commit/twharmon/govalid) [govalid](https://github.com/twharmon/govalid) - Fast, tag-based validation for structs.

## Version Control

*Libraries for version control.*

* <code>&nbsp;&nbsp;2513</code> ![](https://img.shields.io/github/last-commit/go-git/go-git) [go-git](https://github.com/go-git/go-git) - highly extensible Git implementation in pure Go.
* <code>&nbsp;&nbsp;1635</code> ![](https://img.shields.io/github/last-commit/libgit2/git2go) [git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2.
* <code>&nbsp;&nbsp;1392</code> ![](https://img.shields.io/github/last-commit/src-d/hercules) [hercules](https://github.com/src-d/hercules) - gaining advanced insights from Git repository history.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;75</code> ![](https://img.shields.io/github/last-commit/rjeczalik/gh) [gh](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;75</code> ![](https://img.shields.io/github/last-commit/sourcegraph/go-vcs) [go-vcs](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> ![](https://img.shields.io/github/last-commit/beyang/hgo) [hgo](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories.

## Video

*Libraries for manipulating video.*

* <code>&nbsp;&nbsp;1677</code> ![](https://img.shields.io/github/last-commit/giorgisio/goav) [goav](https://github.com/giorgisio/goav) - Comprehensive Go bindings for FFmpeg.
* <code>&nbsp;&nbsp;&nbsp;840</code> ![](https://img.shields.io/github/last-commit/grafov/m3u8) [m3u8](https://github.com/grafov/m3u8) - Parser and generator library of M3U8 playlists for Apple HLS.
* <code>&nbsp;&nbsp;&nbsp;696</code> ![](https://img.shields.io/github/last-commit/3d0c/gmf) [gmf](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries.
* <code>&nbsp;&nbsp;&nbsp;373</code> ![](https://img.shields.io/github/last-commit/asticode/go-astits) [go-astits](https://github.com/asticode/go-astits) - Parse and demux MPEG Transport Streams (.ts) natively in GO.
* <code>&nbsp;&nbsp;&nbsp;326</code> ![](https://img.shields.io/github/last-commit/asticode/go-astisub) [go-astisub](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).
* <code>&nbsp;&nbsp;&nbsp;226</code> ![](https://img.shields.io/github/last-commit/adrg/libvlc-go) [libvlc-go](https://github.com/adrg/libvlc-go) - Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player).
* <code>&nbsp;&nbsp;&nbsp;159</code> ![](https://img.shields.io/github/last-commit/ziutek/gst) [gst](https://github.com/ziutek/gst) - Go bindings for GStreamer.
* <code>&nbsp;&nbsp;&nbsp;104</code> ![](https://img.shields.io/github/last-commit/aler9/gortsplib) [gortsplib](https://github.com/aler9/gortsplib) - Pure Go RTSP server and client library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;75</code> ![](https://img.shields.io/github/last-commit/quangngotan95/go-m3u8) [go-m3u8](https://github.com/quangngotan95/go-m3u8) - Parser and generator library for Apple m3u8 playlists.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;58</code> ![](https://img.shields.io/github/last-commit/korandiz/v4l) [v4l](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/wargarblgarbl/libgosubs) [libgosubs](https://github.com/wargarblgarbl/libgosubs) - Subtitle format support for go. Supports .srt, .ttml, and .ass.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/unki2aut/go-mpd) [go-mpd](https://github.com/unki2aut/go-mpd) - Parser and generator library for MPEG-DASH manifest files.

## Web Frameworks

*Full stack web frameworks.*

* <code>&nbsp;50243</code> ![](https://img.shields.io/github/last-commit/gin-gonic/gin) [Gin](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.
* <code>&nbsp;20382</code> ![](https://img.shields.io/github/last-commit/labstack/echo) [Echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework.
* <code>&nbsp;14506</code> ![](https://img.shields.io/github/last-commit/gofiber/fiber) [Fiber](https://github.com/gofiber/fiber) - An Express.js inspired web framework build on Fasthttp.
* <code>&nbsp;12329</code> ![](https://img.shields.io/github/last-commit/revel/revel) [Revel](https://github.com/revel/revel) - High-productivity web framework for the Go language.
* <code>&nbsp;&nbsp;4322</code> ![](https://img.shields.io/github/last-commit/goadesign/goa) [Goa](https://github.com/goadesign/goa) - Goa provides a holistic approach for developing remote APIs and microservices in Go.
* <code>&nbsp;&nbsp;3474</code> ![](https://img.shields.io/github/last-commit/ant0ine/go-json-rest) [go-json-rest](https://github.com/ant0ine/go-json-rest) - Quick and easy way to setup a RESTful JSON API.
* <code>&nbsp;&nbsp;3463</code> ![](https://img.shields.io/github/last-commit/NYTimes/gizmo) [Gizmo](https://github.com/NYTimes/gizmo) - Microservice toolkit used by the New York Times.
* <code>&nbsp;&nbsp;3181</code> ![](https://img.shields.io/github/last-commit/go-macaron/macaron) [Macaron](https://github.com/go-macaron/macaron) - Macaron is a high productive and modular design web framework in Go.
* <code>&nbsp;&nbsp;2199</code> ![](https://img.shields.io/github/last-commit/gernest/utron) [utron](https://github.com/gernest/utron) - Lightweight MVC framework for Go(Golang).
* <code>&nbsp;&nbsp;&nbsp;997</code> ![](https://img.shields.io/github/last-commit/rcrowley/go-tigertonic) [tigertonic](https://github.com/rcrowley/go-tigertonic) - Go framework for building JSON web services inspired by Dropwizard.
* <code>&nbsp;&nbsp;&nbsp;869</code> ![](https://img.shields.io/github/last-commit/go-goyave/goyave) [Goyave](https://github.com/go-goyave/goyave) - Feature-complete REST API framework aimed at clean code and fast development, with powerful built-in functionalities.
* <code>&nbsp;&nbsp;&nbsp;833</code> ![](https://img.shields.io/github/last-commit/lunny/tango) [tango](https://github.com/lunny/tango) - Micro & pluggable web framework for Go.
* <code>&nbsp;&nbsp;&nbsp;529</code> ![](https://img.shields.io/github/last-commit/abahmed/gearbox) [Gearbox](https://github.com/abahmed/gearbox) - A web framework written in Go with a focus on high performance and memory optimization.
* <code>&nbsp;&nbsp;&nbsp;442</code> ![](https://img.shields.io/github/last-commit/mustafaakin/gongular) [gongular](https://github.com/mustafaakin/gongular) - Fast Go web framework with input mapping/validation and (DI) Dependency Injection.
* <code>&nbsp;&nbsp;&nbsp;412</code> ![](https://img.shields.io/github/last-commit/ivpusic/neo) [neo](https://github.com/ivpusic/neo) - Neo is minimal and fast Go Web Framework with extremely simple API.
* <code>&nbsp;&nbsp;&nbsp;405</code> ![](https://img.shields.io/github/last-commit/aofei/air) [Air](https://github.com/aofei/air) - An ideally refined web framework for Go.
* <code>&nbsp;&nbsp;&nbsp;394</code> ![](https://img.shields.io/github/last-commit/aerogo/aero) [Aero](https://github.com/aerogo/aero) - High-performance web framework for Go, reaches top scores in Lighthouse.
* <code>&nbsp;&nbsp;&nbsp;357</code> ![](https://img.shields.io/github/last-commit/paulbellamy/mango) [mango](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333.
* <code>&nbsp;&nbsp;&nbsp;308</code> ![](https://img.shields.io/github/last-commit/rainycape/gondola) [Gondola](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster.
* <code>&nbsp;&nbsp;&nbsp;249</code> ![](https://img.shields.io/github/last-commit/dinever/golf) [Golf](https://github.com/dinever/golf) - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library.
* <code>&nbsp;&nbsp;&nbsp;223</code> ![](https://img.shields.io/github/last-commit/i-love-flamingo/flamingo) [Flamingo](https://github.com/i-love-flamingo/flamingo) - Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc.
* <code>&nbsp;&nbsp;&nbsp;215</code> ![](https://img.shields.io/github/last-commit/astaxie/beego) [Beego](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language.
* <code>&nbsp;&nbsp;&nbsp;199</code> ![](https://img.shields.io/github/last-commit/i-love-flamingo/flamingo-commerce) [Flamingo Commerce](https://github.com/i-love-flamingo/flamingo-commerce) - Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications.
* <code>&nbsp;&nbsp;&nbsp;181</code> ![](https://img.shields.io/github/last-commit/xxjwxc/ginrpc) [Ginrpc](https://github.com/xxjwxc/ginrpc) - Gin parameter automatic binding tool,gin rpc tools.
* <code>&nbsp;&nbsp;&nbsp;176</code> ![](https://img.shields.io/github/last-commit/bnkamalesh/webgo) [WebGo](https://github.com/bnkamalesh/webgo) - A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc).
* <code>&nbsp;&nbsp;&nbsp;162</code> ![](https://img.shields.io/github/last-commit/hidevopsio/hiboot) [hiboot](https://github.com/hidevopsio/hiboot) - hiboot is a high performance web application framework with auto configuration and dependency injection support.
* <code>&nbsp;&nbsp;&nbsp;145</code> ![](https://img.shields.io/github/last-commit/uadmin/uadmin) [uAdmin](https://github.com/uadmin/uadmin) - Fully featured web framework for Golang, inspired by Django.
* <code>&nbsp;&nbsp;&nbsp;125</code> ![](https://img.shields.io/github/last-commit/ungerik/go-rest) [go-rest](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go.
* <code>&nbsp;&nbsp;&nbsp;103</code> ![](https://img.shields.io/github/last-commit/appist/appy) [appy](https://github.com/appist/appy) - An opinionated productive web framework that helps scaling business easier.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;77</code> ![](https://img.shields.io/github/last-commit/beatlabs/patron) [patron](https://github.com/beatlabs/patron) - Patron is a microservice framework following best cloud practices with a focus on productivity.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;74</code> ![](https://img.shields.io/github/last-commit/claygod/microservice) [Microservice](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;74</code> ![](https://img.shields.io/github/last-commit/aisk/vox) [vox](https://github.com/aisk/vox) - A golang web framework for humans, inspired by Koa heavily.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;73</code> ![](https://img.shields.io/github/last-commit/fulldump/golax) [Golax](https://github.com/fulldump/golax) - A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;66</code> ![](https://img.shields.io/github/last-commit/gookit/rux) [rux](https://github.com/gookit/rux) - Simple and fast web framework for build golang HTTP applications.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;62</code> ![](https://img.shields.io/github/last-commit/yarf-framework/yarf) [YARF](https://github.com/yarf-framework/yarf) - Fast micro-framework designed to build REST APIs and web services in a fast and simple way.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;56</code> ![](https://img.shields.io/github/last-commit/zpatrick/fireball) [Fireball](https://github.com/zpatrick/fireball) - More "natural" feeling web framework.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> ![](https://img.shields.io/github/last-commit/goa-go/goa) [goa](https://github.com/goa-go/goa) - goa is just like koajs for golang, it is a flexible, light, high-performance and extensible web framework based on middleware.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> ![](https://img.shields.io/github/last-commit/gotuna/gotuna) [GoTuna](https://github.com/gotuna/gotuna) - Minimalistic web framework for Go with mux router, middlewares, sessions, templates, embeded views and static files.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> ![](https://img.shields.io/github/last-commit/resoursea/api) [Resoursea](https://github.com/resoursea/api) - REST framework for quickly writing resource based services.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> ![](https://img.shields.io/github/last-commit/goanywhere/rex) [rex](https://github.com/goanywhere/rex) - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/twharmon/goweb) [goweb](https://github.com/twharmon/goweb) - Web framework with routing, websockets, logging, middleware, static file server (optional gzip), and automatic TLS.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> ![](https://img.shields.io/github/last-commit/nsheremet/banjo) [Banjo](https://github.com/nsheremet/banjo) - Very simple and fast web framework for Go.
* [REST Layer](http://rest-layer.io) - Framework to build REST/GraphQL API on top of databases with mostly configuration over code.
* [aah](https://aahframework.org) - Scalable, performant, rapid development Web framework for Go.
* [Confetti Framework](https://www.confetti-framework.com) - Confetti is a Go web application framework with an expressive, elegant syntax. Confetti combines the elegance of Laravel and the simplicity of Go.
* [Buffalo](http://gobuffalo.io) - Bringing the productivity of Rails to Go!

### Middlewares

#### Actual middlewares

* <code>&nbsp;&nbsp;1980</code> ![](https://img.shields.io/github/last-commit/didip/tollbooth) [Tollbooth](https://github.com/didip/tollbooth) - Rate limit HTTP request handler.
* <code>&nbsp;&nbsp;1880</code> ![](https://img.shields.io/github/last-commit/rs/cors) [CORS](https://github.com/rs/cors) - Easily add CORS capabilities to your API.
* <code>&nbsp;&nbsp;1309</code> ![](https://img.shields.io/github/last-commit/ulule/limiter) [Limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go.
* <code>&nbsp;&nbsp;&nbsp;820</code> ![](https://img.shields.io/github/last-commit/mitchellh/go-server-timing) [go-server-timing](https://github.com/mitchellh/go-server-timing) - Add/parse Server-Timing header.
* <code>&nbsp;&nbsp;&nbsp;403</code> ![](https://img.shields.io/github/last-commit/github/go-fault) [go-fault](https://github.com/github/go-fault) - Fault injection middleware for Go.
* <code>&nbsp;&nbsp;&nbsp;112</code> ![](https://img.shields.io/github/last-commit/philippgille/ln-paywall) [ln-paywall](https://github.com/philippgille/ln-paywall) - Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;81</code> ![](https://img.shields.io/github/last-commit/sebest/xff) [XFF](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> ![](https://img.shields.io/github/last-commit/rs/formjson) [formjson](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> ![](https://img.shields.io/github/last-commit/posener/client-timing) [client-timing](https://github.com/posener/client-timing) - An HTTP client for Server-Timing header.

#### Libraries for creating HTTP middlewares

* <code>&nbsp;&nbsp;7045</code> ![](https://img.shields.io/github/last-commit/urfave/negroni) [negroni](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang.
* <code>&nbsp;&nbsp;2325</code> ![](https://img.shields.io/github/last-commit/justinas/alice) [alice](https://github.com/justinas/alice) - Painless middleware chaining for Go.
* <code>&nbsp;&nbsp;1525</code> ![](https://img.shields.io/github/last-commit/unrolled/render) [render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses.
* <code>&nbsp;&nbsp;&nbsp;579</code> ![](https://img.shields.io/github/last-commit/thoas/stats) [stats](https://github.com/thoas/stats) - Go middleware that stores various information about your web application.
* <code>&nbsp;&nbsp;&nbsp;291</code> ![](https://img.shields.io/github/last-commit/carbocation/interpose) [interpose](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang.
* <code>&nbsp;&nbsp;&nbsp;224</code> ![](https://img.shields.io/github/last-commit/thedevsaddam/renderer) [renderer](https://github.com/thedevsaddam/renderer) - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go.
* <code>&nbsp;&nbsp;&nbsp;209</code> ![](https://img.shields.io/github/last-commit/stephens2424/muxchain) [muxchain](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;97</code> ![](https://img.shields.io/github/last-commit/alioygur/gores) [gores](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;97</code> ![](https://img.shields.io/github/last-commit/InVisionApp/rye) [rye](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;74</code> ![](https://img.shields.io/github/last-commit/HereMobilityDevelopers/mediary) [mediary](https://github.com/HereMobilityDevelopers/mediary) - add interceptors to `http.Client` to allow dumping/shaping/tracing/... of requests/responses.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;63</code> ![](https://img.shields.io/github/last-commit/codemodus/chain) [chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware").
* <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> ![](https://img.shields.io/github/last-commit/go-on/wrap) [go-wrap](https://github.com/go-on/wrap) - Small middlewares package for net/http.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/codemodus/catena) [catena](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain").

### Routers

* <code>&nbsp;14856</code> ![](https://img.shields.io/github/last-commit/gorilla/mux) [mux](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang.
* <code>&nbsp;12985</code> ![](https://img.shields.io/github/last-commit/julienschmidt/httprouter) [httprouter](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework.
* <code>&nbsp;&nbsp;9816</code> ![](https://img.shields.io/github/last-commit/go-chi/chi) [chi](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context.
* <code>&nbsp;&nbsp;1444</code> ![](https://img.shields.io/github/last-commit/gocraft/web) [gocraft/web](https://github.com/gocraft/web) - Mux and middleware package in Go.
* <code>&nbsp;&nbsp;1275</code> ![](https://img.shields.io/github/last-commit/go-zoo/bone) [Bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer.
* <code>&nbsp;&nbsp;&nbsp;873</code> ![](https://img.shields.io/github/last-commit/buaazp/fasthttprouter) [fasthttprouter](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`.
* <code>&nbsp;&nbsp;&nbsp;872</code> ![](https://img.shields.io/github/last-commit/goji/goji) [Goji](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`.
* <code>&nbsp;&nbsp;&nbsp;499</code> ![](https://img.shields.io/github/last-commit/xujiajun/gorouter) [xujiajun/gorouter](https://github.com/xujiajun/gorouter) - A simple and fast HTTP router for Go.
* <code>&nbsp;&nbsp;&nbsp;498</code> ![](https://img.shields.io/github/last-commit/dimfeld/httptreemux) [httptreemux](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter.
* <code>&nbsp;&nbsp;&nbsp;407</code> ![](https://img.shields.io/github/last-commit/go-ozzo/ozzo-routing) [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs.
* <code>&nbsp;&nbsp;&nbsp;382</code> ![](https://img.shields.io/github/last-commit/go-playground/lars) [lars](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks.
* <code>&nbsp;&nbsp;&nbsp;349</code> ![](https://img.shields.io/github/last-commit/VividCortex/siesta) [Siesta](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers.
* <code>&nbsp;&nbsp;&nbsp;263</code> ![](https://img.shields.io/github/last-commit/husobee/vestigo) [vestigo](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications.
* <code>&nbsp;&nbsp;&nbsp;160</code> ![](https://img.shields.io/github/last-commit/gowww/router) [gowww/router](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface.
* <code>&nbsp;&nbsp;&nbsp;120</code> ![](https://img.shields.io/github/last-commit/gernest/alien) [alien](https://github.com/gernest/alien) - Lightweight and fast http router from outer space.
* <code>&nbsp;&nbsp;&nbsp;115</code> ![](https://img.shields.io/github/last-commit/go-playground/pure) [pure](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation.
* <code>&nbsp;&nbsp;&nbsp;103</code> ![](https://img.shields.io/github/last-commit/nbari/violetear) [violetear](https://github.com/nbari/violetear) - Go HTTP router.
* <code>&nbsp;&nbsp;&nbsp;102</code> ![](https://img.shields.io/github/last-commit/claygod/Bxog) [Bxog](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;97</code> ![](https://img.shields.io/github/last-commit/vardius/gorouter) [GoRouter](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;90</code> ![](https://img.shields.io/github/last-commit/rs/xmux) [xmux](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> ![](https://img.shields.io/github/last-commit/GuilhermeCaruso/bellt) [bellt](https://github.com/GuilhermeCaruso/bellt) - A simple Go HTTP router.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> ![](https://img.shields.io/github/last-commit/razonyang/fastrouter) [FastRouter](https://github.com/razonyang/fastrouter) - a fast, flexible HTTP router written in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/goroute/route) [goroute](https://github.com/goroute/route) - Simple yet powerful HTTP request multiplexer.

## WebAssembly

* <code>&nbsp;&nbsp;8383</code> ![](https://img.shields.io/github/last-commit/tinygo-org/tinygo) [tinygo](https://github.com/tinygo-org/tinygo) - Go compiler for small places. Microcontrollers, WebAssembly, and command-line tools. Based on LLVM.
* <code>&nbsp;&nbsp;&nbsp;434</code> ![](https://img.shields.io/github/last-commit/dennwc/dom) [dom](https://github.com/dennwc/dom) - DOM library.
* <code>&nbsp;&nbsp;&nbsp;138</code> ![](https://img.shields.io/github/last-commit/markfarnan/go-canvas) [go-canvas](https://github.com/markfarnan/go-canvas) - Library to use HTML5 Canvas, with all drawing within go code.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;86</code> ![](https://img.shields.io/github/last-commit/gowebapi/webapi) [webapi](https://github.com/gowebapi/webapi) - Bindings for DOM and HTML generated from WebIDL.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;82</code> ![](https://img.shields.io/github/last-commit/agnivade/wasmbrowsertest) [wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) - Run Go WASM tests in your browser.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> ![](https://img.shields.io/github/last-commit/norunners/vert) [vert](https://github.com/norunners/vert) - Interop between Go and JS values.

## Windows

* <code>&nbsp;&nbsp;&nbsp;779</code> ![](https://img.shields.io/github/last-commit/go-ole/go-ole) [go-ole](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang.
* <code>&nbsp;&nbsp;&nbsp;122</code> ![](https://img.shields.io/github/last-commit/gonutz/d3d9) [d3d9](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/MonaxGT/gosddl) [gosddl](https://github.com/MonaxGT/gosddl) - Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL.

## XML

*Libraries and tools for manipulating XML.*

* <code>&nbsp;&nbsp;&nbsp;481</code> ![](https://img.shields.io/github/last-commit/miku/zek) [zek](https://github.com/miku/zek) - Generate a Go struct from XML.
* <code>&nbsp;&nbsp;&nbsp;407</code> ![](https://img.shields.io/github/last-commit/antchfx/xpath) [xpath](https://github.com/antchfx/xpath) - XPath package for Go.
* <code>&nbsp;&nbsp;&nbsp;155</code> ![](https://img.shields.io/github/last-commit/antchfx/xquery) [xquery](https://github.com/antchfx/xquery) - XQuery lets you extract data from HTML/XML documents using XPath expression.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/sbabiv/xml2map) [xml2map](https://github.com/sbabiv/xml2map) - XML to MAP converter written Golang.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> ![](https://img.shields.io/github/last-commit/shabbyrobe/xmlwriter) [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/xml-comp/xml-comp) [XML-Comp](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags.

# Tools

*Go software and plugins.*

## Code Analysis

* <code>&nbsp;&nbsp;4045</code> ![](https://img.shields.io/github/last-commit/dominikh/go-tools) [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
* <code>&nbsp;&nbsp;4045</code> ![](https://img.shields.io/github/last-commit/dominikh/go-tools) [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - gosimple is a linter for Go source code that specialises on simplifying code.
* <code>&nbsp;&nbsp;4045</code> ![](https://img.shields.io/github/last-commit/dominikh/go-tools) [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - unused checks Go code for unused constants, variables, functions and types.
* <code>&nbsp;&nbsp;3901</code> ![](https://img.shields.io/github/last-commit/golang/lint) [GoLint](https://github.com/golang/lint) - Golint is a linter for Go source code.
* <code>&nbsp;&nbsp;1713</code> ![](https://img.shields.io/github/last-commit/kisielk/errcheck) [errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs.
* <code>&nbsp;&nbsp;1022</code> ![](https://img.shields.io/github/last-commit/davecheney/gcvis) [gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time.
* <code>&nbsp;&nbsp;&nbsp;965</code> ![](https://img.shields.io/github/last-commit/go-critic/go-critic) [go-critic](https://github.com/go-critic/go-critic) - source code linter that brings checks that are currently not implemented in other linters.
* <code>&nbsp;&nbsp;&nbsp;814</code> ![](https://img.shields.io/github/last-commit/z7zmey/php-parser) [php-parser](https://github.com/z7zmey/php-parser) - A Parser for PHP written in Go.
* <code>&nbsp;&nbsp;&nbsp;528</code> ![](https://img.shields.io/github/last-commit/yuroyoro/goast-viewer) [goast-viewer](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer.
* <code>&nbsp;&nbsp;&nbsp;522</code> ![](https://img.shields.io/github/last-commit/psampaz/go-mod-outdated) [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) - An easy way to find outdated dependencies of your Go projects.
* <code>&nbsp;&nbsp;&nbsp;481</code> ![](https://img.shields.io/github/last-commit/roblaszczak/go-cleanarch) [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects.
* <code>&nbsp;&nbsp;&nbsp;452</code> ![](https://img.shields.io/github/last-commit/jfeliu007/goplantuml) [GoPlantUML](https://github.com/jfeliu007/goplantuml) - Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them.
* <code>&nbsp;&nbsp;&nbsp;309</code> ![](https://img.shields.io/github/last-commit/mdempsky/unconvert) [unconvert](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source.
* <code>&nbsp;&nbsp;&nbsp;258</code> ![](https://img.shields.io/github/last-commit/augmentable-dev/tickgit) [tickgit](https://github.com/augmentable-dev/tickgit) - CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author.
* <code>&nbsp;&nbsp;&nbsp;250</code> ![](https://img.shields.io/github/last-commit/mibk/dupl) [dupl](https://github.com/mibk/dupl) - Tool for code clone detection.
* <code>&nbsp;&nbsp;&nbsp;246</code> ![](https://img.shields.io/github/last-commit/shurcooL/gostatus) [gostatus](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages.
* <code>&nbsp;&nbsp;&nbsp;215</code> ![](https://img.shields.io/github/last-commit/segmentio/golines) [golines](https://github.com/segmentio/golines) - Formatter that automatically shortens long lines in Go code.
* <code>&nbsp;&nbsp;&nbsp;173</code> ![](https://img.shields.io/github/last-commit/bradleyfalzon/apicompat) [apicompat](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes.
* <code>&nbsp;&nbsp;&nbsp;115</code> ![](https://img.shields.io/github/last-commit/qiniu/checkstyle) [go-checkstyle](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;66</code> ![](https://img.shields.io/github/last-commit/surullabs/lint) [lint](https://github.com/surullabs/lint) - Run linters as part of go test.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;60</code> ![](https://img.shields.io/github/last-commit/mccoyst/validate) [validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> ![](https://img.shields.io/github/last-commit/firstrow/go-outdated) [go-outdated](https://github.com/firstrow/go-outdated) - Console application that displays outdated packages.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/verygoodsoftwarenotvirus/tarp) [tarp](https://github.com/verygoodsoftwarenotvirus/tarp) - tarp finds functions and methods without direct unit tests in Go source code.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/arxdsilva/golang-ifood-sdk) [golang-ifood-sdk](https://github.com/arxdsilva/golang-ifood-sdk) - iFood API SDK.
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* [GoCover.io](http://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.

## Editor Plugins

* <code>&nbsp;13630</code> ![](https://img.shields.io/github/last-commit/fatih/vim-go) [vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim.
* <code>&nbsp;&nbsp;4923</code> ![](https://img.shields.io/github/last-commit/nsf/gocode) [gocode](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language.
* <code>&nbsp;&nbsp;3409</code> ![](https://img.shields.io/github/last-commit/DisposaBoy/GoSublime) [GoSublime](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features.
* <code>&nbsp;&nbsp;1907</code> ![](https://img.shields.io/github/last-commit/golang/vscode-go) [vscode-go](https://github.com/golang/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language.
* <code>&nbsp;&nbsp;1519</code> ![](https://img.shields.io/github/last-commit/joefitzgerald/go-plus) [go-plus](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting.
* <code>&nbsp;&nbsp;1168</code> ![](https://img.shields.io/github/last-commit/dominikh/go-mode.el) [go-mode](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs.
* <code>&nbsp;&nbsp;&nbsp;186</code> ![](https://img.shields.io/github/last-commit/eaburns/Watch) [Watch](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;88</code> ![](https://img.shields.io/github/last-commit/rjohnsondev/vim-compiler-go) [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;60</code> ![](https://img.shields.io/github/last-commit/incu6us/goimports-reviser) [goimports-reviser](https://github.com/incu6us/goimports-reviser) - Formatting tool for imports.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/theia-ide/go-language-server) [go-language-server](https://github.com/theia-ide/go-language-server) - A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> ![](https://img.shields.io/github/last-commit/hexdigest/gounit-vim) [gounit-vim](https://github.com/hexdigest/gounit-vim) - Vim plugin for generating Go tests based on the function's or method's signature.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/theia-ide/theia-go-extension) [theia-go-extension](https://github.com/theia-ide/theia-go-extension) - Go language support for the Theia IDE.
* [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) - This extension adds benchmark profiling support for the Go language to VS Code.
* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.

## Go Generate Tools

* <code>&nbsp;&nbsp;3352</code> ![](https://img.shields.io/github/last-commit/cweill/gotests) [gotests](https://github.com/cweill/gotests) - Generate Go tests from your source code.
* <code>&nbsp;&nbsp;1550</code> ![](https://img.shields.io/github/last-commit/cheekybits/genny) [genny](https://github.com/cheekybits/genny) - Elegant generics for Go.
* <code>&nbsp;&nbsp;&nbsp;185</code> ![](https://img.shields.io/github/last-commit/opennota/re2dfa) [re2dfa](https://github.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code.
* <code>&nbsp;&nbsp;&nbsp;111</code> ![](https://img.shields.io/github/last-commit/bouk/gonerics) [gonerics](http://github.com/bouk/gonerics) - Idiomatic Generics in Go.
* <code>&nbsp;&nbsp;&nbsp;105</code> ![](https://img.shields.io/github/last-commit/xuri/xgen) [xgen](https://github.com/xuri/xgen) - XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;95</code> ![](https://img.shields.io/github/last-commit/DylanMeeus/hasgo) [hasgo](https://github.com/DylanMeeus/hasgo) - Generate Haskell inspired functions for your slices.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;72</code> ![](https://img.shields.io/github/last-commit/Parquery/gocontracts) [gocontracts](https://github.com/Parquery/gocontracts) - brings design-by-contract to Go by synchronizing the code with the documentation.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;56</code> ![](https://img.shields.io/github/last-commit/hexdigest/gounit) [gounit](https://github.com/hexdigest/gounit) - Generate Go tests using your own templates.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> ![](https://img.shields.io/github/last-commit/usk81/generic) [generic](https://github.com/usk81/generic) - flexible data type for Go.
* [TOML-to-Go](https://xuri.me/toml-to-go) - Translates TOML into a Go type in the browser instantly.

## Go Tools

* <code>&nbsp;&nbsp;6637</code> ![](https://img.shields.io/github/last-commit/go-swagger/go-swagger) [go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API.
* <code>&nbsp;&nbsp;4775</code> ![](https://img.shields.io/github/last-commit/OctoLinker/browser-extension) [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.
* <code>&nbsp;&nbsp;3453</code> ![](https://img.shields.io/github/last-commit/TrueFurby/go-callvis) [go-callvis](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format.
* <code>&nbsp;&nbsp;&nbsp;633</code> ![](https://img.shields.io/github/last-commit/KyleBanks/depth) [depth](https://github.com/KyleBanks/depth) - Visualize dependency trees of any package by analyzing imports.
* <code>&nbsp;&nbsp;&nbsp;592</code> ![](https://img.shields.io/github/last-commit/kyoh86/richgo) [richgo](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations.
* <code>&nbsp;&nbsp;&nbsp;214</code> ![](https://img.shields.io/github/last-commit/galeone/rts) [rts](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses.
* <code>&nbsp;&nbsp;&nbsp;177</code> ![](https://img.shields.io/github/last-commit/tylerwince/godbg) [godbg](https://github.com/tylerwince/godbg) - Implementation of Rusts `dbg!` macro for quick and easy debugging during development.
* <code>&nbsp;&nbsp;&nbsp;132</code> ![](https://img.shields.io/github/last-commit/dtgorski/typex) [typex](https://github.com/dtgorski/typex) - Examine Go types and their transitive dependencies, alternatively export results as TypeScript value objects (or types) declaration.
* <code>&nbsp;&nbsp;&nbsp;108</code> ![](https://img.shields.io/github/last-commit/songgao/colorgo) [colorgo](https://github.com/songgao/colorgo) - Wrapper around `go` command for colorized `go build` output.
* <code>&nbsp;&nbsp;&nbsp;101</code> ![](https://img.shields.io/github/last-commit/psampaz/gothanks) [gothanks](https://github.com/psampaz/gothanks) - GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;60</code> ![](https://img.shields.io/github/last-commit/becheran/roumon) [roumon](https://github.com/becheran/roumon) - Monitor current state of all active goroutines via a command line interface.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;44</code> ![](https://img.shields.io/github/last-commit/rocketlaunchr/igo) [igo](https://github.com/rocketlaunchr/igo) - An igo to go transpiler (new language features for Go language!)
* <code>&nbsp;&nbsp;&nbsp;&nbsp;43</code> ![](https://img.shields.io/github/last-commit/pieterclaerhout/go-james) [go-james](https://github.com/pieterclaerhout/go-james) - Go project skeleton creator, builds and tests your projects without the manual setup.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> ![](https://img.shields.io/github/last-commit/skelterjohn/go-pkg-complete) [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - Bash completion for go and wgo.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> ![](https://img.shields.io/github/last-commit/axelspringer/generator-go-lang) [generator-go-lang](https://github.com/axelspringer/generator-go-lang) - A [Yeoman](http://yeoman.io) generator to get new Go projects started.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> ![](https://img.shields.io/github/last-commit/dustinblackman/gomodrun) [gomodrun](https://github.com/dustinblackman/gomodrun/) - Go tool that executes and caches binaries included in go.mod files.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/go-oas/docs) [docs](https://github.com/go-oas/docs) - Automatically generate RESTful API documentation for GO projects - aligned with Open API Specification standard.

## Software Packages

*Software written in Go.*

### DevOps Tools

* <code>&nbsp;79648</code> ![](https://img.shields.io/github/last-commit/kubernetes/kubernetes) [kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google.
* <code>&nbsp;60804</code> ![](https://img.shields.io/github/last-commit/moby/moby) [Moby](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems.
* <code>&nbsp;34565</code> ![](https://img.shields.io/github/last-commit/containous/traefik) [traefik](https://github.com/containous/traefik) - Reverse proxy and load balancer with support for multiple backends.
* <code>&nbsp;25639</code> ![](https://img.shields.io/github/last-commit/go-gitea/gitea) [Gitea](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven.
* <code>&nbsp;17996</code> ![](https://img.shields.io/github/last-commit/tsenart/vegeta) [Vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000!
* <code>&nbsp;13048</code> ![](https://img.shields.io/github/last-commit/mitchellh/packer) [Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
* <code>&nbsp;11710</code> ![](https://img.shields.io/github/last-commit/rakyll/hey) [Hey](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application.
* <code>&nbsp;&nbsp;6785</code> ![](https://img.shields.io/github/last-commit/adnanh/webhook) [webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.
* <code>&nbsp;&nbsp;6457</code> ![](https://img.shields.io/github/last-commit/moovweb/gvm) [GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions.
* <code>&nbsp;&nbsp;4426</code> ![](https://img.shields.io/github/last-commit/gaia-pipeline/gaia) [gaia](https://github.com/gaia-pipeline/gaia) - Build powerful pipelines in any programming language.
* <code>&nbsp;&nbsp;4071</code> ![](https://img.shields.io/github/last-commit/mitchellh/gox) [gox](https://github.com/mitchellh/gox) - Dead simple, no frills Go cross compile tool.
* <code>&nbsp;&nbsp;3171</code> ![](https://img.shields.io/github/last-commit/bosun-monitor/bosun) [bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework.
* <code>&nbsp;&nbsp;2730</code> ![](https://img.shields.io/github/last-commit/codesenberg/bombardier) [bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool.
* <code>&nbsp;&nbsp;2638</code> ![](https://img.shields.io/github/last-commit/pomerium/pomerium) [Pomerium](https://github.com/pomerium/pomerium) - Pomerium is an identity-aware access proxy.
* <code>&nbsp;&nbsp;1854</code> ![](https://img.shields.io/github/last-commit/bitfield/script) [script](https://github.com/bitfield/script) - Making it easy to write shell-like scripts in Go for DevOps and system administration tasks.
* <code>&nbsp;&nbsp;1721</code> ![](https://img.shields.io/github/last-commit/mkchoi212/fac) [fac](https://github.com/mkchoi212/fac) - Command-line user interface to fix git merge conflicts.
* <code>&nbsp;&nbsp;1702</code> ![](https://img.shields.io/github/last-commit/ajvb/kala) [kala](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler.
* <code>&nbsp;&nbsp;1669</code> ![](https://img.shields.io/github/last-commit/laher/goxc) [goxc](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging.
* <code>&nbsp;&nbsp;1502</code> ![](https://img.shields.io/github/last-commit/sanathp/statusok) [StatusOK](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected.
* <code>&nbsp;&nbsp;1102</code> ![](https://img.shields.io/github/last-commit/rlmcpherson/s3gof3r) [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.
* <code>&nbsp;&nbsp;&nbsp;857</code> ![](https://img.shields.io/github/last-commit/sanbornm/go-selfupdate) [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update.
* <code>&nbsp;&nbsp;&nbsp;756</code> ![](https://img.shields.io/github/last-commit/peak/s5cmd) [s5cmd](https://github.com/peak/s5cmd) - Blazing fast S3 and local filesystem execution tool.
* <code>&nbsp;&nbsp;&nbsp;701</code> ![](https://img.shields.io/github/last-commit/TimothyYe/skm) [skm](https://github.com/TimothyYe/skm) - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily!
* <code>&nbsp;&nbsp;&nbsp;679</code> ![](https://img.shields.io/github/last-commit/scaleway/scaleway-cli) [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker).
* <code>&nbsp;&nbsp;&nbsp;529</code> ![](https://img.shields.io/github/last-commit/xuri/aurora) [aurora](https://github.com/xuri/aurora) - Cross-platform web-based Beanstalkd queue server console.
* <code>&nbsp;&nbsp;&nbsp;524</code> ![](https://img.shields.io/github/last-commit/rogerwelin/cassowary) [cassowary](https://github.com/rogerwelin/cassowary) - Modern cross-platform HTTP load-testing tool written in Go.
* <code>&nbsp;&nbsp;&nbsp;492</code> ![](https://img.shields.io/github/last-commit/ahmetalpbalkan/govvv) [govvv](https://github.com/ahmetalpbalkan/govvv) - “go build” wrapper to easily add version information into Go binaries.
* <code>&nbsp;&nbsp;&nbsp;480</code> ![](https://img.shields.io/github/last-commit/ovh/utask) [uTask](https://github.com/ovh/utask) - Automation engine that models and executes business processes declared in yaml.
* <code>&nbsp;&nbsp;&nbsp;474</code> ![](https://img.shields.io/github/last-commit/gabrie30/ghorg) [ghorg](https://github.com/gabrie30/ghorg) - Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, Gitea, and Bitbucket.
* <code>&nbsp;&nbsp;&nbsp;327</code> ![](https://img.shields.io/github/last-commit/inconshreveable/gonative) [gonative](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.
* <code>&nbsp;&nbsp;&nbsp;301</code> ![](https://img.shields.io/github/last-commit/xitonix/trubka) [trubka](https://github.com/xitonix/trubka) - A CLI tool to manage and troubleshoot Apache Kafka clusters with the ability of generically publishing/consuming protocol buffer and plain text events to/from Kafka.
* <code>&nbsp;&nbsp;&nbsp;288</code> ![](https://img.shields.io/github/last-commit/emicklei/mora) [Mora](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data.
* <code>&nbsp;&nbsp;&nbsp;287</code> ![](https://img.shields.io/github/last-commit/bengadbois/pewpew) [Pewpew](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester.
* <code>&nbsp;&nbsp;&nbsp;282</code> ![](https://img.shields.io/github/last-commit/ivanilves/lstags) [lstags](https://github.com/ivanilves/lstags) - Tool and API to sync Docker images across different registries.
* <code>&nbsp;&nbsp;&nbsp;271</code> ![](https://img.shields.io/github/last-commit/jenkins-zh/jenkins-cli) [jcli](https://github.com/jenkins-zh/jenkins-cli) - Jenkins CLI allows you manage your Jenkins as an easy way.
* <code>&nbsp;&nbsp;&nbsp;240</code> ![](https://img.shields.io/github/last-commit/liudng/dogo) [dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart).
* <code>&nbsp;&nbsp;&nbsp;228</code> ![](https://img.shields.io/github/last-commit/xwjdsh/manssh) [manssh](https://github.com/xwjdsh/manssh) - manssh is a command line tool for managing your ssh alias config easily.
* <code>&nbsp;&nbsp;&nbsp;224</code> ![](https://img.shields.io/github/last-commit/sirnewton01/godbg) [godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application.
* <code>&nbsp;&nbsp;&nbsp;200</code> ![](https://img.shields.io/github/last-commit/dave/blast) [Blast](https://github.com/dave/blast) - A simple tool for API load testing and batch jobs.
* <code>&nbsp;&nbsp;&nbsp;195</code> ![](https://img.shields.io/github/last-commit/balerter/balerter) [Balerter](https://github.com/balerter/balerter) - A self-hosted script-based alerting manager
* <code>&nbsp;&nbsp;&nbsp;192</code> ![](https://img.shields.io/github/last-commit/appleboy/easyssh-proxy) [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`.
* <code>&nbsp;&nbsp;&nbsp;182</code> ![](https://img.shields.io/github/last-commit/cryptojuice/gobrew) [gobrew](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go.
* <code>&nbsp;&nbsp;&nbsp;172</code> ![](https://img.shields.io/github/last-commit/ostrost/ostent) [ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB.
* <code>&nbsp;&nbsp;&nbsp;166</code> ![](https://img.shields.io/github/last-commit/dnnrly/abbreviate) [abbreviate](https://github.com/dnnrly/abbreviate) - abbreviate is a tool turning long strings in to shorter ones with configurable seperaters, for example to embed branch names in to deployment stack IDs.
* <code>&nbsp;&nbsp;&nbsp;161</code> ![](https://img.shields.io/github/last-commit/dikhan/terraform-provider-openapi) [terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) - Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed.
* <code>&nbsp;&nbsp;&nbsp;155</code> ![](https://img.shields.io/github/last-commit/cswank/kcli) [kcli](https://github.com/cswank/kcli) - Command line tool for inspecting kafka topics/partitions/messages.
* <code>&nbsp;&nbsp;&nbsp;152</code> ![](https://img.shields.io/github/last-commit/yaronsumel/grapes) [grapes](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease.
* <code>&nbsp;&nbsp;&nbsp;122</code> ![](https://img.shields.io/github/last-commit/masterzen/winrm-cli) [winrm-cli](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines.
* <code>&nbsp;&nbsp;&nbsp;111</code> ![](https://img.shields.io/github/last-commit/ozankasikci/dockerfile-generator) [Dockerfile-Generator](https://github.com/ozankasikci/dockerfile-generator) - A go library and an executable that produces valid Dockerfiles using various input channels.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> ![](https://img.shields.io/github/last-commit/appleboy/drone-scp) [drone-scp](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;83</code> ![](https://img.shields.io/github/last-commit/go-furnace/go-furnace) [go-furnace](https://github.com/go-furnace/go-furnace) - Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> ![](https://img.shields.io/github/last-commit/oxyno-zeta/s3-proxy) [s3-proxy](https://github.com/oxyno-zeta/s3-proxy) - S3 Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> ![](https://img.shields.io/github/last-commit/chrismckenzie/dropship) [Dropship](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;32</code> ![](https://img.shields.io/github/last-commit/appleboy/drone-jenkins) [drone-jenkins](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> ![](https://img.shields.io/github/last-commit/alouche/rodent) [Rodent](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> ![](https://img.shields.io/github/last-commit/soniah/awsenv) [awsenv](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> ![](https://img.shields.io/github/last-commit/timdp/lwc) [lwc](https://github.com/timdp/lwc) - A live-updating version of the UNIX wc command.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> ![](https://img.shields.io/github/last-commit/centerorbit/depcharge) [DepCharge](https://github.com/centerorbit/depcharge) - Helps orchestrating the execution of commands across the many dependencies in larger projects.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/x1unix/docker-go-mingw) [docker-go-mingw](https://github.com/x1unix/docker-go-mingw) - Docker image for building Go binaries for Windows with MinGW toolchain.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/dnnrly/httpref) [httpref](https://github.com/dnnrly/httpref) - httpref is a handy CLI reference for HTTP methods, status codes, headers, and TCP and UDP ports.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/ChristopherRabotin/sg) [sg](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/smira/aptly) [aptly](https://github.com/smira/aptly) - aptly is a Debian repository management tool.
* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) - Migrate all your GitHub repositories, issues, milestones and labels to your Gitea instance.
* [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.

### Other Software

* <code>&nbsp;14500</code> ![](https://img.shields.io/github/last-commit/schollz/croc) [croc](https://github.com/schollz/croc) - Easily and securely send files or folders from one computer to another.
* <code>&nbsp;14445</code> ![](https://img.shields.io/github/last-commit/buger/gor) [Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.
* <code>&nbsp;13328</code> ![](https://img.shields.io/github/last-commit/restic/restic) [restic](https://github.com/restic/restic) - De-duplicating backup program.
* <code>&nbsp;12430</code> ![](https://img.shields.io/github/last-commit/chrislusf/seaweedfs) [Seaweed File System](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek.
* <code>&nbsp;&nbsp;7553</code> ![](https://img.shields.io/github/last-commit/kelseyhightower/confd) [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul.
* <code>&nbsp;&nbsp;7498</code> ![](https://img.shields.io/github/last-commit/tylertreat/Comcast) [Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections.
* <code>&nbsp;&nbsp;6520</code> ![](https://img.shields.io/github/last-commit/visualfc/liteide) [LiteIDE](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE.
* <code>&nbsp;&nbsp;6098</code> ![](https://img.shields.io/github/last-commit/odeke-em/drive) [drive](https://github.com/odeke-em/drive) - Google Drive client for the commandline.
* <code>&nbsp;&nbsp;5579</code> ![](https://img.shields.io/github/last-commit/shopify/toxiproxy) [toxiproxy](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests.
* <code>&nbsp;&nbsp;4806</code> ![](https://img.shields.io/github/last-commit/fogleman/nes) [nes](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go.
* <code>&nbsp;&nbsp;3764</code> ![](https://img.shields.io/github/last-commit/gilbertchen/duplicacy) [Duplicacy](https://github.com/gilbertchen/duplicacy) - A cross-platform network and cloud backup tool based on the idea of lock-free deduplication.
* <code>&nbsp;&nbsp;2659</code> ![](https://img.shields.io/github/last-commit/boyter/scc) [scc](https://github.com/boyter/scc) - Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates.
* <code>&nbsp;&nbsp;2500</code> ![](https://img.shields.io/github/last-commit/mehrdadrad/mylg) [myLG](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go.
* <code>&nbsp;&nbsp;2372</code> ![](https://img.shields.io/github/last-commit/Humpheh/goboy) [GoBoy](https://github.com/Humpheh/goboy) - Nintendo Game Boy Color emulator written in Go.
* <code>&nbsp;&nbsp;2270</code> ![](https://img.shields.io/github/last-commit/pressly/sup) [Stack Up](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers.
* <code>&nbsp;&nbsp;2191</code> ![](https://img.shields.io/github/last-commit/yunabe/lgo) [lgo](https://github.com/yunabe/lgo) - Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility.
* <code>&nbsp;&nbsp;1905</code> ![](https://img.shields.io/github/last-commit/gocircuit/circuit) [Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
* <code>&nbsp;&nbsp;1793</code> ![](https://img.shields.io/github/last-commit/intelsdi-x/snap) [snap](https://github.com/intelsdi-x/snap) - Powerful telemetry framework.
* <code>&nbsp;&nbsp;1517</code> ![](https://img.shields.io/github/last-commit/crufter/borg) [borg](https://github.com/crufter/borg) - Terminal based search engine for bash snippets.
* <code>&nbsp;&nbsp;1362</code> ![](https://img.shields.io/github/last-commit/documize/community) [Documize](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools.
* <code>&nbsp;&nbsp;&nbsp;886</code> ![](https://img.shields.io/github/last-commit/shurcooL/Go-Package-Store) [Go Package Store](https://github.com/shurcooL/Go-Package-Store) - App that displays updates for the Go packages in your GOPATH.
* <code>&nbsp;&nbsp;&nbsp;818</code> ![](https://img.shields.io/github/last-commit/VerizonDigital/vflow) [vFlow](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector.
* <code>&nbsp;&nbsp;&nbsp;804</code> ![](https://img.shields.io/github/last-commit/pointlander/peg) [peg](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator.
* <code>&nbsp;&nbsp;&nbsp;802</code> ![](https://img.shields.io/github/last-commit/0xERR0R/blocky) [blocky](https://github.com/0xERR0R/blocky) - Fast and lightweight DNS proxy as ad-blocker for local network with many features.
* <code>&nbsp;&nbsp;&nbsp;790</code> ![](https://img.shields.io/github/last-commit/msoap/shell2http) [shell2http](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control).
* <code>&nbsp;&nbsp;&nbsp;706</code> ![](https://img.shields.io/github/last-commit/jeffail/leaps) [Leaps](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms.
* <code>&nbsp;&nbsp;&nbsp;626</code> ![](https://img.shields.io/github/last-commit/Antonito/gfile) [gfile](https://github.com/Antonito/gfile) - Securely transfer files between two computers, without any third party, over WebRTC.
* <code>&nbsp;&nbsp;&nbsp;546</code> ![](https://img.shields.io/github/last-commit/moshebe/gebug) [Gebug](https://github.com/moshebe/gebug) - A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly.
* <code>&nbsp;&nbsp;&nbsp;542</code> ![](https://img.shields.io/github/last-commit/meloalright/guora) [Guora](https://github.com/meloalright/guora) - A self-hosted Quora like web application written in Go.
* <code>&nbsp;&nbsp;&nbsp;495</code> ![](https://img.shields.io/github/last-commit/quii/mockingjay-server) [mockingjay](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests.
* <code>&nbsp;&nbsp;&nbsp;492</code> ![](https://img.shields.io/github/last-commit/goccmack/gocc) [gocc](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go.
* <code>&nbsp;&nbsp;&nbsp;433</code> ![](https://img.shields.io/github/last-commit/Sioro-Neoku/go-peerflix) [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client.
* <code>&nbsp;&nbsp;&nbsp;328</code> ![](https://img.shields.io/github/last-commit/dimiro1/ipe) [ipe](https://github.com/dimiro1/ipe) - Open source Pusher server implementation compatible with Pusher client libraries written in GO.
* <code>&nbsp;&nbsp;&nbsp;316</code> ![](https://img.shields.io/github/last-commit/thestrukture/ide) [ide](https://github.com/thestrukture/ide) - Browser accessible IDE. Designed for Go with Go.
* <code>&nbsp;&nbsp;&nbsp;301</code> ![](https://img.shields.io/github/last-commit/mehrdadrad/tcpprobe) [tcpprobe](https://github.com/mehrdadrad/tcpprobe) - TCP tool for network performance and path monitoring, including socket statistics.
* <code>&nbsp;&nbsp;&nbsp;297</code> ![](https://img.shields.io/github/last-commit/wellington/wellington) [wellington](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass).
* <code>&nbsp;&nbsp;&nbsp;248</code> ![](https://img.shields.io/github/last-commit/get-woke/woke) [woke](https://github.com/get-woke/woke) - Detect non-inclusive language in your source code.
* <code>&nbsp;&nbsp;&nbsp;246</code> ![](https://img.shields.io/github/last-commit/rafael-santiago/cherry) [Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go.
* <code>&nbsp;&nbsp;&nbsp;166</code> ![](https://img.shields.io/github/last-commit/assafmo/joincap) [joincap](https://github.com/assafmo/joincap) - Command-line utility for merging multiple pcap files together.
* <code>&nbsp;&nbsp;&nbsp;154</code> ![](https://img.shields.io/github/last-commit/gulien/orbit) [Orbit](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates.
* <code>&nbsp;&nbsp;&nbsp;150</code> ![](https://img.shields.io/github/last-commit/mehrdadrad/tcpdog) [tcpdog](https://github.com/mehrdadrad/tcpdog) - eBPF based TCP observability.
* <code>&nbsp;&nbsp;&nbsp;117</code> ![](https://img.shields.io/github/last-commit/lingrino/vaku) [vaku](https://github.com/lingrino/vaku) - CLI & API for folder-based functions in Vault like copy, move, and search.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;82</code> ![](https://img.shields.io/github/last-commit/scryinfo/dp) [dp](https://github.com/scryinfo/dp) - Through SDK for data exchange with blockchain, developers can get easy access to DAPP development.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;75</code> ![](https://img.shields.io/github/last-commit/tejo/boxed) [boxed](https://github.com/tejo/boxed) - Dropbox based blog engine.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> ![](https://img.shields.io/github/last-commit/unix4fun/naclpipe) [naclpipe](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> ![](https://img.shields.io/github/last-commit/crazcalm/term-quiz) [term-quiz](https://github.com/crazcalm/term-quiz) - Quizzes for your terminal.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/lucasgomide/snitch) [Snitch](https://github.com/lucasgomide/snitch) - Simple way to notify your team and many tools when someone has deployed any application via Tsuru.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/diankong/GoDocTooltip) [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at function list.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code> ![](https://img.shields.io/github/last-commit/dnnrly/hoofli) [hoofli](https://github.com/dnnrly/hoofli) - Generate PlantUML diagrams from Chrome or Firefox network inspections.
* [Docker](http://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
* [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
* [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
* [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
* [limetext](https://limetext.github.io) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* [hugo](http://gohugo.io/) - Fast and Modern Static Website Engine.
* [Better Go Playground](https://goplay.tools) - Go playground with syntax highlight, code completion and other features.
* [GoLand](https://jetbrains.com/go) - Full featured cross-platform Go IDE.

# Resources

*Where to discover new Go libraries.*

## Benchmarks

* <code>&nbsp;&nbsp;1519</code> ![](https://img.shields.io/github/last-commit/smallnest/go-web-framework-benchmark) [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark.
* <code>&nbsp;&nbsp;1511</code> ![](https://img.shields.io/github/last-commit/julienschmidt/go-http-routing-benchmark) [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison.
* <code>&nbsp;&nbsp;1186</code> ![](https://img.shields.io/github/last-commit/alecthomas/go_serialization_benchmarks) [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods.
* <code>&nbsp;&nbsp;&nbsp;989</code> ![](https://img.shields.io/github/last-commit/atemerev/skynet) [skynet](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark.
* <code>&nbsp;&nbsp;&nbsp;211</code> ![](https://img.shields.io/github/last-commit/fawick/speedtest-resize) [speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language.
* <code>&nbsp;&nbsp;&nbsp;139</code> ![](https://img.shields.io/github/last-commit/tylertreat/go-benchmarks) [go-benchmarks](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches.
* <code>&nbsp;&nbsp;&nbsp;106</code> ![](https://img.shields.io/github/last-commit/feyeleanor/GoSpeed) [gospeed](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;91</code> ![](https://img.shields.io/github/last-commit/davecheney/autobench) [autobench](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> ![](https://img.shields.io/github/last-commit/tyler-smith/golang-sql-benchmark) [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;57</code> ![](https://img.shields.io/github/last-commit/PuerkitoBio/gocostmodel) [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> ![](https://img.shields.io/github/last-commit/mrLSD/go-benchmark-app) [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> ![](https://img.shields.io/github/last-commit/jimrobinson/kvbench) [kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> ![](https://img.shields.io/github/last-commit/nikolaydubina/go-ml-benchmarks) [go-ml-benchmarks](https://github.com/nikolaydubina/go-ml-benchmarks) - benchmarks for machine learning inference in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/zerosnake0/go-json-benchmark) [go-json-benchmark](https://github.com/zerosnake0/go-json-benchmark) - Go JSON benchmark.

## Conferences

* [Capital Go](http://www.capitalgolang.com) - Washington, D.C., USA.
* [dotGo](http://www.dotgo.eu) - Paris, France.
* [GoCon](http://gocon.connpass.com/) - Tokyo, Japan.
* [GoDays](https://www.godays.io/) - Berlin, Germany.
* [GoLab](http://golab.io/) - Florence, Italy.
* [GolangUK](http://golanguk.com/) - London, UK.
* [GopherChina](http://gopherchina.org) - Shanghai, China.
* [GopherCon](http://www.gophercon.com/) - Denver, USA.
* [GopherCon Australia](https://gophercon.com.au/) - Sydney, Australia.
* [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, BR.
* [GopherCon Europe](https://gophercon.is/) - Berlin, Germany.
* [GopherCon India](https://www.gophercon.in/) - Pune, India.
* [GopherCon Israel](https://www.gophercon.org.il/) - Tel Aviv, Israel.
* [GopherCon Russia](https://www.gophercon-russia.ru) - Moscow, Russia.
* [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore.
* [GopherCon Vietnam](https://gophercon.vn/) - Ho Chi Minh City, Vietnam.
* [GothamGo](http://gothamgo.com/) - New York City, USA.
* [GoWayFest](https://goway.io/) - Minsk, Belarus.

## E-Books

* <code>&nbsp;&nbsp;9798</code> ![](https://img.shields.io/github/last-commit/dariubs/GoBooks) [GoBooks](https://github.com/dariubs/GoBooks) - A curated list of Go books.
* <code>&nbsp;&nbsp;7964</code> ![](https://img.shields.io/github/last-commit/polaris1119/The-Golang-Standard-Library-by-Example) [The Golang Standard Library by Example (Chinese)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example)
* <code>&nbsp;&nbsp;2831</code> ![](https://img.shields.io/github/last-commit/thewhitetulip/web-dev-golang-anti-textbook) [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)
* <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> ![](https://img.shields.io/github/last-commit/thedevsir/gosuccinctly) [Go Succinctly](https://github.com/thedevsir/gosuccinctly) - in Persian.
* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [Go 101](https://go101.org) - A book focusing on Go syntax/semantics and all kinds of details.
* [Go Bootcamp](http://golangbootcamp.com)
* [For the Love of Go](https://bitfieldconsulting.com/books) - A series of introductory books for Go beginners.
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [How To Code in Go eBook](https://www.digitalocean.com/community/books/how-to-code-in-go-ebook) - A 600 page introduction to Go aimed at first time developers.
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [Practical Go Lessons](https://www.practical-go-lessons.com/)
* [Spaceship Go A Journey to the Standard Library](https://blasrodri.github.io/spaceship-go-gh-pages/)
* [The Go Programming Language](http://www.gopl.io/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Writing A Compiler In Go](https://compilerbook.com)
* [Writing An Interpreter In Go](https://interpreterbook.com)

## Gophers

* <code>&nbsp;&nbsp;2476</code> ![](https://img.shields.io/github/last-commit/ashleymcnamara/gophers) [gophers](https://github.com/ashleymcnamara/gophers) - Gopher artworks by Ashley McNamara.
* <code>&nbsp;&nbsp;2416</code> ![](https://img.shields.io/github/last-commit/egonelbre/gophers) [gophers](https://github.com/egonelbre/gophers) - Free gophers.
* <code>&nbsp;&nbsp;2276</code> ![](https://img.shields.io/github/last-commit/MariaLetta/free-gophers-pack) [Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack) - Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster.
* <code>&nbsp;&nbsp;&nbsp;589</code> ![](https://img.shields.io/github/last-commit/shalakhin/gophericons) [gophericons](https://github.com/shalakhin/gophericons)
* <code>&nbsp;&nbsp;&nbsp;511</code> ![](https://img.shields.io/github/last-commit/matryer/gopherize.me) [gopherize.me](https://github.com/matryer/gopherize.me) - Gopherize yourself.
* <code>&nbsp;&nbsp;&nbsp;506</code> ![](https://img.shields.io/github/last-commit/tenntenn/gopher-stickers) [gopher-stickers](https://github.com/tenntenn/gopher-stickers)
* <code>&nbsp;&nbsp;&nbsp;386</code> ![](https://img.shields.io/github/last-commit/golang-samples/gopher-vector) [gopher-vector](https://github.com/golang-samples/gopher-vector)
* <code>&nbsp;&nbsp;&nbsp;&nbsp;96</code> ![](https://img.shields.io/github/last-commit/sillecelik/go-gopher) [gophers](https://github.com/sillecelik/go-gopher) - Gopher amigurumi toy pattern.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;92</code> ![](https://img.shields.io/github/last-commit/GolangUA/gopher-logos) [gopher-logos](https://github.com/GolangUA/gopher-logos) - adorable gopher logos.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> ![](https://img.shields.io/github/last-commit/rogeralsing/gophers) [gophers](https://github.com/rogeralsing/gophers) - random gopher graphics.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> ![](https://img.shields.io/github/last-commit/keygx/Go-gopher-Vector) [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) - Go gopher Vector Data [.ai, .svg].

## Meetups

* [Basel Go Meetup](https://www.meetup.com/Basel-Go-Meetup/)
* [Belfast Gophers](https://www.meetup.com/Belfast-Gophers/)
* [Berlin Golang](https://www.meetup.com/golang-users-berlin/)
* [Brisbane Gophers](https://www.meetup.com/Brisbane-Golang-Meetup/)
* [Canberra Gophers](https://www.meetup.com/Canberra-Gophers/)
* [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
* [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
* [Go Remote Meetup](https://www.meetup.com/Go-Remote-Meetup/)
* [Go Toronto](https://www.meetup.com/go-toronto/)
* [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
* [GoBandung](https://www.meetup.com/GoBandung/)
* [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
* [GoCracow - Krakow, Poland](https://www.meetup.com/GoCracow/)
* [GoJakarta](https://www.meetup.com/GoJakarta/)
* [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
* [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
* [Golang Baltimore, MD](https://www.meetup.com/BaltimoreGolang/)
* [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
* [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
* [Golang Boston](https://www.meetup.com/bostongo/)
* [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
* [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
* [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
* [Golang Curitiba - Brazil](https://www.meetup.com/GolangCWB/)
* [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
* [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
* [Golang Estonia](https://www.meetup.com/Golang-Estonia/)
* [Golang Gurgaon, India](https://www.meetup.com/Gurgaon-Go-Meetup/)
* [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
* [Golang Israel](https://www.meetup.com/Go-Israel/)
* [Golang Joinville - Brazil](https://www.meetup.com/Joinville-Go-Meetup/)
* [Golang Kathmandu](https://www.meetup.com/Golang-Kathmandu/)
* [Golang Korea](https://www.meetup.com/GDG-Golang-Korea/)
* [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
* [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
* [Golang Marseille](https://www.meetup.com/fr-FR/Golang-Marseille/)
* [Golang Melbourne](https://www.meetup.com/golang-mel/)
* [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
* [Golang New York](https://www.meetup.com/nycgolang/)
* [Golang North East](https://www.meetup.com/en-AU/Golang-North-East/)
* [Golang Paris](https://www.meetup.com/Golang-Paris/)
* [Golang Poland](https://www.meetup.com/Golang-Poland/)
* [Golang Pune](https://www.meetup.com/Golang-Pune/)
* [Golang Singapore](https://www.meetup.com/golangsg/)
* [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
* [Golang Sydney, AU](https://www.meetup.com/golang-syd/)
* [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
* [Golang Taipei](https://www.meetup.com/golang-taipei-meetup/)
* [Golang Turkey](https://kommunity.com/goturkiye)
* [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
* [Golang Vienna, Austria](https://www.meetup.com/viennago/)
* [Golang Казань](https://www.meetup.com/GolangKazan/)
* [Golang Москва](https://www.meetup.com/Golang-Moscow/)
* [Golang Питер](https://www.meetup.com/Golang-Peter/)
* [GoSF - San Francisco, CA](https://www.meetup.com/golangsf)
* [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
* [Seattle Go Programmers](https://www.meetup.com/golang/)
* [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
* [Utah Go User Group](https://www.meetup.com/utahgophers/)
* [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)

*Add the group of your city/country here (send **PR**)*

## Style Guides

* <code>&nbsp;21344</code> ![](https://img.shields.io/github/last-commit/cockroachdb/cockroach) [CockroachDB](https://github.com/cockroachdb/cockroach/blob/master/docs/style.md)
* <code>&nbsp;12145</code> ![](https://img.shields.io/github/last-commit/hyperledger/fabric) [Hyperledger](https://github.com/hyperledger/fabric/blob/release-1.4/docs/source/style-guides/go-style.rst)
* <code>&nbsp;&nbsp;9339</code> ![](https://img.shields.io/github/last-commit/uber-go/guide) [Uber](https://github.com/uber-go/guide/blob/master/style.md)
* <code>&nbsp;&nbsp;2534</code> ![](https://img.shields.io/github/last-commit/boramalper/magnetico) [Magnetico](https://github.com/boramalper/magnetico/wiki/magnetico-Design-Specification)
* <code>&nbsp;&nbsp;1100</code> ![](https://img.shields.io/github/last-commit/bahlo/go-styleguide) [bahlo/go-styleguide](https://github.com/bahlo/go-styleguide)
* [GitLab](https://docs.gitlab.com/ee/development/go_guide/)
* [Sourcegraph](https://about.sourcegraph.com/handbook/engineering/go_style_guide)
* [Thanos](https://thanos.io/tip/contributing/coding-style-guide.md/)

## Social Media

### Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangch](https://twitter.com/golangch)
* [@golangflow](https://twitter.com/golangflow)
* [@golangweekly](https://twitter.com/golangweekly)

### Reddit
* [r/golang](https://www.reddit.com/r/golang/)

## Websites

* <code>&nbsp;88458</code> ![](https://img.shields.io/github/last-commit/golang/go) [Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki.
* <code>&nbsp;27862</code> ![](https://img.shields.io/github/last-commit/bayandin/awesome-awesomeness) [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists.
* <code>&nbsp;20759</code> ![](https://img.shields.io/github/last-commit/lukasz-madon/awesome-remote-job) [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them are looking for Go hackers.
* <code>&nbsp;&nbsp;&nbsp;140</code> ![](https://img.shields.io/github/last-commit/mholt/golang-graphics) [golang-graphics](https://github.com/mholt/golang-graphics) - Collection of Go images, graphics, and art.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> ![](https://img.shields.io/github/last-commit/ninedraft/gocryforhelp) [gocryforhelp](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> ![](https://img.shields.io/github/last-commit/xwjdsh/awesome-go-extra) [awesome-go-extra](https://github.com/xwjdsh/awesome-go-extra) - Parse awesome-go README file and generate a new README file with repo info.
* [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
* [Go Code Club](https://www.youtube.com/watch?v=nvoIPQYdx9g&list=PLEcwzBXTPUE_YQR7R0BRtHBYJ0LN3Y0i3) - A group of Gophers read and discuss a different Go project every week.
* [Go Community on Hashnode](https://hashnode.com/n/go) - Community of Gophers on Hashnode.
* [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
* [Go In 5 Minutes](https://www.goin5minutes.com/) - 5 minute screencasts focused on getting one thing done.
* [Go Challenge](http://golang-challenge.org/) - Learn Go by solving problems and getting feedback from Go experts.
* [Go Report Card](https://goreportcard.com) - A report card for your Go package.
* [go.dev](https://go.dev/) - A hub for Go developers.
* [Go Blog](http://blog.golang.org) - The official Go blog.
* [godoc.org](https://godoc.org/) - Documentation for open source Go packages.
* [Golang Developer Jobs](https://golangjob.xyz) - Developer Jobs exclusivly for Golang related Roles.
* [Golang Flow](https://golangflow.io) - Post Updates, News, Packages and more.
* [Golang News](https://golangnews.com) - Links and news about Go programming.
* [Golang Resources](https://golangresources.com) - A curation of the best articles, exercises, talks and videos to learn Go.
* [CodinGame](https://www.codingame.com/) - Learn Go by solving interactive tasks using small games as practical examples.
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
* [Gophercises](https://gophercises.com/) - Free coding exercises for budding gophers.
* [gowalker.org](https://gowalker.org) - Go Project API documentation.
* [json2go](https://m-zajac.github.io/json2go) - Advanced JSON to Go struct conversion - online tool.
* [justforfunc](https://www.youtube.com/c/justforfunc) - Youtube channel dedicated to Go programming language tips and tricks, hosted by Francesc Campoy [@francesc](https://twitter.com/francesc).
* [Learn Go Programming](https://blog.learngoprogramming.com) - Learn Go concepts with illustrations.
* [Lille Gophers](https://lille-gophers.loscrackitos.codes/) - Golang talks community in Lille, France ([@LilleGophers](https://twitter.com/LilleGophers)).
* [Made with Golang](https://madewithgolang.com/?ref=awesome-go)
* [r/Golang](https://www.reddit.com/r/golang) - News about Go.
* [studygolang](https://studygolang.com) - The community of studygolang in China.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.
* [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

### Tutorials

* <code>&nbsp;38302</code> ![](https://img.shields.io/github/last-commit/astaxie/build-web-application-with-golang) [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang.
* <code>&nbsp;15927</code> ![](https://img.shields.io/github/last-commit/tmrts/go-patterns) [go-patterns](https://github.com/tmrts/go-patterns) - Curated list of Go design patterns, recipes and idioms.
* <code>&nbsp;14992</code> ![](https://img.shields.io/github/last-commit/quii/learn-go-with-tests) [Learn Go with TDD](https://github.com/quii/learn-go-with-tests) - Learn Go with test-driven development.
* <code>&nbsp;10662</code> ![](https://img.shields.io/github/last-commit/inancgumus/learngo) [Learn Go with 1000+ Exercises](https://github.com/inancgumus/learngo) - Learn Go with thousands of examples, exercises, and quizzes.
* <code>&nbsp;&nbsp;5695</code> ![](https://img.shields.io/github/last-commit/a8m/go-lang-cheat-sheet) [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card.
* <code>&nbsp;&nbsp;2473</code> ![](https://img.shields.io/github/last-commit/miguelmota/golang-for-nodejs-developers) [Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) - Examples of Golang compared to Node.js for learning.
* <code>&nbsp;&nbsp;1161</code> ![](https://img.shields.io/github/last-commit/mkaz/working-with-go) [Working with Go](https://github.com/mkaz/working-with-go) - Intro to go for experienced programmers.
* <code>&nbsp;&nbsp;&nbsp;886</code> ![](https://img.shields.io/github/last-commit/miguelmota/ethereum-development-with-go-book) [Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) - A little e-book on Ethereum Development with Go.
* <code>&nbsp;&nbsp;&nbsp;266</code> ![](https://img.shields.io/github/last-commit/bnkamalesh/goapp) [goapp](https://github.com/bnkamalesh/goapp) - An opinionated guideline to structure & develop a Go web application/service.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;56</code> ![](https://img.shields.io/github/last-commit/shubhamzanwar/design-patterns) [Design Patterns in Go](https://github.com/shubhamzanwar/design-patterns) - Collection of programming design patterns implemented in Go.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code> ![](https://img.shields.io/github/last-commit/haveyoudebuggedit/go-patterns) [Debugged.it Go patterns](https://github.com/haveyoudebuggedit/go-patterns) - Advanced Go patterns with ready-to-run examples.
* [50 Shades of Go](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - Traps, Gotchas, and Common Mistakes for New Golang Devs.
* [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
* [Games With Go](http://gameswithgo.org/) - A video series teaching programming and game development.
* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
* [Go Playground for iOS](https://codeplayground.app) - Interactively edit & play Go snippets on your mobile device.
* [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
* [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - How to cancel MySQL queries.
* [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) - How to cache slow database queries.
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
* [GolangCode](https://golangcode.com/) - Collection of code snippets and tutorials to help tackle every day issues.
* [GopherSnippets](https://gophersnippets.com/) - Code snippets with tests and testable examples for the Go programming language.
* [Hackr.io](https://hackr.io/tutorials/learn-golang) - Learn Go from the best online golang tutorials submitted & voted by the golang programming community.
* [How to Benchmark: dbq vs sqlx vs GORM](https://medium.com/@rocketlaunchr.cloud/how-to-benchmark-dbq-vs-sqlx-vs-gorm-e814caacecb5) - Learn how to benchmark in Go. As a case-study, we will benchmark dbq, sqlx and GORM.
* [How To Deploy a Go Web Application with Docker](https://semaphoreci.com/community/tutorials/how-to-deploy-a-go-web-application-with-docker) - Learn how to use Docker for Go development and how to build production Docker images.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
* [Building and Testing a REST API in Go with Gorilla Mux and PostgreSQL](https://semaphoreci.com/community/tutorials/building-and-testing-a-rest-api-in-go-with-gorilla-mux-and-postgresql) - We’ll write an API with the help of the powerful Gorilla Mux.
* [A Tour of Go](http://tour.golang.org/) - Interactive tour of Go.
* [Learning Golang - From zero to hero](https://milapneupane.com.np/2019/07/06/learning-golang-from-zero-to-hero/) - Getting started with golang for beginner.
* [package main](https://www.youtube.com/packagemain) - YouTube channel about Programming in Go.
* [Programming with Google Go](https://www.coursera.org/specializations/google-golang) - Coursera Specialization to learn about Go from scratch.
* [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
* [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) - Building a Golang site for e-commerce (demo included).
* [Your basic Go](http://yourbasic.org/golang) - Huge collection of tutorials and how to's.
