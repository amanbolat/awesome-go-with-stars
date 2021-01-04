### Contents

- [Awesome Go](#awesome-go)
  - [Audio and Music](#audio-and-music)
  - [Authentication and OAuth](#authentication-and-oauth)
  - [Bot Building](#bot-building)
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

* `   142` [flac](https://github.com/mewkiz/flac) - Native Go FLAC encoder/decoder with support for FLAC streams.
* `    77` [gaad](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser.
* `   117` [go-sox](https://github.com/krig/go-sox) - libsox bindings for go.
* `    98` [GoAudio](https://github.com/DylanMeeus/GoAudio) - Native Go Audio Processing Library.
* `    10` [gosamplerate](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go.
* `   175` [id3v2](https://github.com/bogem/id3v2) - ID3 decoding and encoding library for Go.
* `   133` [malgo](https://github.com/gen2brain/malgo) - Mini audio library.
* `    52` [minimp3](https://github.com/tosone/minimp3) - Lightweight MP3 decoder library.
* `   136` [mix](https://github.com/go-mix/mix) - Sequence-based Go-native audio mixer for music apps.
* `   113` [mp3](https://github.com/tcolgate/mp3) - Native Go MP3 decoder.
* `   328` [music-theory](https://github.com/go-music-theory/music-theory) - Music theory models in Go.
* `   721` [Oto](https://github.com/hajimehoshi/oto) - A low-level library to play sound on multiple platforms.
* `   422` [PortAudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library.
* `   252` [portmidi](https://github.com/rakyll/portmidi) - Go bindings for PortMidi.
* `    28` [vorbis](https://github.com/mccoyst/vorbis) - "Native" Go Vorbis decoder (uses CGO, but has no dependencies).
* `   318` [waveform](https://github.com/mdlayher/waveform) - Go package capable of generating waveform images from audio streams.

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

* `  2500` [authboss](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time.
* `   143` [branca](https://github.com/hako/branca) - Golang implementation of Branca Tokens.
* `  8391` [casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC.
* `     6` [cookiestxt](https://github.com/mengzhuo/cookiestxt) - provides parser of cookies.txt file format.
* `     9` [go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) - Golang library for providing a canonical representation of email address.
* `   147` [go-guardian](https://github.com/shaj13/go-guardian) - Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token and Certificate based authentication.
* `  1692` [go-jose](https://github.com/square/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.
* `  1681` [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - Standalone, specification-compliant, OAuth2 server written in Golang.
* `  1319` [gologin](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers.
* `  1121` [gorbac](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang.
* `  2995` [goth](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box.
* `   197` [httpauth](https://github.com/goji/httpauth) - HTTP Authentication middleware.
* `   222` [jeff](https://github.com/abraithwaite/jeff) - Simple, flexible, secure and idiomatic web session management with pluggable backends.
* `    88` [jwt](https://github.com/robbert229/jwt) - Clean and easy to use implementation of JSON Web Tokens (JWT).
* `   236` [jwt](https://github.com/pascaldekloe/jwt) - Lightweight JSON Web Token (JWT) library.
* `   193` [jwt](https://github.com/cristalhq/jwt) - Safe, simple and fast JSON Web Tokens for Go.
* `   200` [jwt-auth](https://github.com/adam-hanna/jwt-auth) - JWT middleware for Golang http servers with many configuration options.
* `  8837` [jwt-go](https://github.com/dgrijalva/jwt-go) - Golang implementation of JSON Web Tokens (JWT).
* `  1721` [loginsrv](https://github.com/tarent/loginsrv) - JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam.
* `  3430` [oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support.
* `  1639` [osin](https://github.com/openshift/osin) - Golang OAuth2 server library.
* `    13` [otpgo](https://github.com/jltorresm/otpgo) - Time-Based One-Time Password (TOTP) and HMAC-Based One-Time Password (HOTP) library for Go.
* `   410` [paseto](https://github.com/o1egl/paseto) - Golang implementation of Platform-Agnostic Security Tokens (PASETO).
* `   414` [permissions2](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt.
* `    70` [rbac](https://github.com/zpatrick/rbac) - Minimalistic RBAC package for Go applications.
* [scope](https://github.com/SonicRoshan/scope) - Easily Manage OAuth2 Scopes In Go.
* `   817` [scs](https://github.com/alexedwards/scs) - Session Manager for HTTP servers.
* `    42` [securecookie](https://github.com/chmike/securecookie) - Efficient secure cookie encoding/decoding.
* `   104` [session](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE).
* `     9` [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) - Go session management using the SessionGate Redis module.
* `    56` [sessions](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers.
* `   104` [sessionup](https://github.com/swithek/sessionup) - Simple, yet effective HTTP session management and identification package.
* `    76` [sjwt](https://github.com/brianvoe/sjwt) - Simple jwt generator and parser.

## Bot Building

*Libraries for building and working with bots.*

* `    38` [ephemeral-roles](https://github.com/ewohltman/ephemeral-roles) - A Discord bot for managing ephemeral roles based upon voice channel member presence.
* `   641` [go-chat-bot](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go.
* [go-joe](https://joe-bot.net) - A general-purpose bot library inspired by Hubot but written in Go.
* `   186` [go-sarah](https://github.com/oklahomer/go-sarah) - Framework to build bot for desired chat services including LINE, Slack, Gitter and more.
* `   102` [go-tgbot](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware.
* `   141` [go-twitch-irc](https://github.com/gempir/go-twitch-irc) - Libary to write bots for twitch.tv chat
* `   375` [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) - A golang implementation of a console-based trading bot for cryptocurrency exchanges.
* `    34` [govkbot](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library.
* `   127` [hanu](https://github.com/sbstjn/hanu) - Framework for writing Slack bots.
* `   448` [Kelp](https://github.com/stellar/kelp) - official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies.
* `    64` [margelet](https://github.com/zhulik/margelet) - Framework for building Telegram bots.
* `    18` [micha](https://github.com/onrik/micha) - Go Library for Telegram bot api.
* `  2737` [olivia](https://github.com/olivia-ai/olivia) - A chatbot built with an artificial neural network.
* `   479` [slacker](https://github.com/shomali11/slacker) - Easy to use framework to create Slack bots.
* `    36` [slackscot](https://github.com/alexandre-normand/slackscot) - Another framework for building Slack bots.
* `   297` [tbot](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http.
* `  1602` [telebot](https://github.com/tucnak/telebot) - Telegram bot framework written in Go.
* `  2571` [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client.
* `   169` [Tenyks](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging.

## Command Line

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* `    84` [1build](https://github.com/gopinath-langote/1build) - Command line tool to frictionlessly manage project-specific commands.
* `   262` [argparse](https://github.com/akamensky/argparse) - Command line argument parser inspired by Python's argparse module.
* `    27` [argv](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax.
* `   548` [cli](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang struct tags.
* `    77` [cli](https://github.com/teris-io/cli) - Simple and complete API for building command line interfaces in Go.
* `   177` [climax](http://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.
* `    57` [clîr](https://github.com/leaanthony/clir) - A Simple and Clear CLI library. Dependency free.
* `    30` [cmd](https://github.com/posener/cmd) - Extends the standard `flag` package to support sub commands and more in idomatic way.
* `    50` [cmdr](https://github.com/hedzr/cmdr) - A POSIX/GNU style, getopt-like command-line UI Go library.
* ` 19880` [cobra](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions.
* `   142` [commandeer](https://github.com/jaffee/commandeer) - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags.
* `   744` [complete](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion.
* `  1965` [Dnote](https://github.com/dnote/dnote) - A simple command line notebook with multi-device sync.
* `    71` [env](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs.
* `   110` [flag](https://github.com/cosiner/flag) - Simple but powerful command line option parsing library for Go supporting subcommand.
* `   706` [flaggy](https://github.com/integrii/flaggy) - A robust and idiomatic flags package with excellent subcommand support.
* `    36` [flagvar](https://github.com/sgreben/flagvar) - A collection of flag argument types for Go's standard `flag` package.
* `  1014` [go-arg](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go.
* `    20` [go-commander](https://github.com/yitsushi/go-commander) - Go library to simplify CLI workflow.
* `  1839` [go-flags](https://github.com/jessevdk/go-flags) - go command line option parser.
* `    31` [go-getoptions](https://github.com/DavidGamba/go-getoptions) - Go option parser inspired on the flexibility of Perl’s GetOpt::Long.
* `    47` [gocmd](https://github.com/devfacet/gocmd) - Go library for building command line applications.
* `   142` [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - cli application framework with auto configuration and dependency injection.
* `    93` [job](https://github.com/liujianping/job) - JOB, make your short-term command as a long-term job.
* `  2988` [kingpin](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands.
* `   743` [liner](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces.
* `  1245` [mitchellh/cli](https://github.com/mitchellh/cli) - Go library for implementing command-line interfaces.
* `   714` [mow.cli](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation.
* `   533` [ops](https://github.com/nanovms/ops) - Unikernel Builder/Orchestrator.
* `  1330` [pflag](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.
* `    11` [sand](https://github.com/Zaba505/sand) - Simple API for creating interpreters and so much more.
* `   122` [sflags](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries.
* `    40` [strumt](https://github.com/antham/strumt) - Library to create prompt chain.
* `    12` [ts](https://github.com/liujianping/ts) - Timestamp convert & compare tool.
* `   106` [ukautz/clif](https://github.com/ukautz/clif) - Small command line interface framework.
* ` 15040` [urfave/cli](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).
* `    44` [wlog](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency.
* `   125` [wmenu](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompts users to make choices.

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* `  1515` [asciigraph](https://github.com/guptarohit/asciigraph) - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies.
* `  1009` [aurora](https://github.com/logrusorgru/aurora) - ANSI terminal colors that supports fmt.Printf/Sprintf.
* [cfmt](https://github.com/mingrammer/cfmt) - Contextual fmt inspired by bootstrap color classes.
* `    19` [cfmt](https://github.com/i582/cfmt) - Simple and convenient formatted stylized output fully compatible with fmt library.
* `   357` [chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output.
* `    22` [colourize](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals.
* `    28` [ctc](https://github.com/wzshiming/ctc) - The non-invasive cross-platform terminal color library does not need to modify the Print method.
* `     9` [go-ataman](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals.
* `   493` [go-colorable](https://github.com/mattn/go-colorable) - Colorable writer for windows.
* `   206` [go-colortext](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals.
* `   471` [go-isatty](https://github.com/mattn/go-isatty) - isatty for golang.
* `  3616` [go-prompt](https://github.com/c-bata/go-prompt) - Library for building a powerful interactive prompt, inspired by `  6723` [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).
* `  6866` [gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces.
* `   380` [gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text.
* `   639` [gookit/color](https://github.com/gookit/color) - Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows.
* `  1169` [mpb](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications.
* `  1495` [progressbar](https://github.com/schollz/progressbar) - Basic thread-safe progress bar that works in every OS.
* `   383` [pterm](https://github.com/pterm/pterm) - A library to beautify console output on every platform with many combinable components.
* `   280` [simpletable](https://github.com/alexeyco/simpletable) - Simple tables in terminal with Go.
* `   277` [tabby](https://github.com/cheynewallace/tabby) - A tiny library for super simple Golang tables.
* `     1` [table](https://github.com/tomlazar/table) - Small library for terminal color based tables .
* `    49` [tabular](https://github.com/InVisionApp/tabular) - Print ASCII tables from command line utilities without the need to pass large sets of data to the API.
* `  3933` [termbox-go](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces.
* `  1488` [termdash](https://github.com/mum4k/termdash) - Go terminal dashboard based on **termbox-go** and inspired by ` 10488` [termui](https://github.com/gizak/termui).
* ` 10488` [termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by ` 13988` [blessed-contrib](https://github.com/yaronn/blessed-contrib).
* `  1257` [uilive](https://github.com/gosuri/uilive) - Library for updating terminal output in realtime.
* `  1741` [uiprogress](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications.
* `   609` [uitable](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data.
* `   131` [yacspin](https://github.com/theckman/yacspin) - Yet Another CLi Spinner package, for working with terminal spinners.

## Configuration

*Libraries for configuration parsing.*

* `   146` [aconfig](https://github.com/cristalhq/aconfig) - Simple, useful and opinionated config loader.
* `   210` [cleanenv](https://github.com/ilyakaznacheev/cleanenv) - Minimalistic configuration reader (from files, ENV, and wherever you want).
* `    99` [config](https://github.com/golobby/config) - A lightweight yet powerful config package for Go projects.
* `   252` [config](https://github.com/JeremyLoy/config) - Cloud native application configuration. Bind ENV to structs in only two lines.
* `   235` [config](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with environment variables and flags parsing.
* `    37` [configuration](https://github.com/BoRuDar/configuration) - Library for initializing configuration structs from env variables, files, flags and 'default' tag.
* `    55` [configure](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables.
* `    68` [configuro](https://github.com/sherifabdlnaby/configuro) - opinionated configuration loading & validation framework from ENV and Files focused towards 12-Factor compliant applications.
* `   336` [confita](https://github.com/heetch/confita) - Load configuration in cascade from multiple backends into a struct.
* `    18` [conflate](https://github.com/the4thamigo-uk/conflate) - Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema.
* `  1729` [env](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults).
* `    93` [envcfg](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs.
* `    10` [envconf](https://github.com/ian-kent/envconf) - Configuration from environment.
* `   186` [envconfig](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables.
* `    94` [envh](https://github.com/antham/envh) - Helpers to manage environment variables.
* `   139` [fig](https://github.com/kkyr/fig) - Tiny library for reading configuration from a file and from environment variables (with validation & defaults).
* `   138` [gcfg](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections.
* `    18` [genv](https://github.com/sakirsensoy/genv) - Read environment variables easily with dotenv support.
* `    37` [go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) - Go package that fetches parameters from AWS System Manager - Parameter Store.
* `     3` [go-ini](https://github.com/subpop/go-ini) - A Go package that marshals and unmarshals INI-files.
* `     8` [go-ssm-config](https://github.com/ianlopshire/go-ssm-config) - Go utility for loading configuration parameters from AWS SSM (Parameter Store).
* `    29` [go-up](https://github.com/ufoscout/go-up) - A simple configuration library with recursive placeholders resolution and no magic.
* `   145` [goConfig](https://github.com/crgimenes/goConfig) - Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file.
* `  3463` [godotenv](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`).
* `    59` [gofigure](https://github.com/ian-kent/gofigure) - Go application configuration made easy.
* `    35` [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.
* `   188` [gookit/config](https://github.com/gookit/config) - application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge.
* `    74` [harvester](https://github.com/beatlabs/harvester) - Harvester, a easy to use static and dynamic configuration package supportig seeding, env vars and Consul integration.
* `   225` [hjson](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments.
* `    20` [hocon](https://github.com/gurkankaymak/hocon) - Configuration library for working with the HOCON(a human-friendly JSON superset) format, supports features like environment variables, referencing other values, comments and multiple files.
* `    32` [ingo](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file.
* `  2320` [ini](https://github.com/go-ini/ini) - Go package to read and write INI files.
* `   203` [joshbetz/config](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP.
* `  3389` [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - Go library for managing configuration data from environment variables.
* `   281` [koanf](https://github.com/knadh/koanf) - Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line.
* `   589` [konfig](https://github.com/lalamove/konfig) - Composable, observable and performant config handling for Go for the distributed processing era.
* `    28` [mini](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files.
* `     3` [nasermirzaei89/env](https://github.com/nasermirzaei89/env) - Simple useful package for read environment variables.
* `    91` [onion](http://github.com/goraz/onion) - Layer based configuration for Go, Supports JSON, TOML, YAML, properties, etcd, env, and encryption using PGP.
* `   254` [store](https://github.com/tucnak/store) - Lightweight configuration manager for Go.
* `     4` [swap](https://github.com/oblq/swap) - Instantiate/configure structs recursively, based on build environment. (YAML, TOML, JSON and env).
* `     3` [typenv](https://github.com/diegomarangoni/typenv) - Minimalistic, zero dependency, typed environment variables library.
* ` 14353` [viper](https://github.com/spf13/viper) - Go configuration with fangs.
* `    61` [xdg](https://github.com/OpenPeeDeeP/xdg) - Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html).

## Continuous Integration

*Tools for help with continuous integration.*

* `  3213` [CDS](https://github.com/ovh/cds) - Enterprise-Grade CI/CD and DevOps Automation Open Source Platform.
* ` 22323` [drone](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go.
* `    61` [duci](https://github.com/duck8823/duci) - A simple ci server no needs domain specific languages.
* `    50` [gomason](https://github.com/nikogura/gomason) - Test, Build, Sign, and Publish your go binaries from a clean workspace.
* `   672` [goveralls](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system.
* `   105` [overalls](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls.
* `    14` [roveralls](https://github.com/LawrenceWoodman/roveralls) - Recursive coverage testing tool.

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

* `   435` [gcss](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor.
* `   165` [go-libsass](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project.

## Data Structures

*Generic datastructures and algorithms in Go.*

* `   458` [algorithms](https://github.com/shady831213/algorithms) - Algorithms and data structures.CLRS study.
* `   159` [binpacker](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream.
* `    95` [bit](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions.
* `   632` [bitset](https://github.com/willf/bitset) - Go package implementing bitsets.
* `   135` [bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go.
* `    55` [bloom](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation.
* `  1315` [boomfilters](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams.
* `     8` [cmap](https://github.com/lrita/cmap) - a thread-safe concurrent map for go, support using `interface{}` as key and auto scale up shards.
* `    30` [concurrent-writer](https://github.com/free/concurrent-writer) - Highly concurrent drop-in replacement for `bufio.Writer`.
* [conjungo](https://github.com/InVisionApp/conjungo) - A small, powerful and flexible merge library.
* `    52` [count-min-log](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory).
* `    42` [crunch](https://github.com/superwhiskers/crunch) - Go package implementing buffers for handling various datatypes easily.
* `   734` [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go.
* `    22` [deque](https://github.com/edwingeng/deque) - A highly optimized double-ended queue.
* `   194` [deque](https://github.com/gammazero/deque) - Fast ring-buffer deque (double-ended queue).
* `    18` [dict](https://github.com/srfrog/dict) - Python-like dictionaries (dict) for Go.
* `   104` [encoding](https://github.com/zhenjl/encoding) - Integer Compression Libraries for Go.
* `   169` [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree.
* `  5855` [go-datastructures](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures.
* `   244` [go-edlib](https://github.com/hbollon/go-edlib) - Go string comparison and edit distance algorithms library (Levenshtein, LCS, Hamming, Damerau levenshtein, Jaro-Winkler, etc.) compatible with Unicode.
* `    16` [go-ef](https://github.com/amallia/go-ef) - A Go implementation of the Elias-Fano encoding.
* `   327` [go-geoindex](https://github.com/hailocab/go-geoindex) - In-memory geo index.
* `    57` [go-mcache](https://github.com/OrlovEvgeny/go-mcache) - Fast in-memory key:value store/cache library. Pointer caches.
* `   111` [go-rquad](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding.
* `   574` [gocache](https://github.com/eko/gocache) - A complete Go cache library with mutiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more.
* `   120` [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) - Concurrent FIFO queue.
* `  9416` [gods](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.
* `     9` [gofal](https://github.com/xxjwxc/gofal) - fractional api for Go.
* `  1765` [golang-set](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go.
* `    28` [goset](https://github.com/zoumo/goset) - A useful Set collection implementation for Go.
* `   220` [goskiplist](https://github.com/ryszard/goskiplist) - Skip list implementation in Go.
* `   192` [gostl](https://github.com/liyue201/gostl) - Data structure and algorithm library for go, designed to provide functions similar to C++ STL.
* `  1474` [gota](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go.
* `     3` [goterator](https://github.com/yaa110/goterator) - Iterator implementation to provide map and reduce functionalities.
* `    29` [hide](https://github.com/emvi/hide) - ID type with marshalling to/from hash to prevent sending IDs to clients.
* `   223` [hilbert](https://github.com/google/hilbert) - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves.
* `   735` [hyperloglog](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.
* `   129` [iter](https://github.com/disksing/iter) - Go implementation of C++ STL iterators and algorithms.
* `    54` [levenshtein](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.
* `   114` [levenshtein](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go.
* `   284` [mafsa](https://github.com/smartystreets/mafsa) - MA-FSA implementation with Minimal Perfect Hashing.
* `   229` [merkletree](https://github.com/cbergoon/merkletree) - Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures.
* `    13` [mspm](https://github.com/BlackRabbitt/mspm) - Multi-String Pattern Matching Algorithm for information retrieval.
* `    31` [nan](https://github.com/kak-tus/nan) - Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers.
* `    15` [null](https://github.com/emvi/null) - Nullable Go types that can be marshalled/unmarshalled to/from JSON.
* `     5` [parsefields](https://github.com/MonaxGT/parsefields) - Tools for parse JSON-like logs for collecting unique fields and events.
* `    28` [pipeline](https://github.com/hyfather/pipeline) - An implementation of pipelines with fan-in and fan-out.
* `    11` [ptrie](https://github.com/viant/ptrie) - An implementation of prefix tree.
* `    71` [remember-go](https://github.com/rocketlaunchr/remember-go) - A universal interface for caching slow database queries (backed by redis, memcached, ristretto, or in-memory).
* `   111` [ring](https://github.com/TheTannerRyan/ring) - Go implementation of a high performance, thread safe bloom filter.
* `  1062` [roaring](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets.
* `    12` [set](https://github.com/StudioSol/set) - Simple set data structure implementation in Go using LinkedHashMap.
* `   136` [skiplist](https://github.com/MauriceGit/skiplist) - Very fast Go Skiplist implementation.
* `    71` [skiplist](https://github.com/gansidui/skiplist) - Skiplist implementation in Go.
* `     1` [slices](https://github.com/srfrog/slices) - Functions that operate on slices; like `package strings` but adapted to work with slices.
* `    21` [timedmap](https://github.com/zekroTJA/timedmap) - Map with expiring key-value pairs.
* `    10` [treap](https://github.com/perdata/treap) - Persistent, fast ordered map using tree heaps.
* `   513` [trie](https://github.com/derekparker/trie) - Trie implementation in Go.
* `   187` [ttlcache](https://github.com/ReneKroon/ttlcache) - In-memory string-interface{} cache with various time-based expiration options and callbacks.
* `    22` [typ](https://github.com/gurukami/typ) - Null Types, Safe primitive type conversion and fetching value from complex structures.
* `   935` [willf/bloom](https://github.com/willf/bloom) - Go package implementing Bloom filters.

## Database

*Databases implemented in Go.*

* `  8604` [badger](https://github.com/dgraph-io/badger) - Fast key-value store in Go.
* `  3939` [bbolt](https://github.com/etcd-io/bbolt) - An embedded key/value database for Go.
* `    60` [bcache](https://github.com/iwanbk/bcache) - Eventually consistent distributed in-memory cache Go library.
* `  4534` [BigCache](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data.
* `   566` [Bitcask](https://github.com/prologic/bitcask) - Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL).
* [buntdb](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.
* `    73` [cache](https://github.com/akyoto/cache) - In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage.
* `  1431` [cache2go](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts.
* `    36` [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) - BigCache with clustering support and individual item expiration.
* ` 19652` [cockroach](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore.
* `    23` [Coffer](https://github.com/claygod/coffer) - Simple ACID key-value database that supports transactions.
* `    51` [couchcache](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server.
* `  1120` [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) - CovenantSQL is a SQL database on blockchain.
* `    99` [Databunker](https://github.com/paranoidguy/databunker) - Personally identifiable information (PII) storage service built to comply with GDPR and CCPA.
* ` 14578` [dgraph](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database.
* `   992` [diskv](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store.
* `   600` [eliasdb](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.
* `   966` [fastcache](https://github.com/VictoriaMetrics/fastcache) - fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead.
* `  1339` [GCache](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC.
* `  4554` [go-cache](https://github.com/pmylund/go-cache) - In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
* `  4068` [goleveldb](https://github.com/syndtr/goleveldb) - Implementation of the ` 22624` [LevelDB](https://github.com/google/leveldb) key/value database in Go.
* `  9589` [groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
* `  1694` [immudb](https://github.com/codenotary/immudb) - immudb is a lightweight, high-speed immutable database for systems and applications written in Go.
* ` 20237` [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
* `   197` [Kivik](https://github.com/go-kivik/kivik) - Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases.
* `  3504` [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
* `   391` [levigo](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB.
* `   778` [moss](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go.
* `  1457` [nutsdb](https://github.com/xujiajun/nutsdb) - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as list, set, sorted set.
* `   181` [piladb](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures.
* `   675` [pogreb](https://github.com/akrylysov/pogreb) - Embedded key-value store for read-heavy workloads.
* ` 34597` [prometheus](https://github.com/prometheus/prometheus) - Monitoring system and time series database.
* `   280` [pudge](https://github.com/recoilme/pudge) - Fast and simple key/value store written using Go's standard library.
* `  6432` [rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite.
* `   114` [Scribble](https://github.com/nanobox-io/golang-scribble) - Tiny flat file JSON store.
* `    98` [slowpoke](https://github.com/recoilme/slowpoke) - Key-value store with persistence.
* `    14` [tempdb](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items.
* ` 26415` [tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1.
* `  2559` [tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang.
* `    49` [unitdb](https://github.com/unit-io/unitdb) - Fast timeseries database for IoT, realtime messaging applications. Access unitdb with pubsub over tcp or websocket using github.com/unit-io/unitd application.
* `   201` [Vasto](https://github.com/chrislusf/vasto) - A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption.
* `  3483` [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL.

*Database schema migration.*

* `    19` [avro](https://github.com/khezen/avro) - Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes.
* `   109` [darwin](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go.
* `    25` [go-fixtures](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang's excellent built-in database/sql library.
* `    68` [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) - A Go package to help write migrations with go-pg/pg.
* `    31` [gondolier](https://github.com/emvi/gondolier) - Database migration library using struct decorators.
* `  1518` [goose](https://github.com/pressly/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.
* `   539` [gormigrate](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM.
* `  5551` [migrate](https://github.com/golang-migrate/migrate) - Database migrations. CLI and Golang library.
* `   106` [migrator](https://github.com/lopezator/migrator) - Dead simple Go database migration library.
* `    24` [pravasan](https://github.com/pravasan/pravasan) - Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc.
* `     6` [schema](https://github.com/adlio/schema) - Library to embed schema migrations for database/sql-compatible databases inside your Go binaries.
* `   805` [skeema](https://github.com/skeema/skeema) - Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools.
* `  1002` [soda](https://github.com/gobuffalo/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* `  1995` [sql-migrate](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata.

*Database tools.*

* `     6` [bucket](https://github.com/PumpkinSeed/bucket) - Optimized data structure framework for Couchbase specialized on one bucket usage.
* `   526` [chproxy](https://github.com/Vertamedia/chproxy) - HTTP proxy for ClickHouse database.
* `   244` [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) - Collects small insterts and sends big requests to ClickHouse servers.
* `    28` [datagen](https://github.com/codingconcepts/datagen) - A fast data generator that's multi-table aware and supports multi-row DML.
* `    48` [dbbench](https://github.com/sj14/dbbench) - Database benchmarking tool with support for several databases and scripts.
* `  2778` [go-mysql](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication.
* `  3290` [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically.
* `  5504` [kingshard](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang.
* `   169` [myreplication](https://github.com/2tvenom/myreplication) - MySql binary log replication listener. Supports statement and row based replication.
* `   109` [octillery](https://github.com/knocknote/octillery) - Go package for sharding databases ( Supports every ORM or raw SQL ).
* `  3885` [orchestrator](https://github.com/github/orchestrator) - MySQL replication topology manager & visualizer.
* `   341` [pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) - Advanced scheduling for PostgreSQL.
* `  6717` [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser.
* `    27` [prep](https://github.com/hexdigest/prep) - Use prepared SQL statements without changing your code.
* `  2515` [pREST](https://github.com/nuveo/prest) - Serve a RESTful API from any PostgreSQL database.
* `    11` [rwdb](https://github.com/andizzle/rwdb) - rwdb provides read replica capability for multiple database servers setup.
* ` 11189` [vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.

*SQL query builder, libraries for building and using SQL.*

* `    25` [buildsqlx](https://github.com/arthurkushman/buildsqlx) - Go database query builder library for PostgreSQL.
* `   252` [dbq](https://github.com/rocketlaunchr/dbq) - Zero boilerplate database operations for Go.
* `   567` [Dotsql](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use them with ease.
* `  1135` [gendry](https://github.com/didi/gendry) - Non-invasive SQL builder and powerful data binder.
* `    51` [godbal](https://github.com/xujiajun/godbal) - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily.
* `   926` [goqu](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library.
* `    15` [gosql](https://github.com/twharmon/gosql) - SQL Query builder with better null values support.
* [hasql](https://golang.yandex/hasql) - Library for accessing multi-host SQL database installations.
* `    83` [igor](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.
* `   343` [jet](https://github.com/go-jet/jet) - Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure.
* `     7` [mpath](https://github.com/spacetab-io/mpath-go) - MPTT (Modified Preorder Tree Traversal) package for SQL records - materialized path realisation.
* [ormlite](https://github.com/pupizoid/ormlite) - Lightweight package containing some ORM-like features and helpers for sqlite databases.
* `   515` [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities.
* `    19` [qry](https://github.com/HnH/qry) - Tool that generates constants from files with raw SQL queries.
* `    94` [sq](https://github.com/bokwoon95/go-structured-query) - Type-safe SQL builder and struct mapper for Go.
* `    16` [sqlf](https://github.com/leporo/sqlf) - Fast SQL query builder.
* `   134` [sqlingo](https://github.com/lqs/sqlingo) - A lightweight DSL to build SQL in Go.
* `   216` [sqrl](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance.
* [Squalus](https://gitlab.com/qosenergy/squalus) - Thin layer over the Go SQL package that makes it easier to perform queries.
* `  3545` [Squirrel](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries.
* `  2665` [xo](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.

## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
  * `    60` [avatica](https://github.com/apache/calcite-avatica-go) - Apache Avatica/Phoenix SQL driver for database/sql.
  * `    15` [bgc](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go.
  * `   135` [firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go.
  * `   114` [go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that uses database/sql.
  * `  1322` [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go.
  * `   518` [go-oci8](https://github.com/mattn/go-oci8) - Oracle driver for go that uses database/sql.
  * ` 10353` [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go.
  * `  4532` [go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that uses database/sql.
  * `   104` [gofreetds](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org).
  * `   283` [goracle](https://github.com/go-goracle/goracle) - Oracle driver for Go, using the ODPI-C driver.
  * `  3559` [pgx](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql.
  * `  6288` [pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql.
  * `    27` [Sqinn-Go](https://github.com/cvilsmeier/sqinn-go) - SQLite with pure Go.

* NoSQL Databases
  * `   351` [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language.
  * `    69` [arangolite](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB.
  * `     6` [asc](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go.
  * `    71` [dynago](https://github.com/underarmour/dynago) - Dynago is a principle of least surprise client for DynamoDB.
  * `    29` [forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB.
  * `   305` [go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go.
  * `    43` [go-pilosa](https://github.com/pilosa/go-pilosa) - Go client library for Pilosa.
  * `   148` [go-rejson](https://github.com/nitishm/go-rejson) - Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease.
  * `   318` [gocb](https://github.com/couchbase/gocb) - Official Couchbase Go SDK.
  * [gocql](http://gocql.github.io) - Go language driver for Apache Cassandra.
  * `    85` [godis](https://github.com/piaohao/godis) - redis client implement by golang, inspired by jedis.
  * `     7` [godscache](https://github.com/defcronyke/godscache) - A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached.
  * `  1297` [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language.
  * `  1549` [gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB.
  * `    26` [goriak](https://github.com/zegl/goriak) - Go language driver for Riak KV.
  * `   226` [mgm](https://github.com/kamva/mgm) - MongoDB model-based ODM for Go (based on official MongoDB driver).
  * `  1855` [mgo](https://github.com/globalsign/mgo) - (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.
  * `  5189` [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - Official MongoDB driver for the Go language.
  * `    26` [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang.
  * `    76` [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang.
  * `   373` [neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang.
  * `   369` [qmgo](https://github.com/qiniu/qmgo) - The MongoDB driver for Go. It‘s based on official MongoDB driver but easier to use like Mgo.
  * `   389` [redeo](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services.
  * `  8099` [redigo](https://github.com/gomodule/redigo) - Redigo is a Go client for the Redis database.
  * ` 10447` [redis](https://github.com/go-redis/redis) - Redis client for Golang.
  * `    13` [xredis](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client.

* Search and Analytic Databases.
  * `  7175` [bleve](https://github.com/blevesearch/bleve) - Modern text indexing library for go.
  * `  5606` [elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go.
  * `   642` [elasticsql](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go.
  * `   946` [elastigo](https://github.com/mattbaird/elastigo) - Elasticsearch client library.
  * `  3030` [go-elasticsearch](https://github.com/elastic/go-elasticsearch) - Official Elasticsearch client for Go.
  * `    24` [goes](https://github.com/OwnLocal/goes) - Library to interact with Elasticsearch.
  * `  5549` [riot](https://github.com/go-ego/riot) - Go Open Source, Distributed, Simple and efficient Search Engine.
  * `    75` [skizze](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage.

* Multiple Backends.
  * `   142` [cachego](https://github.com/fabiorphp/cachego) - Golang Cache component for multiple drivers.
  * ` 13704` [cayley](https://github.com/google/cayley) - Graph database with support for multiple backends.
  * `    21` [dsc](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files.
  * `   295` [gokv](https://github.com/philippgille/gokv) - Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more).

## Date and Time

*Libraries for working with dates and times.*

* `   526` [carbon](https://github.com/uniplaces/carbon) - Simple Time extension with a lot of util methods, ported from PHP Carbon library.
* `     6` [cronrange](https://github.com/1set/cronrange) - Parses Cron-style time range expressions, checks if the given time is within any ranges.
* `    56` [date](https://github.com/rickb777/date) - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day.
* `  1205` [dateparse](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance.
* `   337` [durafmt](https://github.com/hako/durafmt) - Time duration formatting library for Go.
* `    34` [feiertage](https://github.com/wlbr/feiertage) - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving...
* `    90` [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang).
* `    17` [go-str2duration](https://github.com/xhit/go-str2duration) - Convert string to duration. Support time.Duration returned string and more.
* `    30` [go-sunrise](https://github.com/nathan-osman/go-sunrise) - Calculate the sunrise and sunset times for a given location.
* `     4` [go-week](https://github.com/stoewer/go-week) - An efficient package to work with ISO8601 week dates.
* `    83` [iso8601](https://github.com/relvacode/iso8601) - Efficiently parse ISO8601 date-times without regex.
* `    17` [kair](https://github.com/GuilhermeCaruso/kair) - Date and Time - Golang Formatting Library.
* `  2857` [now](https://github.com/jinzhu/now) - Now is a time toolkit for golang.
* `    11` [NullTime](https://github.com/kirillDanshin/nulltime) - Nullable `time.Time`.
* `     7` [strftime](https://github.com/awoodbeck/strftime) - C99-compatible strftime formatter.
* `    74` [timespan](https://github.com/SaidinWoT/timespan) - For interacting with intervals of time, defined as a start time and a duration.
* `   183` [timeutil](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package.
* `     9` [tuesday](https://github.com/osteele/tuesday) - Ruby-compatible Strftime function.

## Distributed Systems

*Packages that help with building Distributed Systems.*

* `   135` [arpc](https://github.com/lesismal/arpc) - More effective network communication, support two-way-calling, notify, broadcast.
* `    61` [celeriac](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go.
* `   343` [consistent](https://github.com/buraksezer/consistent) - Consistent hashing with bounded loads.
* `     5` [consistenthash](https://github.com/mbrostami/consistenthash) - Consistent hashing with configurable replicas.
* `   177` [dht](https://github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation.
* `   369` [digota](https://github.com/digota/digota) - grpc ecommerce microservice.
* `    48` [dot](https://github.com/dotchain/dot/) - distributed sync using operational transformation/OT.
* `    56` [doublejump](https://github.com/edwingeng/doublejump) - A revamped Google's jump consistent hash.
* `  3387` [dragonboat](https://github.com/lni/dragonboat) - A feature complete and high performance multi-group Raft library in Go.
* `    29` [drmaa](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard.
* [dynamolock](https://cirello.io/dynamolock) - DynamoDB-backed distributed locking implementation.
* `    14` [dynatomic](https://github.com/tylfin/dynatomic) - A library for using DynamoDB as an atomic counter.
* `  2681` [emitter-io](https://github.com/emitter-io/emitter) - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love.
* `    38` [flowgraph](https://github.com/vectaport/flowgraph) - flow-based programming package.
* `  2712` [gleam](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed.
* `  2908` [glow](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go.
* `     9` [gmsec](https://github.com/gmsec/micro) - A Go distributed systems development framework.
* `   577` [go-health](https://github.com/InVisionApp/go-health) - Library for enabling asynchronous dependency health checks in your service.
* `   307` [go-jump](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function.
* ` 19030` [go-kit](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.
* ` 15135` [go-micro](https://github.com/micro/go-micro) - A distributed systems development framework.
* `    16` [go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) - MySQL based distributed lock.
* `    24` [go-pdu](https://github.com/pdupub/go-pdu) - A decentralized identity-based social network.
* `   336` [go-sundheit](https://github.com/AppsFlyer/go-sundheit) - A library built to provide support for defining async service health checks for golang services.
* `   621` [gorpc](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load.
* ` 12872` [grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC.
* `  1130` [hprose](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now.
* `   139` [jsonrpc](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0.
* `   155` [jsonrpc](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation.
* `  3418` [KrakenD](https://github.com/devopsfaith/krakend) - Ultra performant API Gateway framework with middlewares.
* `  1967` [liftbridge](https://github.com/liftbridge-io/liftbridge) - Lightweight, fault-tolerant message streams for NATS.
* `  9451` [micro](https://github.com/micro/micro) - A distributed systems runtime for the cloud and beyond.
* `  8695` [NATS](https://github.com/nats-io/gnatsd) - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems.
* `    47` [outboxer](https://github.com/italolelis/outboxer) - Outboxer is a go library that implements the outbox pattern.
* [pglock](https://cirello.io/pglock) - PostgreSQL-backed distributed locking implementation.
* [pjrpc](https://gitlab.com/pjrpc/pjrpc) - Golang JSON-RPC Server-Client with Protobuf spec.
* `  4181` [raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp.
* ` 34180` [raft](https://github.com/coreos/etcd/tree/master/raft) - Go implementation of the Raft consensus protocol, by CoreOS.
* `   549` [rain](https://github.com/cenkalti/rain) - BitTorrent client and library.
* `   280` [redis-lock](https://github.com/bsm/redislock) - Simplified distributed locking implementation using Redis.
* [resgate](https://resgate.io/) - Realtime API Gateway for building REST, real time, and RPC APIs, where all clients are synchronized seamlessly.
* `   651` [ringpop-go](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications.
* `  5339` [rpcx](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo.
* `    51` [Semaphore](https://github.com/jexia/semaphore) - A straightforward (micro) service orchestrator.
* `   326` [sleuth](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using `  6635` [ZeroMQ](https://github.com/zeromq/libzmq)).
* `  3836` [tendermint](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.
* `  3734` [torrent](https://github.com/anacrolix/torrent) - BitTorrent client package.

## Dynamic DNS

*Tools for updating dynamic DNS records.*

* `   169` [DDNS](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend.
* [dyndns](https://gitlab.com/alcastle/dyndns) - Background Go process to regularly and automatically check your IP Address and make updates to (one or many) Dynamic DNS records for Google domains whenever your address changes.
* `   732` [GoDNS](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go.

## Email

*Libraries and tools that implement email creation and sending.*

* [chasquid](https://blitiri.com.ar/p/chasquid) - SMTP server written in Go.
* `   187` [douceur](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails.
* `  1609` [email](https://github.com/jordan-wright/email) - A robust and flexible email library for Go.
* `   121` [email-verifier](https://github.com/AfterShip/email-verifier) - A Go library for email verification without sending any emails.
* `    64` [go-dkim](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email.
* `  1170` [go-imap](https://github.com/emersion/go-imap) - IMAP library for clients and servers.
* `   183` [go-message](https://github.com/emersion/go-message) - Streaming library for the Internet Message Format and mail messages.
* `    66` [go-premailer](https://github.com/vanng822/go-premailer) - Inline styling for HTML mail in Go.
* `    84` [go-simple-mail](https://github.com/xhit/go-simple-mail) - Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send.
* `   192` [Hectane](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API.
* `  2142` [hermes](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails.
* `    68` [mailchain](https://github.com/mailchain/mailchain) - Send encrypted emails to blockchain addresses written in Go.
* `   493` [mailgun-go](https://github.com/mailgun/mailgun-go) - Go library for sending mail with the Mailgun API.
* `  7602` [MailHog](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface.
* `   688` [SendGrid](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email.
* `    59` [smtp](https://github.com/mailhog/smtp) - SMTP server protocol state machine.

## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

* `  1090` [anko](https://github.com/mattn/anko) - Scriptable interpreter written in Go.
* `    48` [binder](https://github.com/alexeyco/binder) - Go to Lua binding library, based on `  3870` [gopher-lua](https://github.com/yuin/gopher-lua).
* `   658` [cel-go](https://github.com/google/cel-go) - Fast, portable, non-Turing complete expression evaluation with gradual typing.
* `     3` [ecal](https://github.com/krotik/ecal) - A simple embeddable scripting language which supports concurrent event processing.
* `  1558` [expr](https://github.com/antonmedv/expr) - Expression evaluation engine for Go: fast, non-Turing complete, dynamic typing, static typing.
* `    69` [gentee](https://github.com/gentee/gentee) - Embeddable scripting programming language.
* `   443` [gisp](https://github.com/jcla1/gisp) - Simple LISP in Go.
* `   741` [go-duktape](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go.
* `  2000` [go-lua](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go.
* `   771` [go-php](https://github.com/deuill/go-php) - PHP bindings for Go.
* `  1213` [go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API.
* `  1914` [goja](https://github.com/dop251/goja) - ECMAScript 5.1(+) implementation in Go.
* `   498` [golua](https://github.com/aarzilli/golua) - Go bindings for Lua C API.
* `  3870` [gopher-lua](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go.
* `   274` [gval](https://github.com/PaesslerAG/gval) - A highly customizable expression language written in Go.
* `    20` [ngaro](https://github.com/db47h/ngaro) - Embeddable Ngaro VM implementation enabling scripting in Retro.
* `    30` [purl](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go.
* `  2118` [tengo](https://github.com/d5/tengo) - Bytecode compiled script language for Go.

## Error Handling

*Libraries for handling errors.*

* `   194` [emperror](https://github.com/emperror/emperror) - Error handling tools and best practices for Go libraries and applications.
* `   713` [eris](https://github.com/rotisserie/eris) - A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors.
* `   389` [errlog](https://github.com/snwfdhmp/errlog) - Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place.
* `    86` [errors](https://github.com/emperror/errors) - Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives.
* `  6413` [errors](https://github.com/pkg/errors) - Package that provides simple error handling primitives.
* `     3` [errors](https://github.com/neuronlabs/errors) - Simple golang error handling with classification primitives.
* `     2` [errors](https://github.com/PumpkinSeed/errors) - The most simple error wrapper with awesome performance and minimal memory overhead.
* `    12` [errors](https://github.com/bnkamalesh/errors) - Drop-in replacement for builting Go errors. This is a minimal error handling package with custom error types, user friendly messages, Unwrap & Is. With very easy to use and straightforward helper functions.
* `   662` [errorx](https://github.com/joomcode/errorx) - A feature rich error package with stack traces, composition of errors and more.
* `     6` [Falcon](https://github.com/SonicRoshan/falcon) - A Simple Yet Highly Powerful Package For Error Handling.
* `  1098` [go-multierror](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error.
* `   638` [tracerr](https://github.com/ztrue/tracerr) - Golang errors with stack trace and source fragments.

## File Handling

*Libraries for handling files and file systems.*

* `  3394` [afero](https://github.com/spf13/afero) - FileSystem Abstraction System for Go.
* `   104` [afs](https://github.com/viant/afs) - Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go.
* `    16` [baraka](https://github.com/xis/baraka) - A library to process http file uploads easily.
* `   175` [bigfile](https://github.com/bigfile/bigfile) - A file transfer system, support to manage files with http api, rpc call and ftp client.
* `    30` [checksum](https://github.com/codingsince1985/checksum) - Compute message digest, like MD5 and SHA256, for large files.
* `   230` [copy](https://github.com/otiai10/copy) - Copy directory recursively.
* `    21` [flop](https://github.com/homedepot/flop) - File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html).
* `    77` [go-csv-tag](https://github.com/artonge/go-csv-tag) - Load csv file using tag.
* `    14` [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) - Copy files for humans.
* `    44` [go-exiftool](https://github.com/barasher/go-exiftool) - Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...).
* `    24` [go-gtfs](https://github.com/artonge/go-gtfs) - Load gtfs files in go.
* `    14` [gut/yos](https://github.com/1set/gut) - Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links.
* `   600` [notify](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal.
* `    65` [opc](https://github.com/qmuntal/opc) - Load Open Packaging Conventions (OPC) files for Go.
* `     9` [parquet](https://github.com/parsyl/parquet) - Read and write [parquet](https://parquet.apache.org) files.
* `  1844` [pdfcpu](https://github.com/pdfcpu/pdfcpu) - PDF processor.
* `    60` [skywalker](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease.
* [stl](https://gitlab.com/russoj88/stl) - Modules to read and write STL (stereolithography) files. Concurrent algorithm for reading.
* `    45` [tarfs](https://github.com/posener/tarfs) - Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files.
* `     5` [todotxt](https://github.com/1set/todotxt) - Go library for Gina Trapani's [*todo.txt*](http://todotxt.org/) files, supports parsing and manipulating of task lists in the `  1034` [*todo.txt* format](https://github.com/todotxt/todo.txt).
* `    78` [vfs](https://github.com/C2FO/vfs) - A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS.

## Financial

*Packages for accounting and finance.*

* `   610` [accounting](https://github.com/leekchan/accounting) - money and currency formatting for golang.
* `   229` [currency](https://github.com/bojanz/currency) - Handles currency amounts, provides currency information and formatting.
* `    36` [currency](https://github.com/bnkamalesh/currency) - High performant & accurate currency computation package.
* `  2677` [decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers.
* `    18` [fastme](https://github.com/newity/fastme) - Fast extensible matching engine Go implementation.
* `   534` [go-finance](https://github.com/FlashBoys/go-finance) - Comprehensive financial markets data in Go.
* `    87` [go-finance](https://github.com/alpeb/go-finance) - Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations.
* `     4` [go-finance](https://github.com/pieterclaerhout/go-finance) - Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers.
* `    47` [go-finnhub](https://github.com/m1/go-finnhub) - Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges.
* `   859` [go-money](https://github.com/rhymond/go-money) - Implementation of Fowler's Money pattern.
* `    79` [ofxgo](https://github.com/aclindsa/ofxgo) - Query OFX servers and/or parse the responses (with example command-line client).
* `   171` [orderbook](https://github.com/i25959341/orderbook) - Matching Engine for Limit Order Book in Golang.
* `    24` [sleet](https://github.com/BoltApp/sleet) - One unified interface for multiple Payment Service Providers (PsP) to process online payment.
* `   346` [techan](https://github.com/sdcoffey/techan) - Technical analysis library with advanced market analysis and trading strategies.
* `    80` [transaction](https://github.com/claygod/transaction) - Embedded transactional database of accounts, running in multithreaded mode.
* `    80` [vat](https://github.com/dannyvankooten/vat) - VAT number validation & EU VAT rates.

## Forms

*Libraries for working with forms.*

* `    25` [bind](https://github.com/robfig/bind) - Bind form data to any Go values.
* `   783` [binding](https://github.com/mholt/binding) - Binds form and JSON data from net/http Request to struct.
* `   208` [conform](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags.
* `   439` [form](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support.
* `   154` [formam](https://github.com/monoculum/formam) - decode form's values into a struct.
* `   114` [forms](https://github.com/albrow/forms) - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files.
* `   607` [gorilla/csrf](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services.
* `  1112` [nosurf](https://github.com/justinas/nosurf) - CSRF protection middleware for Go.
* `    55` [qs](https://github.com/sonh/qs) - Go module for encoding structs into URL query parameters.
* `     7` [queryparam](https://github.com/tomwright/queryparam) - Decode `url.Values` into usable struct values of standard or custom types.

## Functional

*Packages to support functional programming in Go.*

* `   162` [fpGo](https://github.com/TeaEntityLab/fpGo) - Monad, Functional Programming features for Golang.
* `    80` [fuego](https://github.com/seborama/fuego) - Functional Experiment in Go.
* `  1176` [go-underscore](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities.

## Game Development

*Awesome game development libraries.*

* `   465` [Azul3D](https://github.com/azul3d/engine) - 3D game engine written in Go.
* `  3917` [Ebiten](https://github.com/hajimehoshi/ebiten) - dead simple 2D game library in Go.
* `  1311` [engo](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm.
* `  1278` [g3n](https://github.com/g3n/engine) - Go 3D Game Engine.
* `   405` [go-astar](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm.
* `  1466` [go-sdl2](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/).
* `   188` [go3d](https://github.com/ungerik/go3d) - Performance oriented 2D/3D math package for Go.
* `  1121` [gonet](https://github.com/xtaci/gonet) - Game server skeleton implemented with golang.
* `  1718` [goworld](https://github.com/xiaonanln/goworld) - Scalable game server engine, featuring space-entity framework and hot-swapping.
* `  3812` [Leaf](https://github.com/name5566/leaf) - Lightweight game server framework.
* `  1536` [nano](https://github.com/lonng/nano) - Lightweight, facility, high performance golang based game server framework.
* `   826` [Oak](https://github.com/oakmound/oak) - Pure Go game engine.
* `   838` [Pitaya](https://github.com/topfreegames/pitaya) - Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK.
* `  3289` [Pixel](https://github.com/faiface/pixel) - Hand-crafted 2D game library in Go.
* `    40` [prototype](https://github.com/gonutz/prototype) - Cross-platform (Windows/Linux/Mac) library for creating desktop games using a minimal API.
* `   562` [raylib-go](https://github.com/gen2brain/raylib-go) - Go bindings for [raylib](http://www.raylib.com/), a simple and easy-to-use library to learn videogames programming.
* `  1180` [termloop](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox.
* `    14` [tile](https://github.com/kelindar/tile) - Data-oriented and cache-friendly 2D Grid library (TileMap), includes pathfinding, observers and import/export.

## Generation and Generics

*Tools to enhance the language with features like generics via code generation.*

* `    47` [efaceconv](https://github.com/t0pep0/efaceconv) - Code generation tool for high performance conversion from interface{} to immutable type without allocations.
* `  1210` [gen](https://github.com/clipperhouse/gen) - Code generation tool for ‘generics’-like functionality.
* `    22` [generis](https://github.com/senselogic/GENERIS) - Code generation tool providing generics, free-form macros, conditional compilation and HTML templating.
* `   147` [go-enum](https://github.com/abice/go-enum) - Code generation for enums from code comments.
* `  2339` [go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go.
* `    16` [go-xray](https://github.com/pieterclaerhout/go-xray) - Helpers for making the use of reflection easier.
* `   837` [goderive](https://github.com/awalterschulze/goderive) - Derives functions from input types.
* `    33` [gotype](https://github.com/wzshiming/gotype) - Golang source code parsing, usage like reflect package.
* `   429` [GoWrap](https://github.com/hexdigest/gowrap) - Generate decorators for Go interfaces using simple templates.
* `   258` [interfaces](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions.
* `  1792` [jennifer](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates.
* `    96` [pkgreflect](https://github.com/ungerik/pkgreflect) - Go preprocessor for package scoped reflection.
* `     8` [typeregistry](https://github.com/xiaoxin01/typeregistry) - A library to create type dynamically.

## Geographic

*Geographic tools and servers*

* `   128` [geocache](https://github.com/melihmucuk/geocache) - In-memory cache that is suitable for geolocation based applications.
* `    42` [geoserver](https://github.com/hishamkaram/geoserver) - geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API.
* `    35` [gismanager](https://github.com/hishamkaram/gismanager) - Publish Your GIS Data(Vector Data) to PostGIS and Geoserver.
* `   197` [mbtileserver](https://github.com/consbio/mbtileserver) - A simple Go-based server for map tiles stored in mbtiles format.
* `   148` [osm](https://github.com/paulmach/osm) - Library for reading, writing and working with OpenStreetMap data and APIs.
* `    23` [pbf](https://github.com/maguro/pbf) - OpenStreetMap PBF golang encoder/decoder.
* `     9` [S2 geojson](https://github.com/pantrif/s2-geojson) - Convert geojson to s2 cells & demonstrating some S2 geometry features on map.
* `  1146` [S2 geometry](https://github.com/golang/geo) - S2 geometry library in Go.
* `  7192` [Tile38](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing.
* `    58` [WGS84](https://github.com/wroge/wgs84) - Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM).

## Go Compilers

*Tools for compiling Go to other languages.*

* `   243` [c4go](https://github.com/Konstantin8105/c4go) - Transpile C code to Go code.
* `    24` [f4go](https://github.com/Konstantin8105/f4go) - Transpile FORTRAN 77 code to Go code.
* `  9838` [gopherjs](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript.
* `  1103` [llgo](https://github.com/go-llvm/llgo) - LLVM-based compiler for Go.
* `   404` [tardisgo](https://github.com/tardisgo/tardisgo) - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler.

## Goroutines

*Tools for managing and working with Goroutines.*

* `  4740` [ants](https://github.com/panjf2000/ants) - A high-performance and low-cost goroutine pool in Go.
* `    96` [artifex](https://github.com/borderstech/artifex) - Simple in-memory job queue for Golang using worker-based dispatching.
* `    18` [async](https://github.com/reugn/async) - An alternative sync library for Go (Future, Promise, Locks).
* `    69` [async](https://github.com/studiosol/async) - A safe way to execute functions asynchronously, recovering them in case of panic.
* `    82` [breaker](https://github.com/kamilsk/breaker) - Flexible mechanism to make execution flow interruptible.
* `     5` [channelify](https://github.com/ddelizia/channelify) - Transform your function to return channels for easy and powerful parallel processing.
* `     4` [concurrency-limiter](https://github.com/vivek-ng/concurrency-limiter) - Concurrency limiter with support for timeouts , dynamic priority and context cancellation of goroutines.
* `    10` [conexec](https://github.com/ITcathyh/conexec) - A concurrent toolkit to help execute funcs concurrently in an efficient and safe way. It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency.
* `    56` [cyclicbarrier](https://github.com/marusama/cyclicbarrier) - CyclicBarrier for golang.
* `   183` [go-floc](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease.
* `   148` [go-flow](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order.
* `     5` [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) - Manage a pool of goroutines using this lightweight library with a simple API.
* `    12` [go-trylock](https://github.com/subchen/go-trylock) - TryLock support on read-write lock for Golang.
* `    14` [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) - Like `sync.WaitGroup` with error handling and concurrency control.
* `    18` [goccm](https://github.com/zenthangplus/goccm) - Go Concurrency Manager package limits the number of goroutines that allowed to run concurrently.
* `    13` [gohive](https://github.com/loveleshsharma/gohive) - A highly performant and easy to use Goroutine pool for Go.
* `    44` [gollback](https://github.com/vardius/gollback) - asynchronous simple function utilities, for managing execution of closures and callbacks.
* `  2500` [goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker.
* `   247` [gowp](https://github.com/xxjwxc/gowp) - gowp is concurrency limiting goroutine pool.
* `    71` [gpool](https://github.com/Sherifabdlnaby/gpool) - manages a resizeable pool of context-aware goroutines to bound concurrency.
* `   603` [grpool](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool.
* `     5` [hands](https://github.com/duanckham/hands) - A process controller used to control the execution and return strategies of multiple goroutines.
* `    38` [Hunch](https://github.com/AaronJan/Hunch) - Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive.
* `    30` [kyoo](https://github.com/dirkaholic/kyoo) - Provides an unlimited job queue and concurrent worker pools.
* `    61` [neilotoole/errgroup](https://github.com/neilotoole/errgroup) - Drop-in alternative to `sync/errgroup`, limited to a pool of N worker goroutines.
* `    19` [nursery](https://github.com/arunsworld/nursery) - Structured concurrency in Go.
* [oversight](https://cirello.io/oversight) - Oversight is a complete implementation of the Erlang supervision trees.
* `    29` [parallel-fn](https://github.com/rafaeljesus/parallel-fn) - Run functions in parallel.
* `   145` [pond](https://github.com/alitto/pond) - Minimalistic and High-performance goroutine worker pool written in Go.
* `   585` [pool](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation.
* `     9` [queue](https://github.com/AnikHasibul/queue) - Gives you a `sync.WaitGroup` like queue group accessibility. Helps you to throttle and limit goroutines, wait for the end of the all goroutines and much more.
* `    39` [routine](https://github.com/x-mod/routine) - go routine control with context, support: Main, Go, Pool and some useful Executors.
* `    84` [semaphore](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context.
* `   104` [semaphore](https://github.com/marusama/semaphore) - Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations).
* `    18` [stl](https://github.com/ssgreg/stl) - Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism.
* `    51` [threadpool](https://github.com/shettyh/threadpool) - Golang threadpool implementation.
* `  1820` [tunny](https://github.com/Jeffail/tunny) - Goroutine pool for golang.
* `    69` [worker-pool](https://github.com/vardius/worker-pool) - goworker is a Go simple async worker pool.
* `   436` [workerpool](https://github.com/gammazero/workerpool) - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued.

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

* `  4270` [app](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress.
* ` 11764` [fyne](https://github.com/fyne-io/fyne) - Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android.
* `  3572` [go-astilectron](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron).
* [go-gtk](http://mattn.github.io/go-gtk/) - Go bindings for GTK.
* `  1939` [go-sciter](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform.
* `  1348` [gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3.
* `   293` [gowd](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform.
* `  8106` [qt](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi).
* `  7759` [ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform.
* [Wails](https://wails.app) - Mac, Windows, Linux desktop apps with HTML UI using built-in OS HTML renderer.
* `  5074` [walk](https://github.com/lxn/walk) - Windows application library kit for Go.
* `  7313` [webview](https://github.com/zserge/webview) - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux).

*Interaction*

* `    13` [go-appindicator](https://github.com/dawidd6/go-appindicator) - Go bindings for libappindicator3 C library.
* `   529` [gosx-notifier](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go.
* `     8` [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) - OSX library to notify about any (pluggable) activity on your machine.
* `     7` [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) - OSX Sleep/Wake notifications in golang.
* `  6346` [robotgo](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other.
* `  1589` [systray](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area.
* `   199` [trayhost](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar.

## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See `  1121` [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

## Images

*Libraries for manipulating images.*

* `  3008` [bild](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go.
* `  1304` [bimg](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips.
* `    66` [cameron](https://github.com/aofei/cameron) - An avatar generator for Go.
* `   568` [canvas](https://github.com/tdewolff/canvas) - Vector graphics to PDF, SVG or rasterized image.
* `   152` [darkroom](https://github.com/gojek/darkroom) - An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency.
* `   475` [draft](https://github.com/lucasepe/draft) - Generate High Level Microservice Architecture diagrams for GraphViz using simple YAML syntax.
* `  1100` [geopattern](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string.
* `  2591` [gg](https://github.com/fogleman/gg) - 2D rendering in pure Go.
* `  1394` [gift](https://github.com/disintegration/gift) - Package of image processing filters.
* `    88` [gltf](https://github.com/qmuntal/gltf) - Efficient and robust glTF 2.0 reader, writer and validator.
* `    96` [go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library.
* `    51` [go-gd](https://github.com/bolknote/go-gd) - Go binding for GD library.
* `   320` [go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go.
* `  1214` [go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV.
* `    25` [go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go.
* `  3737` [gocv](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3.3+.
* `   365` [goimagehash](https://github.com/corona10/goimagehash) - Go Perceptual image hashing package.
* `    36` [goimghdr](https://github.com/corona10/goimghdr) - The imghdr module determines the type of image contained in a file for Go.
* `   402` [govatar](https://github.com/o1egl/govatar) - Library and CMD tool for generating funny avatars.
* `   409` [govips](https://github.com/davidbyttow/govips) - A lightning fast image processing and resizing library for Go.
* `    35` [gridder](https://github.com/shomali11/gridder) - A Grid based 2D Graphics library.
* `   469` [image2ascii](https://github.com/qeesung/image2ascii) - Convert image to ASCII.
* `  1241` [imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API.
* `  3420` [imaginary](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing.
* `  3434` [imaging](https://github.com/disintegration/imaging) - Simple Go image processing package.
* `   137` [img](https://github.com/hawx/img) - Selection of image manipulation tools.
* `  2817` [ln](https://github.com/fogleman/ln) - 3D line art rendering in Go.
* `   127` [mergi](https://github.com/noelyahan/mergi) - Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate).
* `   417` [mort](https://github.com/aldor007/mort) - Storage and image processing server written in Go.
* `     6` [mpo](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos.
* `  1394` [picfit](https://github.com/thoas/picfit) - An image resizing server written in Go.
* `  1910` [pt](https://github.com/fogleman/pt) - Path tracing engine written in Go.
* `  2549` [resize](https://github.com/nfnt/resize) - Image resizing for Go with common interpolation methods.
* `   200` [rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD.
* `  1480` [smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes.
* `    86` [steganography](https://github.com/auyer/steganography) - Pure Go Library for LSB steganography.
* `   905` [stegify](https://github.com/DimitarPetrov/stegify) - Go tool for LSB steganography, capable of hiding any file within an image.
* `  1580` [svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation.
* `    26` [tga](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder.

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

* `   246` [connectordb](https://github.com/connectordb/connectordb) - Open-Source Platform for Quantified Self & IoT.
* `   238` [devices](https://github.com/goiot/devices) - Suite of libraries for IoT devices, experimental for x/exp/io.
* `    45` [eywa](https://github.com/xcodersun/eywa) - Project Eywa is essentially a connection manager that keeps track of connected devices.
* `  1653` [flogo](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration.
* `   942` [gatt](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals.
* `  6923` [gobot](https://github.com/hybridgroup/gobot/) - Gobot is a framework for robotics, physical computing, and the Internet of Things.
* `   172` [huego](https://github.com/amimof/huego) - An extensive Philips Hue client library for Go.
* `    47` [iot](https://github.com/vaelen/iot/) - IoT is a simple framework for implementing a Google IoT Core device.
* `  1234` [mainflux](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server.
* [periph](https://periph.io/) - Peripherals I/O to interface with low-level board facilities.
* `   199` [sensorbee](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT.

## Job Scheduler

*Libraries for scheduling jobs.*

* `   102` [clockwerk](http://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax.
* `    23` [clockwork](https://github.com/whiteShtef/clockwork) - Simple and intuitive job scheduling library in Go.
* `   203` [go-cron](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.
* `   101` [go-quartz](https://github.com/reugn/go-quartz) - Simple, zero-dependency scheduling library for Go.
* `   441` [gocron](https://github.com/go-co-op/gocron) - Easy and fluent Go job scheduling. This is an actively maintained fork of `  2351` [jasonlvhit/gocron](https://github.com/jasonlvhit/gocron).
* `   811` [gron](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.
* `   817` [JobRunner](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in.
* `   480` [jobs](https://github.com/albrow/jobs) - Persistent and flexible background jobs library.
* `    78` [leprechaun](https://github.com/kilgaloon/leprechaun) - Job scheduler that supports webhooks, crons and classic scheduling.
* `   354` [scheduler](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy.

## JSON

*Libraries for working with JSON.*

* `    52` [ajson](https://github.com/spyzhov/ajson) - Abstract JSON for golang with JSONPath support.
* `     6` [dynjson](https://github.com/cocoonspace/dynjson) - Client-customizable JSON formats for dynamic APIs.
* `     5` [ej](https://github.com/lucassscaravelli/ej) - Write and read JSON from different sources succinctly.
* `     4` [epoch](https://github.com/vtopc/epoch) - Contains primitives for marshaling/unmarshaling Unix timestamp/epoch to/from build-in time.Time type in JSON.
* `    86` [gjo](https://github.com/skanehira/gjo) - Small utility to create JSON objects.
* `  7546` [GJSON](https://github.com/tidwall/gjson) - Get a JSON value with one line of code.
* `    10` [go-jsonerror](https://github.com/ddymko/go-jsonerror) - Go-JsonError is ment to allow us to easily create json response errors that follow the JsonApi spec.
* `    39` [go-respond](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses.
* `   161` [gojq](https://github.com/elgs/gojq) - JSON query in Golang.
* `  2305` [gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON.
* `    80` [JayDiff](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go.
* `    94` [jettison](https://github.com/wI2L/jettison) - Fast and flexible JSON encoder for Go.
* [JSON-to-Go](https://mholt.github.io/json-to-go/) - Convert JSON to Go struct.
* `    72` [json2go](https://github.com/m-zajac/json2go) - Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all.
* `     9` [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference.
* `    98` [jsondiff](https://github.com/wI2L/jsondiff) - JSON diff library for Go based on RFC6902 (JSON Patch).
* `    60` [jsonf](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON.
* `    95` [jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects.
* `     9` [jsonhal](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses.
* `     1` [jzon](https://github.com/zerosnake0/jzon) - JSON library with standard compatible API/behavior.
* `   175` [kazaam](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents.
* `     3` [mapslice-json](https://github.com/mickep76/mapslice-json) - Go MapSlice for ordered marshal/ unmarshal of maps in JSON.
* `    44` [mp](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON.

## Logging

*Libraries for generating and working with log files.*

* `    26` [distillog](https://github.com/amoghe/distillog) - distilled levelled logging (think of it as stdlib + log levels).
* `    96` [glg](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go.
* `    13` [glo](https://github.com/lajosbencz/glo) - PHP Monolog inspired logging facility with identical severity levels.
* `  2633` [glog](https://github.com/golang/glog) - Leveled execution logs for Go.
* `    39` [go-cronowriter](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog.
* `     7` [go-log](https://github.com/pieterclaerhout/go-log) - A logging library with strack traces, object dumping and optional timestamps.
* `    11` [go-log](https://github.com/subchen/go-log) - Simple and configurable Logging in Go, with level, formatters and writers.
* `    28` [go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers.
* `    37` [go-log](https://github.com/ian-kent/go-log) - Log4j implementation in Go.
* `   262` [go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers.
* `    38` [gologger](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch.
* `    16` [gomol](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs.
* `    35` [gone/log](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library.
* `   201` [httpretty](https://github.com/henvic/httpretty) - Pretty-prints your regular HTTP requests on your terminal for debugging (similar to http.DumpRequest).
* `    22` [journald](https://github.com/ssgreg/journald) - Go implementation of systemd Journal's native API for logging.
* `     3` [kemba](https://github.com/clok/kemba) - A tiny debug logging tool inspired by `  9270` [debug](https://github.com/visionmedia/debug), great for CLI tools and applications.
* `     8` [log](https://github.com/aerogo/log) - An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection).
* `  1060` [log](https://github.com/apex/log) - Structured logging package for Go.
* `   276` [log](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go.
* `    24` [log](https://github.com/teris-io/log) - Structured log interface for Go cleanly separates logging facade from its implementation.
* `    88` [log-voyage](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang.
* `   991` [log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go.
* `     9` [logdump](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging.
* `    36` [logex](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib.
* `   148` [logger](https://github.com/azer/logger) - Minimalistic logging library for Go.
* `    10` [logmatic](https://github.com/borderstech/logmatic) - Colorized logger for Golang with dynamic log level configuration.
* `     7` [logo](https://github.com/mbndr/logo) - Golang logger to different configurable writers.
* ` 16828` [logrus](https://github.com/Sirupsen/logrus) - Structured logger for Go.
* `    10` [logrusiowriter](https://github.com/cabify/logrusiowriter) - `io.Writer` implementation using ` 16828` [logrus](https://github.com/sirupsen/logrus) logger.
* `    26` [logrusly](https://github.com/sebest/logrusly) - ` 16828` [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/).
* `   107` [logur](https://github.com/logur/logur) - An opinionated logger interface and collection of logging best practices with adapters and integrations for well-known libraries (` 16828` [logrus](https://github.com/sirupsen/logrus), ` 19030` [go-kit log](https://github.com/go-kit/kit/tree/master/log), ` 11563` [zap](https://github.com/uber-go/zap), `  4137` [zerolog](https://github.com/rs/zerolog), etc).
* `   288` [logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger.
* `   346` [logxi](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy.
* `  2296` [lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser.
* `    21` [mlog](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.
* `   381` [onelog](https://github.com/francoispqt/onelog) - Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenarios. Also, it is one of the logger with the lowest allocation.
* `   115` [ozzo-log](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).
* `   286` [phuslu/log](https://github.com/phuslu/log) - Structured Logging Made Easy.
* `   164` [rollingwriter](https://github.com/arthurkiller/rollingWriter) - RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation.
* `  1522` [seelog](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting.
* `  4159` [spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging.
* `   149` [sqldb-logger](https://github.com/simukti/sqldb-logger) - A logger for Go SQL database driver without modify existing *sql.DB stdlib usage.
* `    45` [stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.
* `  1970` [tail](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program.
* `     6` [xlog](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format.
* `   135` [xlog](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching.
* ` 11563` [zap](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go.
* `  4137` [zerolog](https://github.com/rs/zerolog) - Zero-allocation JSON logger.

## Machine Learning

*Libraries for Machine Learning.*

* `   697` [bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang.
* `   678` [CloudForest](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go.
* `   709` [eaopt](https://github.com/MaxHalford/eaopt) - An evolutionary optimization library.
* `    15` [evoli](https://github.com/khezen/evoli) - Genetic Algorithm and Particle Swarm Optimization library.
* `    44` [fonet](https://github.com/Fontinalis/fonet) - A Deep Neural Network library written in Go.
* `    26` [go-cluster](https://github.com/e-XpertSolutions/go-cluster) - Go implementation of the k-modes and k-prototypes clustering algorithms.
* `   294` [go-deep](https://github.com/patrikeh/go-deep) - A feature-rich neural network library in Go.
* `   104` [go-fann](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library.
* `    28` [go-featureprocessing](https://github.com/nikolaydubina/go-featureprocessing) - Fast and convenient feature processing for low latency machine leraning in Go.
* `   183` [go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang.
* `    58` [go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang.
* `   458` [gobrain](https://github.com/goml/gobrain) - Neural Networks written in go.
* `    26` [godist](https://github.com/e-dard/godist) - Various probability distributions, and associated methods.
* `   100` [goga](https://github.com/tomcraven/goga) - Genetic algorithm library for Go.
* `  7573` [GoLearn](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go.
* `    41` [golinear](https://github.com/danieldk/golinear) - liblinear bindings for Go.
* `    10` [GoMind](https://github.com/surenderthakran/gomind) - A simplistic Neural Network Library in Go.
* `  1151` [goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go.
* `    62` [gonet](https://github.com/dathoangnd/gonet) - Neural Network for Go.
* `   161` [Goptuna](https://github.com/c-bata/goptuna) - Bayesian optimization framework for black-box functions written in Go. Everything will be optimized.
* `   168` [goRecommend](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go.
* `  3764` [gorgonia](https://github.com/gorgonia/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms.
* `  1100` [gorse](https://github.com/zhenghaoz/gorse) - An offline recommender system backend based on collaborative filtering written in Go.
* `    63` [goscore](https://github.com/asafschers/goscore) - Go Scoring API for PMML.
* `  1354` [gosseract](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library.
* `    68` [libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14.
* `    58` [neat](https://github.com/jinyeom/neat) - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT).
* `    62` [neural-go](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation.
* `   343` [ocrserver](https://github.com/otiai10/ocrserver) - A simple OCR API server, seriously easy to be deployed by Docker and Heroku.
* `   296` [onnx-go](https://github.com/owulveryck/onnx-go) - Go Interface to Open Neural Network Exchange (ONNX).
* `    13` [probab](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go.
* `     7` [randomforest](https://github.com/malaschitz/randomForest) - Easy to use Random Forest library for Go.
* `   288` [regommend](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine.
* `   137` [shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go.
* `  1608` [tfgo](https://github.com/galeone/tfgo) - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python.
* `    33` [Varis](https://github.com/Xamber/Varis) - Golang Neural Network.

## Messaging

*Libraries that implement messaging systems.*

* `    12` [ami](https://github.com/kak-tus/ami) - Go client to reliable queues based on Redis Cluster Streams.
* `  2417` [APNs2](https://github.com/sideshow/apns2) - HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps.
* `   827` [Asynq](https://github.com/hibiken/asynq) - A simple, reliable, and efficient distributed task queue for Go built on top of Redis.
* `   991` [Beaver](https://github.com/Clivern/Beaver) - A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps.
* `  2771` [Benthos](https://github.com/Jeffail/benthos) - A message streaming bridge between a range of protocols.
* `   173` [Bus](https://github.com/mustafaturan/bus) - Minimalist message bus implementation for internal communication.
* `  4798` [Centrifugo](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go.
* `    52` [Commander](https://github.com/jeroenrinzema/commander) - A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka.
* `  2436` [Confluent Kafka Golang Client](https://github.com/confluentinc/confluent-kafka-go) - confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform.
* `   536` [dbus](https://github.com/godbus/dbus) - Native Go bindings for D-Bus.
* `    73` [drone-line](https://github.com/appleboy/drone-line) - Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI.
* `   389` [emitter](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins.
* `    36` [event](https://github.com/agoalofalife/event) - Implementation of the pattern observer.
* `   836` [EventBus](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility.
* `     9` [gaurun-client](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go.
* `   357` [Glue](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io).
* `    49` [go-mq](https://github.com/cheshir/go-mq) - RabbitMQ client with declarative configuration.
* `    52` [go-notify](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec.
* `  1823` [go-nsq](https://github.com/nsqio/go-nsq) - the official Go package for NSQ.
* `    42` [go-res](https://github.com/jirenius/go-res) - Package for building REST/real-time services where clients are synchronized seamlessly, using NATS and Resgate.
* `  3866` [go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework.
* `    16` [go-vitotrol](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service.
* `   881` [Gollum](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations.
* `   494` [golongpoll](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple.
* `  1954` [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster.
* `  5152` [gorush](https://github.com/appleboy/gorush) - Push notification server using `  2417` [APNs2](https://github.com/sideshow/apns2) and google `   104` [GCM](https://github.com/google/go-gcm).
* `    17` [gosd](https://github.com/alexsniffin/gosd) - A library for scheduling when to dispatch a message to a channel.
* `   144` [guble](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence.
* `     8` [hare](https://github.com/leozz37/hare) - A user friendly library for sending messages and listening to TCP sockets.
* `    89` [hub](https://github.com/leandro-lugaresi/hub) - A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges.
* `    13` [jazz](https://github.com/socifi/jazz) - A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages.
* `  4832` [machinery](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing.
* `   359` [mangos](https://github.com/nanomsg/mangos) - Pure go implementation of the Nanomsg ("Scalability Protocols") with transport interoperability.
* `  2027` [melody](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling.
* `  2245` [Mercure](https://github.com/dunglas/mercure) - Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events).
* `   156` [messagebus](https://github.com/vardius/message-bus) - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD.
* `  3161` [NATS Go Client](https://github.com/nats-io/nats) - Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library.
* `    66` [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel.
* `   105` [oplog](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs.
* [pubsub](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go.
* `    85` [rabbus](https://github.com/rafaeljesus/rabbus) - A tiny wrapper over amqp exchanges and queues.
* `   163` [rabtap](https://github.com/jandelgado/rabtap) - RabbitMQ swiss army knife cli app.
* `    59` [RapidMQ](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue.
* `    44` [redisqueue](https://github.com/robinjoseph08/redisqueue) - redisqueue provides a producer and consumer of a queue that uses Redis streams.
* `    13` [rmqconn](https://github.com/sbabiv/rmqconn) - RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed.
* `  6664` [sarama](https://github.com/Shopify/sarama) - Go library for Apache Kafka.
* `  1223` [Uniqush-Push](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices.
* `   883` [zmq4](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for `   131` [version 3](https://github.com/pebbe/zmq3) and `    18` [version 2](https://github.com/pebbe/zmq2).

## Microsoft Office

* `  2679` [unioffice](https://github.com/unidoc/unioffice) - Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents.

### Microsoft Excel

*Libraries for working with Microsoft Excel.*

* `  7744` [excelize](https://github.com/360EntSecGroup-Skylar/excelize) - Golang library for reading and writing Microsoft Excel™ (XLSX) files.
* `   113` [go-excel](https://github.com/szyhf/go-excel) - A simple and light reader to read a relate-db-like excel as a table.
* `    15` [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files.
* `  4716` [xlsx](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.
* `   128` [xlsx](https://github.com/plandem/xlsx) - Fast and safe way to read/update your existing Microsoft Excel files in Go programs.

## Miscellaneous

### Dependency Injection

*Libraries for working with dependency injection.*

* `    43` [alice](https://github.com/magic003/alice) - Additive dependency injection container for Golang.
* `   134` [container](https://github.com/golobby/container) - A powerful IoC Container with fluent and easy-to-use interface.
* `    56` [di](https://github.com/goava/di) - A dependency injection container for go programming language.
* `  1731` [dig](https://github.com/uber-go/dig) - A reflection based dependency injection toolkit for Go.
* `    94` [dingo](https://github.com/i-love-flamingo/dingo) - A dependency injection toolkit for Go, based on Guice.
* `  1697` [fx](https://github.com/uber-go/fx) - A dependency injection based application framework for Go (built on top of dig).
* `    14` [gocontainer](https://github.com/vardius/gocontainer) - Simple Dependency Injection Container.
* `    63` [goioc/di](https://github.com/goioc/di) - Spring-inspired Dependency Injection Container.
* `    27` [linker](https://github.com/logrange/linker) - A reflection based dependency injection and inversion of control library with components lifecycle support.
* `    33` [wire](https://github.com/Fs02/wire) - Strict Runtime Dependency Injection for Golang.

### Project Layout

*Unofficial set of patterns for structuring projects.*

* `   421` [cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) - A Go application boilerplate template for quick starting projects following production best practices.
* `    82` [go-sample](https://github.com/zitryss/go-sample) - A sample layout for Go application projects with the real code.
* `    43` [go-todo-backend](https://github.com/Fs02/go-todo-backend) - Go Todo Backend example using modular project layout for product microservice.
* ` 20227` [golang-standards/project-layout](https://github.com/golang-standards/project-layout) - Set of common historical and emerging project layout patterns in the Go ecosystem.
* `   832` [modern-go-application](https://github.com/sagikazarmark/modern-go-application) - Go application boilerplate and example applying modern practices.
* `    92` [scaffold](https://github.com/catchplay/scaffold) - Scaffold generates a starter Go project layout. Lets you focus on business logic implemented.

### Strings

*Libraries for working with strings.*

* [go-formatter](https://gitlab.com/tymonx/go-formatter) - Implements **replacement fields** surrounded by curly braces `{}` format strings.
* `    42` [gobeam/Stringy](https://github.com/gobeam/Stringy) - String manipulation library to convert string to camel case, snake case, kebab case / slugify etc.
* `   108` [strutil](https://github.com/ozgio/strutil) - String utilities.
* `   860` [xstrings](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages.

### Uncategorized

*These libraries were placed here because none of the other categories seemed to fit.*

* `    11` [anagent](https://github.com/mudler/anagent) - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection.
* `   192` [antch](https://github.com/antchfx/antch) - A fast, powerful and extensible web crawling & scraping framework.
* `  3036` [archiver](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives.
* `    32` [autoflags](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields.
* `    10` [avgRating](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation.
* `   306` [banner](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications.
* `  1004` [base64Captcha](https://github.com/mojocn/base64Captcha) - Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha.
* `   167` [battery](https://github.com/distatus/battery) - Cross-platform, normalized battery information library.
* `   141` [bitio](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go.
* `    35` [browscap_go](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](http://browscap.org/).
* `    71` [captcha](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation.
* `   363` [conv](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types.
* `    36` [datacounter](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter.
* `    26` [faker](https://github.com/pioz/faker) - Random fake data and struct generator for Go.
* `   209` [ffmt](https://github.com/go-ffmt/ffmt) - Beautify data display for Humans.
* `  1089` [gatus](https://github.com/TwinProduction/gatus) - Automated service health dashboard.
* `   326` [ghorg](https://github.com/gabrie30/ghorg) - Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, and Bitbucket.
* `   891` [go-commons-pool](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang.
* [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
* `  1125` [go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang.
* `   118` [go-unarr](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives.
* `  1366` [gofakeit](https://github.com/brianvoe/gofakeit) - Random data generator written in go.
* `    93` [gommit](https://github.com/antham/gommit) - Analyze git commit messages to ensure they follow defined patterns.
* `  5729` [gopsutil](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).
* `    24` [gosh](https://github.com/osamingo/gosh) - Provide Go Statistics Handler, Struct, Measure Method.
* `  1322` [gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS.
* `    88` [gotoprom](https://github.com/cabify/gotoprom) - Type-safe metrics builder wrapper library for the official Prometheus client.
* `   291` [gountries](https://github.com/pariz/gountries) - Package that exposes country and subdivision data.
* `   409` [health](https://github.com/dimiro1/health) - Easy to use, extensible health check library.
* `   155` [healthcheck](https://github.com/etherlabsio/healthcheck) - An opinionated and concurrent health-check HTTP handler for RESTful services.
* `     9` [hostutils](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking FQDNs list.
* `    76` [indigo](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58.
* `   181` [lk](https://github.com/hyperboloide/lk) - A simple licensing library for golang.
* `   625` [llvm](https://github.com/llir/llvm) - Library for interacting with LLVM IR in pure Go.
* `    18` [metrics](https://github.com/pascaldekloe/metrics) - Library for metrics instrumentation and Prometheus exposition.
* `    63` [morse](https://github.com/alwindoss/morse) - Library to convert to and from morse code.
* `     4` [numa](https://github.com/lrita/numa) - NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code.
* `    48` [pdfgen](https://github.com/hyperboloide/pdfgen) - HTTP service to generate PDF from Json requests.
* `    45` [persian](https://github.com/mavihq/persian) - Some utilities for Persian language in go.
* `    26` [sandid](https://github.com/aofei/sandid) - Every grain of sand on earth has its own ID.
* `    12` [shellwords](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell.
* `   633` [shortid](https://github.com/teris-io/shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs.
* `   142` [shoutrrr](https://github.com/containrrr/shoutrrr) - Notification library providing easy access to various messaging services like slack, mattermost, gotify and smtp among others.
* `   209` [stateless](https://github.com/qmuntal/stateless) - A fluent library for creating state machines.
* `   145` [stats](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...
* `   115` [turtle](https://github.com/hackebrot/turtle) - Emojis for Go.
* `    25` [url-shortener](https://github.com/pantrif/url-shortener) - A modern, powerful, and robust URL shortener microservice with mysql support.
* `     4` [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and output handling.
* `    23` [xdg](https://github.com/rkoesters/xdg) - FreeDesktop.org (xdg) Specs implemented in Go.
* `    50` [xkg](https://github.com/go-xkg/xkg) - X Keyboard Grabber.

## Natural Language Processing

*Libraries for working with human languages.*

* `     6` [detectlanguage](https://github.com/detectlanguage/detectlanguage-go) - Language Detection API Go Client. Supports batch requests, short phrase or single word language detection.
* `   106` [getlang](https://github.com/rylans/getlang) - Fast natural language detection package.
* `  1535` [go-i18n](https://github.com/nicksnyder/go-i18n/) - Package and an accompanying tool to work with localized text.
* `    11` [go-localize](https://github.com/m1/go-localize) - Simple and easy to use i18n (Internationalization and localization) engine - used for translating locale strings.
* `    25` [go-mystem](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer.
* `    88` [go-nlp](https://github.com/nuance/go-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work.
* `   880` [go-pinyin](https://github.com/mozillazg/go-pinyin) - CN Hanzi to Hanyu Pinyin converter.
* `    58` [go-stem](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm.
* `    81` [go-unidecode](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text.
* `    41` [go2vec](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings.
* `  1358` [gojieba](https://github.com/yanyiwu/gojieba) - This is a Go implementation of ` 25154` [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm.
* `    18` [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2.
* `     4` [gosentiwordnet](https://github.com/dinopuguh/gosentiwordnet) - Sentiment analyzer using sentiwordnet lexicon in Go.
* `     9` [gotokenizer](https://github.com/xujiajun/gotokenizer) - A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation)
* `    72` [gounidecode](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go.
* `     9` [govader](https://github.com/jonreiter/govader) - Go implementation of `  2715` [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment).
* `  1494` [gse](https://github.com/go-ego/gse) - Go efficient text segmentation; support english, chinese, japanese and other.
* `    19` [icu](https://github.com/goodsign/icu) - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1.
* `    16` [iuliia-go](https://github.com/mehanizm/iuliia-go) - Transliterate Cyrillic → Latin in every possible way.
* `   543` [kagome](https://github.com/ikawaha/kagome) - JP morphological analyzer written in pure Go.
* `    10` [libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2.
* `    59` [MMSEGO](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm.
* `   368` [nlp](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp.
* `   293` [nlp](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis).
* `    26` [paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm.
* `    33` [petrovich](https://github.com/striker2000/petrovich) - Petrovich is the library which inflects Russian names to given grammatical case.
* `     8` [porter](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm.
* `    39` [porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer.
* `  2657` [prose](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only.
* `    73` [RAKE.go](https://github.com/afjoseph/RAKE.Go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE).
* `    54` [segment](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/)
* `   291` [sentences](https://github.com/neurosnap/sentences) - Sentence tokenizer: converts text into a list of sentences.
* `    12` [shamoji](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go.
* `    28` [snowball](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/).
* `    49` [stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers.
* `    64` [textcat](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text.
* `     7` [transliterator](https://github.com/alexsergivan/transliterator) - Provides one-way string transliteration with supporting of language-specific transliteration rules.
* `   465` [whatlanggo](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc).
* `  1104` [when](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules.

## Networking

*Libraries for working with various layers of the network.*

* `   236` [arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826.
* `   242` [buffstreams](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy.
* `   142` [canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252).
* `   561` [cidranger](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup for Go.
* `    68` [dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315.
* `  5067` [dns](https://github.com/miekg/dns) - Go library for working with DNS.
* `    68` [ether](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames.
* `   211` [ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags.
* ` 14165` [fasthttp](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http.
* `  1679` [fortio](https://github.com/fortio/fortio) - Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC.
* `   765` [ftp](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959).
* `   249` [gaio](https://github.com/xtaci/gaio) - High performance async-io networking for Golang in proactor mode.
* `  1006` [gev](https://github.com/Allenxuxu/gev) - gev is a lightweight, fast non-blocking TCP network library based on Reactor mode.
* `   234` [gmqtt](https://github.com/DrmagicE/gmqtt) - Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1.
* `  3421` [gnet](https://github.com/panjf2000/gnet) - `gnet` is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go.
* `   164` [gNxI](https://github.com/google/gnxi) - A collection of tools for Network Management that use the gNMI and gNOI protocols.
* `  1061` [go-getter](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL.
* `    22` [go-powerdns](https://github.com/joeig/go-powerdns) - PowerDNS API bindings for Golang.
* `   401` [go-stun](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389).
* `  2106` [gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language.
* `    11` [gohooks](https://github.com/averageflow/gohooks) - GoHooks make it easy to send and consume secured web-hooks from a Go application. Inspired by Spatie's Laravel Webhook Client and Server.
* `    19` [golibwireshark](https://github.com/sunwxg/golibwireshark) - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data.
* `  3830` [gopacket](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings.
* `   408` [gopcap](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap.
* `    10` [goshark](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet.
* `   662` [gosnmp](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions.
* `   476` [gotcp](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications.
* `   780` [grab](https://github.com/cavaliercoder/grab) - Go package for managing file downloads.
* `    26` [graval](https://github.com/koofr/graval) - Experimental FTP server framework.
* `  3641` [HTTPLab](https://github.com/gchaincl/httplab) - HTTPLabs let you inspect HTTP requests and forge responses.
* `     7` [httpproxy](https://github.com/wzshiming/httpproxy) - HTTP proxy handler and dialer.
* `    42` [iplib](https://github.com/c-robinson/iplib) - Library for working with IP addresses (net.IP, net.IPNet), inspired by python [ipaddress](https://docs.python.org/3/library/ipaddress.html) and ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html)
* `   163` [jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices.
* `  2821` [kcp-go](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol.
* ` 12228` [kcptun](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol.
* `   598` [lhttp](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily.
* `    50` [linkio](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces.
* `    11` [llb](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response.
* `   712` [mdns](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang.
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
* `  1014` [NFF-Go](https://github.com/intel-go/nff-go) - Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF).
* `    54` [packet](https://github.com/aerogo/packet) - Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed.
* `    17` [panoptes-stream](https://github.com/yahoo/panoptes-stream) - A cloud native distributed streaming network telemetry (gNMI, Juniper JTI and Cisco MDT).
* `   459` [peerdiscovery](https://github.com/schollz/peerdiscovery) - Pure Go library for cross-platform local peer discovery using UDP multicast.
* `    43` [portproxy](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it.
* `    21` [publicip](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress).
* `  4771` [quic-go](https://github.com/lucas-clemente/quic-go) - An implementation of the QUIC protocol in pure Go.
* `   376` [raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface.
* `   946` [sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt.
* `  1794` [ssh](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh).
* `   131` [sslb](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance.
* `   433` [stun](https://github.com/go-rtc/stun) - Go implementation of RFC 5389 STUN protocol.
* `   346` [tcp_server](https://github.com/firstrow/tcp_server) - Go library for building tcp servers faster.
* `     8` [tspool](https://github.com/two/tspool) - A TCP Library use worker pool to improve performance and protect your server.
* `   154` [utp](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation.
* `   695` [vssh](https://github.com/yahoo/vssh) - Go library for building network and server automation over SSH protocol.
* `  1150` [water](https://github.com/songgao/water) - Simple TUN/TAP library.
* `  6168` [webrtc](https://github.com/pions/webrtc) - A pure Go implementation of the WebRTC API.
* `   282` [winrm](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines.
* `   108` [xtcp](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication, graceful shutdown, and custom protocol.

### HTTP Clients

*Libraries for making HTTP requests.*

* `   859` [gentleman](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library.
* `    15` [go-http-client](https://github.com/bozd4g/go-http-client) - Make http calls simply and easily.
* `  1711` [grequests](https://github.com/levigross/grequests) - A Go "clone" of the great and famous Requests library.
* `  1713` [heimdall](https://github.com/gojektech/heimdall) - An enchanced http client with retry and hystrix capabilities.
* `    10` [httpretry](https://github.com/ybbus/httpretry) - Enriches the default go HTTP client with retry functionality.
* `   532` [pester](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency.
* `    78` [request](https://github.com/monaco-io/request) - HTTP client for golang. If you have experience about axios or requests, you will love it. No 3rd dependency.
* `  3658` [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.
* `    37` [rq](https://github.com/ddo/rq) - A nicer interface for golang stdlib HTTP client.
* `  1229` [sling](https://github.com/dghubble/sling) - Sling is a Go HTTP client library for creating and sending API requests.

## OpenGL

*Libraries for using OpenGL in Go.*

* `   771` [gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow).
* `  1031` [glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3.
* `     1` [go-glmatrix](https://github.com/technohippy/go-glmatrix) - Go port of [glMatrix](http://glmatrix.net/) library.
* `   144` [goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).
* `    68` [goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events.
* `   353` [mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM.

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* `    31` [beego orm](https://github.com/astaxie/beego/tree/master/orm) - Powerful orm framework for go. Support: pq/mysql/sqlite3.
* `  6225` [ent](https://github.com/facebook/ent) - An entity framework for Go. Simple, yet powerful ORM for modeling and querying data.
* `    21` [go-firestorm](https://github.com/jschoedt/go-firestorm) - A simple ORM for Google/Firebase Cloud Firestore.
* `  4274` [go-pg](https://github.com/go-pg/pg) - PostgreSQL ORM with focus on PostgreSQL specific features and performance.
* `   578` [go-queryset](https://github.com/jirfag/go-queryset) - 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM.
* `   133` [go-sql](https://github.com/rushteam/gosql) - A easy ORM for mysql.
* `   506` [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) - A flexible and powerful SQL string builder library plus a zero-config ORM.
* `   100` [go-store](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go.
* ` 22220` [GORM](https://github.com/go-gorm/gorm) - The fantastic ORM library for Golang, aims to be developer friendly.
* `   940` [gormt](https://github.com/xxjwxc/gormt) - Mysql database to golang gorm struct.
* `  3461` [gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go.
* `   149` [grimoire](https://github.com/Fs02/grimoire) - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3).
* `     6` [lore](https://github.com/abrahambotros/lore) - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go.
* `     4` [marlow](https://github.com/marlow/marlow) - Generated ORM from project structs for compile time safety assurances.
* `  1002` [pop/soda](https://github.com/gobuffalo/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* `   553` [QBS](https://github.com/coocood/qbs) - Stands for Query By Struct. A Go ORM.
* `  1047` [reform](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation.
* `   295` [rel](https://github.com/go-rel/rel) - Modern Database Access Layer for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API.
* `  3582` [SQLBoiler](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema.
* `  2429` [upper.io/db](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.
* [XORM](https://gitea.com/xorm/xorm) - Simple and powerful ORM for Go. (Support: MySQL, MyMysql, PostgreSQL, Tidb, SQLite3, MsSql and Oracle).
* `   270` [Zoom](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis.

## Package Management

*Official tooling for dependency and package management*

* [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) - Modules are the unit of source code interchange and versioning. The go command has direct support for working with modules, including recording and resolving dependencies on other modules.

*Official experimental tooling for package management*

* ` 13225` [dep](https://github.com/golang/dep) - Go dependency tool.
* [vgo](https://go.googlesource.com/vgo/) - Versioned Go.

*Unofficial libraries for package and dependency management.*

* `  8075` [glide](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip.
* `  5629` [godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.
* `  1389` [gom](https://github.com/mattn/gom) - Go Manager - bundle for go.
* `   780` [goop](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler.
* `    49` [gop](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH.
* `  2498` [gopm](https://github.com/gpmgo/gopm) - Go Package Manager.
* `  5014` [govendor](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file.
* `  1202` [gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go.
* `   215` [johnny-deps](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git.
* `   355` [modgv](https://github.com/lucasepe/modgv) - Converts 'go mod graph' output into Graphviz's DOT language.
* `   115` [mvn-golang](https://github.com/raydac/mvn-golang) - plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure.
* `   242` [nut](https://github.com/jingweno/nut) - Vendor Go dependencies.
* `   120` [VenGO](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments.

## Performance

* ` 12522` [jaeger](https://github.com/jaegertracing/jaeger) - A distributed tracing system.
* `   505` [pixie](https://github.com/pixie-labs/pixie) - No instrumentation tracing for Golang applications via eBPF.
* `  1358` [profile](https://github.com/pkg/profile) - Simple profiling support package for Go.
* `   965` [statsviz](https://github.com/arl/statsviz) - Live visualization of your Go application runtime statistics.
* `    42` [tracer](https://github.com/kamilsk/tracer) - Simple, lightweight tracing.

## Query Language

* `    22` [api-fu](https://github.com/ccbrown/api-fu) - Comprehensive GraphQL implementation.
* `   676` [dasel](https://github.com/tomwright/dasel) - Query and update data structures using selectors from the command line. Comparable to jq/yq but supports JSON, YAML, TOML and XML with zero runtime dependencies.
* `  1587` [gojsonq](https://github.com/thedevsaddam/gojsonq) - A simple Go package to Query over JSON Data.
* `    52` [graphql](https://github.com/tmc/graphql) - graphql parser + utilities.
* `  3567` [graphql](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use.
* `  7161` [graphql-go](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go.
* `     4` [gws](https://github.com/Zaba505/gws) - Apollos' "GraphQL over Websocket" client and server implementation.
* `   241` [jsonql](https://github.com/elgs/jsonql) - JSON query expression library in Golang.
* `    49` [jsonslice](https://github.com/bhmj/jsonslice) - Jsonpath queries with advanced filters.
* `   183` [rql](https://github.com/a8m/rql) - Resource Query Language for REST API.
* `    14` [rqp](https://github.com/timsolov/rest-query-parser) - Query Parser for REST API. Filtering, validations, both `AND`, `OR` operations are supported directly in the query.
* `    22` [straf](https://github.com/SonicRoshan/straf) - Easily Convert Golang structs to GraphQL objects.

## Resource Embedding

* `   587` [esc](https://github.com/mjibson/esc) - Embeds files into Go programs and provides http.FileSystem interfaces to them.
* `   579` [fileb0x](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use.
* `    28` [go-embed](https://github.com/pyros2097/go-embed) - Generates go code to embed resource files into your library or executable.
* `   171` [go-resources](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go.
* `  2142` [go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as HTML, JS, CSS, images, and templates very easy.
* `     8` [mule](https://github.com/wlbr/mule) - Embed external resources like images, movies ... into Go source code to create single file binaries using `go generate`. Focussed on simplicity.
* `  3115` [packr](https://github.com/gobuffalo/packr) - The simple and easy way to embed static files into Go binaries.
* `    62` [statics](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks.
* `  3057` [statik](https://github.com/rakyll/statik) - Embeds static files into a Go executable.
* `    25` [templify](https://github.com/wlbr/templify) - Embed external template files into Go code to create single file binaries.
* `   918` [vfsgen](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem.

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* `     6` [assocentity](https://github.com/ndabAP/assocentity) - Package assocentity returns the average distance from words to a given entity.
* `     4` [bradleyterry](https://github.com/seanhagen/bradleyterry) - Provides a Bradley-Terry Model for pairwise comparisons.
* `   232` [calendarheatmap](https://github.com/nikolaydubina/calendarheatmap) - Calendar heatmap in plain Go inspired by Github contribution activity.
* `   661` [chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types.
* `   415` [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) - Dataframes for machine-learning and statistics (similar to pandas).
* `    19` [decimal](https://github.com/db47h/decimal) - Package decimal implements arbitrary-precision decimal floating-point arithmetic.
* `    44` [evaler](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator.
* `   317` [ewma](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages.
* `    46` [geom](https://github.com/skelterjohn/geom) - 2D geometry for golang.
* `   706` [go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go.
* `     5` [go-gt](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language.
* `    21` [goent](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures.
* `   149` [gohistogram](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams.
* `  4490` [gonum](https://github.com/gonum/gonum) - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more.
* `  1778` [gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go.
* `   637` [goraph](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorith visualization).
* `  1544` [gosl](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more.
* `    14` [GoStats](https://github.com/OGFris/GoStats) - GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions.
* `   401` [graph](https://github.com/yourbasic/graph) - Library of basic graph algorithms.
* `    12` [ode](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions.
* `   354` [orb](https://github.com/paulmach/orb) - 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support.
* `    66` [pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go.
* `    14` [piecewiselinear](https://github.com/sgreben/piecewiselinear) - Tiny linear interpolation library.
* `    13` [PiHex](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi.
* `     4` [rootfinding](https://github.com/khezen/rootfinding) - root-finding algorithms library for finding roots of quadratic functions.
* `   107` [sparse](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries.
* `  1880` [stats](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library.
* `  1315` [streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data.
* `   119` [TextRank](https://github.com/DavidBelicza/TextRank) - TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support.
* `    19` [triangolatte](https://github.com/tchayen/triangolatte) - 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs.

## Security

*Libraries that are used to help make your application more secure.*

* `  1824` [acmetool](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal.
* `   683` [acra](https://github.com/cossacklabs/acra) - Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system.
* `    12` [argon2-hashing](https://github.com/andskur/argon2-hashing) - light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package.
* `    85` [argon2pw](https://github.com/raja/argon2pw) - Argon2 password hash generation with constant-time password comparison.
* [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) - Auto provision Let's Encrypt certificates and start a TLS server.
* `   291` [BadActor](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban.
* `  2435` [Cameradar](https://github.com/Ullaakut/cameradar) - Tool and library to remotely hack RTSP streams from surveillance cameras.
* `    20` [certificates](https://github.com/mvmaasakkers/certificates) - An opinionated tool for generating tls certificates.
* `   296` [firewalld-rest](https://github.com/prashantgupta24/firewalld-rest) - A rest application to dynamically update firewalld rules on a linux server.
* `    15` [go-generate-password](https://github.com/m1/go-generate-password) - Password generator that can be used on the cli or as a library.
* `   248` [go-password-validator](https://github.com/lane-c-wagner/go-password-validator) - Password validator based on raw cryptographic entropy values.
* `   195` [go-yara](https://github.com/hillu/go-yara) - Go Bindings for `   112` [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)".
* `    13` [goArgonPass](https://github.com/dwin/goArgonPass) - Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations.
* `    38` [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) - A probably paranoid package for securely hashing and encrypting passwords.
* [Interpol](https://bitbucket.org/vahidi/interpol) - Rule-based data generator for fuzzing and penetration testing.
* `  4386` [lego](https://github.com/go-acme/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt).
* `  1835` [memguard](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory.
* `   491` [nacl](https://github.com/kevinburke/nacl) - Go implementation of the NaCL set of API's.
* `   248` [optimus-go](https://github.com/pjebs/optimus-go) - ID hashing and Obfuscation using Knuth's Algorithm.
* `   239` [passlib](https://github.com/hlandau/passlib) - Futureproof password hashing library.
* `  1597` [secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins.
* `    12` [secureio](https://github.com/xaionaro-go/secureio) - An keyexchanging+authenticating+encrypting wrapper and multiplexer for `io.ReadWriteCloser` based on XChaCha20-poly1305, ECDH and ED25519.
* `   163` [simple-scrypt](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in.
* `   267` [ssh-vault](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys.
* `    10` [sslmgr](https://github.com/adrianosela/sslmgr) - SSL certificates made easy with a high level wrapper around acme/autocert.
* `  1184` [themis](https://github.com/cossacklabs/themis) - high-level cryptographic library for solving typical data security tasks (secure data storage, secure messaging, zero-knowledge proof authentication), available for 14 languages, best fit for multi-platform apps.

## Serialization

*Libraries and tools for binary serialization.*

* `    47` [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang.
* `    61` [bambam](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go.
* `    11` [bel](https://github.com/32leaves/bel) - Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC.
* `    26` [binstruct](https://github.com/ghostiam/binstruct) - Golang binary decoder for mapping data into the structure.
* `   228` [cbor](https://github.com/fxamacker/cbor) - Small, safe, and easy CBOR encoding and decoding library.
* `   582` [colfer](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format.
* `   444` [csvutil](https://github.com/jszwec/csvutil) - High Performance, idiomatic CSV record encoding and decoding to native Go structures.
* `    13` [elastic](https://github.com/epiclabs-io/elastic) - Convert slices, maps or any other unknown value across different types at run-time, no matter what.
* `     5` [fixedwidth](https://github.com/huydang284/fixedwidth) - Fixed-width text formatting (UTF-8 supported).
* `    14` [fwencoder](https://github.com/o1egl/fwencoder) - Fixed width file parser (encoding and decoding library) for Go.
* `   278` [go-capnproto](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go.
* `  1488` [go-codec](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support.
* `     2` [go-lctree](https://github.com/sbourlon/go-lctree) - Provides a CLI and primitives to serialize and deserialize [LeetCode binary trees](https://support.leetcode.com/hc/en-us/articles/360011883654-What-does-1-null-2-3-mean-in-binary-tree-representation).
* `  4263` [gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets.
* `  7328` [goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.
* `  8695` [jsoniter](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json".
* `  4038` [mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures.
* `   142` [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions.
* `    11` [pletter](https://github.com/vimeda/pletter) - A standard way to wrap a proto message for message brokers.
* `   117` [structomap](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures.

## Server Applications

* `  1766` [algernon](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber.
* ` 31447` [Caddy](https://github.com/caddyserver/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use.
* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* `  3077` [devd](https://github.com/cortesi/devd) - Local webserver for developers.
* `  1244` [discovery](https://github.com/Bilibili/discovery) - A registry for resilient mid-tier load balancing and failover.
* `   119` [dudeldu](https://github.com/krotik/dudeldu) - A simple SHOUTcast server.
* ` 34181` [etcd](https://github.com/coreos/etcd) - Highly-available key value store for shared configuration and service discovery.
* `  1399` [Fider](https://github.com/getfider/fider) - Fider is an open platform to collect and organize customer feedback.
* `  1437` [Flagr](https://github.com/checkr/flagr) - Flagr is an open-source feature flagging and A/B testing service.
* `  1368` [flipt](https://github.com/markphelps/flipt) - A self contained feature flag solution written in Go and Vue.js
* `     4` [go-proxy-cache](https://github.com/fabiocicerchia/go-proxy-cache) - Simple Reverse Proxy with Caching, written in Go, using Redis.
* `   868` [jackal](https://github.com/ortuman/jackal) - An XMPP server written in Go.
* `    47` [lets-proxy2](https://github.com/rekby/lets-proxy2) - Reverse proxy for handle https with issue certificates in fly from lets-encrypt.
* ` 25296` [minio](https://github.com/minio/minio) - Minio is a distributed object storage server.
* `    16` [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) - Nginx log parser and exporter to Prometheus.
* [nsq](http://nsq.io/) - A realtime distributed messaging platform.
* `     6` [protoxy](https://github.com/camgraff/protoxy) - A proxy server that converts JSON request bodies to Protocol Buffers.
* `    26` [psql-streamer](https://github.com/blind-oracle/psql-streamer) - Stream database events from PostgreSQL to Kafka.
* [riemann-relay](https://github.com/blind-oracle/riemann-relay) - Relay to load-balance Riemann events and/or convert them to Carbon.
* `  4748` [RoadRunner](https://github.com/spiral/roadrunner) - High-performance PHP application server, load-balancer and process manager.
* `  2166` [SFTPGo](https://github.com/drakkan/sftpgo) - Fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. It can serve local filesystem and Cloud Storage backends such as S3 and Google Cloud Storage.
* `     8` [simple-jwt-provider](https://github.com/leberKleber/simple-jwt-provider) - Simple and lightweight provider which exhibits JWTs, supports login, password-reset (via mail) and user management.
* `  1265` [Trickster](https://github.com/tricksterproxy/trickster) - HTTP reverse proxy cache and time series accelerator.

## Stream Processing

*Libraries and tools for stream processing and reactive programming.*

* `   574` [go-streams](https://github.com/reugn/go-streams) - Go stream processing library.
* `    60` [machine](https://github.com/whitaker-io/machine) - Go library for writing and generating stream workers with built in metrics and traceability.
* `    20` [stream](https://github.com/youthlin/stream) - Go Stream, like Java 8 Stream: Filter/Map/FlatMap/Peek/Sorted/ForEach/Reduce...

## Template Engines

*Libraries and tools for templating and lexing.*

* `   797` [ace](https://github.com/yosssi/ace) - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold.
* `   866` [amber](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade.
* `    24` [damsel](https://github.com/dskinner/damsel) - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others.
* `   456` [ego](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled.
* `    30` [extemplate](https://github.com/dannyvankooten/extemplate) - Tiny wrapper around html/template to allow for easy file-based template inheritance.
* `   462` [fasttemplate](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/).
* `  3714` [gofpdf](https://github.com/jung-kurt/gofpdf) - PDF document generator with high level support for text, drawing and images.
* `    20` [gospin](https://github.com/m1/gospin) - Article spinning and spintax/spinning syntax engine, useful for A/B, testing pieces of text/articles and creating more natural conversations.
* `   199` [goview](https://github.com/foolin/goview) - Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application.
* `  1427` [hero](https://github.com/shiyanhui/hero) - Hero is a handy, fast and powerful go template engine.
* `   730` [jet](https://github.com/CloudyKit/jet) - Jet template engine.
* `    72` [kasia.go](https://github.com/ziutek/kasia.go) - Templating system for HTML and other text documents - go implementation.
* `   113` [liquid](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates.
* `   289` [maroto](https://github.com/johnfercher/maroto) - A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple.
* `  1001` [mustache](https://github.com/hoisie/mustache) - Go implementation of the Mustache template language.
* `  1846` [pongo2](https://github.com/flosch/pongo2) - Django-like template-engine for Go.
* `  1950` [quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.
* `   409` [raymond](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go.
* `   765` [Razor](https://github.com/sipin/gorazor) - Razor view engine for Golang.
* `   154` [Soy](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/).
* `    74` [velvet](https://github.com/gobuffalo/velvet) - Complete handlebars implementation in Go.

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
  * [apitest](https://apitest.dev) - Simple and extensible behavioural testing library for REST based services or HTTP handlers that supports mocking external http calls and rendering of sequence diagrams.
  * `    26` [assert](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions.
  * `    10` [badio](https://github.com/cavaliercoder/badio) - Extensions to Go's `testing/iotest` package.
  * `   694` [baloo](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy.
  * `    10` [biff](https://github.com/fulldump/biff) - Bifurcation testing framework, BDD compatible.
  * `   195` [charlatan](https://github.com/percolate/charlatan) - Tool to generate fake interface implementations for tests.
  * `   172` [commander](https://github.com/SimonBaeumer/commander) - Tool for testing cli applications on windows, linux and osx.
  * `    32` [covergates](https://github.com/covergates/covergates) - Self-hosted code coverage report review and management service.
  * `   125` [cupaloy](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework.
  * `   120` [dbcleaner](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby.
  * `    36` [dsunit](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files.
  * `    85` [embedded-postgres](https://github.com/fergusstrange/embedded-postgres) - Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test.
  * `   170` [endly](https://github.com/viant/endly) - Declarative end to end functional testing.
  * `    15` [flute](https://github.com/suzuki-shunsuke/flute) - HTTP client testing framework.
  * `   263` [frisby](https://github.com/verdverm/frisby) - REST API testing framework.
  * [ginkgo](http://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
  * `   336` [gnomock](https://github.com/orlangure/gnomock) - integration testing with real dependencies (database, cache, even Kubernetes or AWS) running in Docker, without mocks.
  * `   211` [go-carpet](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal.
  * `  2084` [go-cmp](https://github.com/google/go-cmp) - Package for comparing Go values in tests.
  * `    25` [go-hit](https://github.com/Eun/go-hit) - Hit is an http integration test framework written in golang.
  * `   376` [go-mutesting](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code.
  * `   115` [go-testdeep](https://github.com/maxatome/go-testdeep) - Extremely flexible golang deep comparison, extends the go testing package.
  * `   477` [go-vcr](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests.
  * `   734` [goblin](https://github.com/franela/goblin) - Mocha like testing framework fo Go.
  * `   261` [goc](https://github.com/qiniu/goc) - Goc is a comprehensive coverage testing system for The Go Programming Language.
  * [gocheck](http://labix.org/gocheck) - More advanced testing framework alternative to gotest.
  * `  6100` [GoConvey](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload.
  * `    75` [gocrest](https://github.com/corbym/gocrest) - Composable hamcrest-like matchers for Go assertions.
  * `  1230` [godog](https://github.com/DATA-DOG/godog) - Cucumber or Behat like BDD framework for Go.
  * `   354` [gofight](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework.
  * `     9` [gogiven](https://github.com/corbym/gogiven) - YATSPEC-like BDD testing framework for Go.
  * `    40` [gomatch](https://github.com/jfilipczyk/gomatch) - library created for testing JSON against patterns.
  * [gomega](http://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
  * `   115` [GoSpec](https://github.com/orfjackal/gospec) - BDD-style testing framework for the Go programming language.
  * `    54` [gospecify](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.
  * `     9` [gosuite](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests.
  * `   186` [gotest.tools](https://github.com/gotestyourself/gotest.tools) - A collection of packages to augment the go testing package and support common patterns.
  * `    27` [Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
  * `  1574` [httpexpect](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing.
  * `    54` [jsonassert](https://github.com/kinbiko/jsonassert) - Package for verifying that your JSON payloads are serialized correctly.
  * `    52` [restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test.
  * `    14` [schema](https://github.com/jgroeneveld/schema) - Quick and easy expression matching for JSON schemas used in requests and responses.
  * `     5` [stop-and-go](https://github.com/elgohr/stop-and-go) - Testing helper for concurrency.
  * `    54` [testcase](https://github.com/adamluzsi/testcase) - Idiomatic testing framework for Behavior Driven Development.
  * `   592` [testfixtures](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications.
  * ` 12195` [Testify](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package.
  * [testmd](https://godoc.org/github.com/tvastar/test/cmd/testmd) - Convert markdown snippets into testable go code.
  * `    10` [testsql](https://github.com/zhulongcheng/testsql) - Generate test data from SQL files before testing and clear it after finished.
  * `     4` [trial](https://github.com/jgroeneveld/trial) - Quick and easy extendable assertions without introducing much boilerplate.
  * `     5` [Tt](https://github.com/vcaesar/tt) - Simple and colorful test tools.
  * `    81` [wstest](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler.

* Mock
  * `   462` [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects.
  * `     7` [go-localstack](https://github.com/elgohr/go-localstack) - Tool for using localstack in AWS testing.
  * `  3044` [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions.
  * `   325` [go-txdb](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes.
  * `  1128` [gock](https://github.com/h2non/gock) - Versatile HTTP mocking made easy.
  * `  5019` [gomock](https://github.com/golang/mock) - Mocking framework for the Go programming language.
  * `    93` [govcr](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing.
  * `  1682` [hoverfly](https://github.com/SpectoLabs/hoverfly) - HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI.
  * `   950` [httpmock](https://github.com/jarcoal/httpmock) - Easy mocking of HTTP responses from external resources.
  * `   335` [minimock](https://github.com/gojuno/minimock) - Mock generator for Go interfaces.
  * `    22` [mockhttp](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter.
  * `    52` [timex](https://github.com/cabify/timex) - A test-friendly replacement for the native `time` package.

* Fuzzing and delta-debugging/reducing/shrinking.
  * `  3766` [go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing system.
  * `   943` [gofuzz](https://github.com/google/gofuzz) - Library for populating go objects with random values.
  * `   225` [Tavor](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework.

* Selenium and browser control tools.
  * `   505` [cdp](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it.
  * `  5682` [chromedp](https://github.com/knq/chromedp) - a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol.
  * `   266` [ggr](https://github.com/aerokube/ggr) - a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs.
  * `  1262` [rod](https://github.com/go-rod/rod) - A Devtools driver to make web automation and scraping easy.
  * `  1781` [selenoid](https://github.com/aerokube/selenoid) - alternative Selenium hub server that launches browsers within containers.

* Fail injection
  * `   547` [failpoint](https://github.com/pingcap/failpoint) - An implementation of [failpoints](http://www.freebsd.org/cgi/man.cgi?query=fail) for Golang.

## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats
  * `    68` [align](https://github.com/Guitarbum722/align) - A general purpose application that aligns text.
  * `    46` [allot](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots.
  * `     6` [bbConvert](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags.
  * `  4601` [blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go.
  * `  1747` [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer.
  * `    16` [codetree](https://github.com/aerogo/codetree) - Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure.
  * ` 12748` [colly](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers.
  * `   711` [commonregex](https://github.com/mingrammer/commonregex) - A collection of common regular expressions for Go.
  * `   443` [dataflowkit](https://github.com/slotix/dataflowkit) - Web scraping Framework to turn websites into structured data.
  * `    44` [did](https://github.com/ockam-network/did) - DID (Decentralized Identifiers) Parser and Stringer in Go.
  * `     6` [doi](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go.
  * `    80` [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go.
  * `    11` [enca](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](http://cihar.com/software/enca/).
  * `     3` [encdec](https://github.com/mickep76/encdec) - Package provides a generic interface to encoders and decodersa.
  * `    60` [genex](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings.
  * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.
  * `    50` [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) - Fixed-width text formatting (encoder/decoder with reflection).
  * `  2469` [go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format.
  * `   135` [go-nmea](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language.
  * `   318` [go-runewidth](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string.
  * `    65` [go-slugify](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support.
  * `   892` [go-toml](https://github.com/pelletier/go-toml) - Go library for the TOML format with query support and handy cli tools.
  * `    52` [go-vcard](https://github.com/emersion/go-vcard) - Parse and format vCard.
  * `    93` [go-zero-width](https://github.com/trubitsyn/go-zero-width) - Zero-width character detection and removal for Go.
  * `  1511` [gofeed](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go.
  * `   407` [gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language.
  * `   380` [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - Format bytes to string.
  * `    33` [gonameparts](https://github.com/polera/gonameparts) - Parses human names into individual name parts.
  * `   185` [goq](https://github.com/andrewstuart/goq) - Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery).
  * `  9634` [GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.
  * `    49` [goregen](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions.
  * `   180` [goribot](https://github.com/zhshch2002/goribot) - A simple golang spider/scraping framework,build a spider in 3 lines.
  * `   287` [gotext](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go.
  * `    51` [guesslanguage](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text.
  * `   129` [html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) - Convert HTML to Markdown. Even works with entire websites and can be extended through rules.
  * `   316` [htmlquery](https://github.com/antchfx/htmlquery) - An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression.
  * `  1295` [inject](https://github.com/facebookgo/inject) - Package inject provides a reflect based injector.
  * `     5` [ltsv](https://github.com/Wing924/ltsv) - High performance [LTSV (Labeled Tab Separated Value)](http://ltsv.org/) reader for Go.
  * `   431` [mxj](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.
  * `   115` [omniparser](https://github.com/jf-tech/omniparser) - A versatile ETL library that parses text input (CSV/txt/JSON/XML/EDI/X12/EDIFACT/etc) in streaming fashion and transforms data into JSON output using data-driven schema.
  * `    22` [pagser](https://github.com/foolin/pagser) - Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler.
  * `    85` [podcast](https://github.com/eduncan911/podcast) - iTunes Compliant and RSS 2.0 Podcast Generator in Golang
  * `   105` [sdp](https://github.com/gortc/sdp) - SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)].
  * `  3384` [sh](https://github.com/mvdan/sh) - Shell parser and formatter.
  * `   618` [slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support.
  * `    28` [Slugify](https://github.com/avelino/slugify) - Go slugify application that handles string.
  * `     7` [syndfeed](https://github.com/zhengchun/syndfeed) - A syndication feed for Atom 1.0 and RSS 2.0.
  * `  3400` [toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection).
* Utility
  * `    30` [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) - A sanitization-based swear filter for Go.
  * `   256` [gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go.
  * `    16` [kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms.
  * `     8` [parseargs-go](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes.
  * [parth](https://github.com/codemodus/parth) - URL path segmentation parsing.
  * `   165` [radix](https://github.com/yourbasic/radix) - fast string sorting algorithm.
  * `    27` [regroup](https://github.com/oriser/regroup) - Match regex expression named groups into go struct using struct tags and automatic parsing.
  * `    13` [Tagify](https://github.com/zoomio/tagify) - Produces a set of tags from given source.
  * `     2` [textwrap](https://github.com/isbm/textwrap) - Implementation of `textwrap` module from Python.
  * `     8` [TySug](https://github.com/Dynom/TySug) - Alternative suggestions with respect to keyboard layouts.
  * `    20` [xj2go](https://github.com/stackerzzq/xj2go) - Convert xml or json to go struct.
  * `   739` [xurls](https://github.com/mvdan/xurls) - Extract urls from text.

## Third-party APIs

*Libraries for accessing third party APIs.*

* `    14` [airtable](https://github.com/mehanizm/airtable) - Go client library for the [Airtable API](https://airtable.com/api).
* `    45` [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) - Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html).
* `  1069` [anaconda](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API.
* `  6328` [aws-sdk-go](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language.
* `    17` [brewerydb](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API.
* `    84` [cachet](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/).
* `    54` [circleci](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API.
* `    57` [clarifai](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API.
* `    16` [codeship-go](https://github.com/codeship/codeship-go) - Go client library for interacting with Codeship's API v2.
* `    11` [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) - Go client library for interacting with Coinpaprika's API.
* `  1714` [discordgo](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API.
* `   189` [ethrpc](https://github.com/onrik/ethrpc) - Go bindings for Ethereum JSON RPC API.
* `   934` [facebook](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API.
* `    39` [fcm](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging.
* `    49` [gads](https://github.com/emiddleton/gads) - Google Adwords Unofficial API.
* `    29` [gami](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface.
* `    29` [gcm](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging.
* `   385` [geo-golang](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](http://geocoder.opencagedata.com/api.html), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs.
* `  7087` [github](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3.
* `   738` [githubql](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4.
* `    10` [go-aws-news](https://github.com/circa10a/go-aws-news) - Go application and library to fetch what's new from AWS.
* `     3` [go-chronos](https://github.com/axelspringer/go-chronos) - Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler
* `    11` [go-hacknews](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API.
* `     9` [go-here](https://github.com/abdullahselek/go-here) - Go client library around the HERE location based APIs.
* `    19` [go-imgur](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com)
* `   837` [go-jira](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira)
* `   194` [go-marathon](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS.
* `    19` [go-myanimelist](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](http://myanimelist.net/modules.php?go=api).
* `    14` [go-postman-collection](https://github.com/rbretecher/go-postman-collection) - Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) (compatible with Insomnia).
* `     8` [go-sophos](https://github.com/esurdam/go-sophos) - Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies.
* `     6` [go-sptrans](https://github.com/sergioaugrod/go-sptrans) - Go client library for the SPTrans Olho Vivo API.
* [go-telegraph](https://gitlab.com/toby3d/telegraph) - Telegraph publishing platform API client.
* `   111` [go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github.
* `    20` [go-twitch](https://github.com/knspriggs/go-twitch) - Go client for interacting with the Twitch v3 API.
* `  1124` [go-twitter](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs.
* `    33` [go-unsplash](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API.
* `    43` [go-xkcd](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API.
* `    43` [gogtrends](https://github.com/groovili/gogtrends) - Google Trends Unofficial API.
* `    36` [golang-tmdb](https://github.com/cyruzin/golang-tmdb) - Golang wrapper for The Movie Database API v3.
* `    36` [golyrics](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website.
* `     8` [gomalshare](https://github.com/MonaxGT/gomalshare) - Go library MalShare API [malshare.com](http://www.malshare.com/)
* `    40` [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library.
* `  2514` [google](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go.
* `    12` [google-analytics](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting.
* `  2419` [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library.
* `     7` [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/).
* `     9` [google-play-scraper](https://github.com/n0madic/google-play-scraper) - Get data from Google Play Store.
* `     7` [gopaapi5](https://github.com/utekaravinash/gopaapi5) - Go Client Library for [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/).
* `    50` [gosip](https://github.com/koltyakov/gosip) - Go client library SharePoint API.
* `   127` [gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.
* `   106` [hipchat](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API.
* `   112` [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP.
* `    65` [igdb](https://github.com/Henry-Sarabia/igdb) - Go client for the [Internet Game Database API](https://api.igdb.com/).
* `     2` [kanka](https://github.com/Henry-Sarabia/kanka) - Go client for the [Kanka API](https://kanka.io/en-US/docs/1.0).
* `    17` [lastpass-go](https://github.com/ansd/lastpass-go) - Go client library for the [LastPass](https://www.lastpass.com/) API.
* `     3` [libgoffi](https://github.com/clevabit/libgoffi) - Library adapter toolbox for native [libffi](http://sourceware.org/libffi/) integration
* `   131` [Medium](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API.
* `    56` [megos](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster.
* `  1168` [minio-go](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage.
* `    36` [mixpanel](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.
* `    24` [patreon-go](https://github.com/mxpv/patreon-go) - Go library for Patreon API.
* `   399` [paypal](https://github.com/logpacker/PayPal-Go-SDK) - Wrapper for PayPal payment API.
* `     1` [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK.
* `    88` [pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API.
* `     2` [rawg-sdk-go](https://github.com/dimuska139/rawg-sdk-go) - Go library for the [RAWG Video Games Database](https://rawg.io/) API
* `     8` [rrdaclient](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP.
* `    21` [shopify](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API.
* `    47` [simples3](https://github.com/rhnvrm/simples3) - Simple no frills AWS S3 Library using REST with V4 Signing written in Go.
* [slack](https://github.com/nlopes/slack) - Slack API in Go.
* `    10` [smite](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API.
* `    31` [spotify](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API.
* `    21` [steam](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers.
* `  1284` [stripe](https://github.com/stripe/stripe-go) - Go client for the Stripe API.
* `    17` [textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API.
* `    30` [translate](https://github.com/poorny/translate) - Go online translation package.
* `   157` [Trello](https://github.com/adlio/trello) - Go wrapper for the Trello API.
* `     1` [TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) - Go wrapper for the TripAdvisor API.
* `     6` [tumblr](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API.
* `    63` [twitter-scraper](https://github.com/n0madic/twitter-scraper) - Scrape the Twitter Frontend API without authentication and limits.
* `    42` [uptimerobot](https://github.com/bitfield/uptimerobot) - Go wrapper and command-line client for the Uptime Robot v2 API.
* `     1` [vl-go](https://github.com/verifid/vl-go) - Go client library around the VerifID identity verification layer API.
* `   573` [webhooks](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket.
* `    96` [wit-go](https://github.com/wit-ai/wit-go) - Go client for wit.ai HTTP API.
* `    43` [ynab](https://github.com/brunomvsouza/ynab.go) - Go wrapper for the YNAB API.
* `     6` [zooz](https://github.com/gojuno/go-zooz) - Go client for the Zooz API.

## Utilities

*General utilities and tools to make your life easier.*

* `   148` [apm](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API.
* `    11` [backscanner](https://github.com/icza/backscanner) - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward.
* `    38` [beyond](https://github.com/wesovilabs/beyond) - The Go tool that will drive you to the AOP world!
* `     5` [blank](https://github.com/Henry-Sarabia/blank) - Verify or remove blanks and whitespace from strings.
* [bleep](https://github.com/sinhashubham95/bleep) - Perform any number of actions on any set of OS signals in Go.
* `  1230` [boilr](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates.
* `    18` [changie](https://github.com/miniscruff/changie) - Automated changelog tool for preparing releases with lots of customization options.
* `   135` [chyle](https://github.com/antham/chyle) - Changelog generator using a git repository with multiple configuration possibilities.
* `   527` [circuit](https://github.com/cep21/circuit) - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern.
* `   917` [circuitbreaker](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go.
* `   312` [clockwork](https://github.com/jonboulle/clockwork) - A simple fake clock for golang.
* `    44` [cmd](https://github.com/SimonBaeumer/cmd) - Library for executing shell commands on osx, windows and linux.
* `    13` [command](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher.
* `     1` [copy](https://github.com/gotidy/copy) - Package for fast copying structs of different types.
* `    47` [copy-pasta](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage.
* `    78` [countries](https://github.com/biter777/countries) - Full implementation of ISO-3166-1, ISO-4217, ITU-T E.164, Unicode CLDR and IANA ccTLD standarts.
* `   250` [create-go-app](https://github.com/create-go-app/cli) - A powerful CLI for create a new production-ready project with backend (Golang), frontend (JavaScript, TypeScript) & deploy automation (Ansible, Docker) by running one command.
* ` 10937` [ctop](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics.
* `    16` [ctxutil](https://github.com/posener/ctxutil) - A collection of utility functions for contexts.
* `    38` [dbt](https://github.com/nikogura/dbt) - A framework for running self-updating signed binaries from a central, trusted repository.
* `   163` [Death](https://github.com/vrecan/death) - Managing go application shutdown with signals.
* `   323` [Deepcopier](https://github.com/ulule/deepcopier) - Simple struct copying for Go.
* `   258` [delve](https://github.com/derekparker/delve) - Go debugger.
* `    16` [dlog](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls.
* `    17` [equalizer](https://github.com/reugn/equalizer) - Quota manager and rate limiter collection for Go.
* `   434` [ergo](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy.
* `    29` [evaluator](https://github.com/nullne/evaluator) - Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend.
* `  1224` [filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature.
* `    16` [filler](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag.
* `    37` [filter](https://github.com/gookit/filter) - provide filtering, sanitizing, and conversion of Go data.
* ` 33969` [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go.
* `    45` [gaper](https://github.com/maxcnunes/gaper) - Builds and restarts a Go project when it crashes or some watched file changes.
* `    24` [generate](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex.
* `    17` [ghokin](https://github.com/antham/ghokin) - Parallelized formatter with no external dependencies for gherkin (cucumber, behat...).
* `   850` [git-time-metric](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git.
* `    56` [go-astitodo](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code.
* `   167` [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only).
* `   108` [go-bsdiff](https://github.com/gabstv/go-bsdiff) - Pure Go bsdiff and bspatch libraries and CLI tools.
* `    10` [go-convert](https://github.com/Eun/go-convert) - Package go-convert enbles you to convert a value into another type.
* `     8` [go-countries](https://github.com/mikekonan/go-countries) - Lightweight lookup over ISO-3166 codes.
* `   459` [go-dry](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go.
* `  2283` [go-funk](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).
* `    76` [go-health](https://github.com/Talento90/go-health) - Health package simplifies the way you add health check to your services.
* `    20` [go-httpheader](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields.
* `    31` [go-lock](https://github.com/viney-shih/go-lock) - go-lock is a lock library implementing read-write mutex and read-write trylock without starvation.
* `     7` [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) - Go package for working with Problem Details.
* `   317` [go-rate](https://github.com/beefsack/go-rate) - Timed rate limiter for Go.
* `     2` [go-safe](https://github.com/kenkyu392/go-safe) - Panic-safe sandbox.
* `   149` [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go.
* `   210` [go-trigger](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.
* `    43` [goback](https://github.com/carlescere/goback) - Go simple exponential backoff package.
* [goctx](https://github.com/zerosnake0/goctx) - Get your context value with high performance.
* `   460` [godaemon](https://github.com/VividCortex/godaemon) - Utility to write daemons.
* `  3923` [godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox.
* `   252` [gohper](https://github.com/cosiner/gohper) - Various tools/modules help for development.
* `    43` [golarm](https://github.com/msempere/golarm) - Fire alarms with system events.
* `    50` [golog](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks.
* `   436` [gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.
* `    22` [goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images.
* `    53` [goreadability](https://github.com/philipjkim/goreadability) - Webpage summary extractor using Facebook Open Graph and arc90's readability.
* `  6751` [goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible.
* `  2787` [goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report.
* `    76` [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features.
* `    28` [gostrutils](https://github.com/ik5/gostrutils) - Collections of string manipulation and conversion functions.
* `   189` [gotenv](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go.
* `    39` [gpath](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection.
* `   306` [gubrak](https://github.com/novalagung/gubrak) - Golang utility library with syntactic sugar. It's like lodash, but for golang.
* `    61` [handy](https://github.com/miguelpragier/handy) - Many utilities and helpers like string handlers/formatters and validators.
* `   636` [hostctl](https://github.com/guumaster/hostctl) - A CLI tool to manage /etc/hosts with easy commands.
* `   528` [htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility.
* ` 20632` [hub](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal.
* `  2999` [hystrix-go](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker.
* `   692` [immortal](https://github.com/immortal/immortal) - \*nix cross-platform (OS agnostic) supervisor.
* `    42` [intrinsic](https://github.com/mengzhuo/intrinsic) - Use x86 SIMD without writing any assembly code.
* `    13` [jsend](https://github.com/clevergo/jsend) - JSend's implementation writen in Go.
* `   977` [jump](https://github.com/gsamokovarov/jump) - Jump helps you navigate faster by learning your habits.
* `   435` [koazee](https://github.com/wesovilabs/koazee) - Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays.
* `     2` [lets-go](https://github.com/aplescia-chwy/lets-go) - Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities.
* `    21` [limiters](https://github.com/mennanov/limiters) - Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks.
* `   112` [lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go.
* `  1700` [mc](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.
* `  1356` [mergo](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.
* `    58` [mimemagic](https://github.com/zRedShift/mimemagic) - Pure Go ultra performant MIME sniffing library/utility.
* `    14` [mimesniffer](https://github.com/aofei/mimesniffer) - A MIME type sniffer for Go.
* `   402` [mimetype](https://github.com/gabriel-vasile/mimetype) - Package for MIME type detection based on magic numbers.
* `  2495` [minify](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats.
* `    57` [minquery](https://github.com/icza/minquery) - MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off).
* `  1528` [mmake](https://github.com/tj/mmake) - Modern Make.
* `   159` [moldova](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template.
* `  1420` [mole](https://github.com/davrodpin/mole) - cli app to easily create ssh tunnels.
* `    47` [mongo-go-pagination](https://github.com/gobeam/mongo-go-pagination) - Mongodb Pagination for official mongodb/mongo-go-driver package which supports both normal queries and Aggregation pipelines.
* `    82` [mssqlx](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind.
* `    64` [multitick](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers.
* `    33` [myhttp](https://github.com/inancgumus/myhttp) - Simple API to make HTTP GET requests with timeout support.
* `    68` [netbug](https://github.com/e-dard/netbug) - Easy remote profiling of your services.
* `     4` [nfdump](https://github.com/chrispassas/nfdump) - Read nfdump netflow files.
* `    80` [nostromo](https://github.com/pokanop/nostromo) - CLI for building powerful aliases.
* `    15` [okrun](https://github.com/xta/okrun) - go run error steamroller.
* `     2` [olaf](https://github.com/btnguyen2k/olaf) - Twitter Snowflake implemented in Go.
* `   115` [onecache](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc).
* `  2490` [panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump.
* `    61` [pattern-match](https://github.com/alexpantyukhin/go-pattern-match) - Pattern matching libray.
* `  6147` [peco](https://github.com/peco/peco) - Simplistic interactive filtering tool.
* `    49` [pgo](https://github.com/arthurkushman/pgo) - Convenient functions for PHP community.
* `    79` [pm](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API.
* `     6` [ptr](https://github.com/gotidy/ptr) - Package that provide functions for simplified creation of pointers from constants of basic types.
* `    32` [rclient](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs.
* `  3882` [realize](https://github.com/tockins/realize) - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths.
* `    72` [repeat](https://github.com/ssgreg/repeat) - Go implementation of different backoff strategies useful for retrying operations and heartbeating.
* `   392` [request](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™.
* `    18` [rerate](https://github.com/abo/rerate) - Redis-based rate counter and rate limiter for Go.
* `   161` [rerun](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes.
* `    14` [rest-go](https://github.com/edermanoel94/rest-go) - A package that provide many helpful methods for working with rest api.
* `   264` [retry](https://github.com/kamilsk/retry) - The most advanced functional mechanism to perform actions repetitively until successful.
* `     7` [retry](https://github.com/percolate/retry) - A simple but highly configurable retry package for Go.
* `    47` [retry](https://github.com/thedevsaddam/retry) - Simple and easy retry mechanism package for Go.
* `    11` [retry](https://github.com/shafreeck/retry) - A pretty simple library to ensure your work to be done.
* `    39` [retry-go](https://github.com/rafaeljesus/retry-go) - Retrying made simple and easy for golang.
* `   148` [robustly](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics.
* `    67` [scan](https://github.com/blockloop/scan) - Scan golang `sql.Rows` directly to structs, slices, or primitive types.
* `   189` [scany](https://github.com/georgysavva/scany) - Library for scanning data from a database into Go structs and more.
* `   230` [serve](https://github.com/syntaqx/serve) - A static http server anywhere you need.
* `    13` [shutdown](https://github.com/ztrue/shutdown) - App shutdown hooks for `os.Signal` handling.
* `     4` [silk](https://github.com/chrispassas/silk) - Read silk netflow files.
* `    37` [slice](https://github.com/psampaz/slice) - Type-safe functions for common Go slice operations.
* `     6` [sliceconv](https://github.com/Henry-Sarabia/sliceconv) - Slice conversion between primitive types.
* `    24` [slicer](https://github.com/leaanthony/slicer) - Makes working with slices easier.
* `    67` [sorty](https://github.com/jfcg/sorty) - Fast Concurrent / Parallel Sorting.
* `  1322` [spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options.
* `  9505` [sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package.
* `     7` [statiks](https://github.com/janiltonmaciel/statiks) - Fast, zero-configuration, static HTTP filer server.
* `  1665` [Storm](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB.
* `    16` [structs](https://github.com/PumpkinSeed/structs) - Implement simple functions to manipulate structs.
* `  3021` [Task](https://github.com/go-task/task) - simple "Make" alternative.
* `    70` [taskctl](https://github.com/taskctl/taskctl) - Concurrent task runner.
* `     1` [tik](https://github.com/andy2046/tik) - Simple and easy timing wheel package for Go.
* `    17` [tome](https://github.com/cyruzin/tome) - Tome was designed to paginate simple RESTful APIs.
* `   155` [toolbox](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer.
* `    24` [ugo](https://github.com/alxrm/ugo) - ugo is slice toolbox with concise syntax for Go.
* `    68` [UNIS](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go.
* `  6069` [usql](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases.
* `   191` [util](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...).
* `  9264` [wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection.
* `    84` [xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang.

## UUID

*Libraries for working with UUIDs.*

* `    29` [goid](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs.
* `     5` [gouid](https://github.com/twharmon/gouid) - Generate cryptographically secure random string IDs with just one allocation.
* `    28` [nanoid](https://github.com/aidarkhanov/nanoid) - A tiny and efficient Go unique string ID generator.
* `    42` [sno](https://github.com/muyo/sno) - Compact, sortable and fast unique IDs with embedded metadata.
* `  2107` [ulid](https://github.com/oklog/ulid) - Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier).
* [uniq](https://gitlab.com/skilstak/code/go/uniq) - No hassle safe, fast unique identifiers with commands.
* `    12` [uuid](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier.
* `   865` [uuid](https://github.com/gofrs/uuid) - Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid.
* `  2341` [uuid](https://github.com/google/uuid) - Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services.
* `   382` [wuid](https://github.com/edwingeng/wuid) - An extremely fast unique number generator, 10-135 times faster than UUID.

## Validation

*Libraries for validation.*

* `    72` [checkdigit](https://github.com/osamingo/checkdigit) - Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.).
* `    45` [gody](https://github.com/guiferpa/gody) - :balloon: A lightweight struct validator for Go.
* `    23` [govalid](https://github.com/twharmon/govalid) - Fast, tag-based validation for structs.
* `  4559` [govalidator](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs.
* `   949` [govalidator](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation.
* `    53` [jio](https://github.com/faceair/jio) - jio is a json schema validator similar to ` 16366` [joi](https://github.com/hapijs/joi).
* `  1824` [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags.
* `    40` [terraform-validator](https://github.com/thazelart/terraform-validator) - A norms and conventions validator for Terraform.
* `   347` [validate](https://github.com/gookit/validate) - Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features.
* `    54` [validate](https://github.com/gobuffalo/validate) - This package provides a framework for writing validations for Go applications.
* `  6794` [validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.

## Version Control

*Libraries for version control.*

* `    75` [gh](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks.
* `  1577` [git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2.
* `  1875` [go-git](https://github.com/go-git/go-git) - highly extensible Git implementation in pure Go.
* `    75` [go-vcs](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go.
* `  1194` [hercules](https://github.com/src-d/hercules) - gaining advanced insights from Git repository history.
* `    13` [hgo](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories.

## Video

*Libraries for manipulating video.*

* `   646` [gmf](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries.
* `   295` [go-astisub](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).
* `   336` [go-astits](https://github.com/asticode/go-astits) - Parse and demux MPEG Transport Streams (.ts) natively in GO.
* `    68` [go-m3u8](https://github.com/quangngotan95/go-m3u8) - Parser and generator library for Apple m3u8 playlists.
* `     5` [go-mpd](https://github.com/unki2aut/go-mpd) - Parser and generator library for MPEG-DASH manifest files.
* `  1466` [goav](https://github.com/giorgisio/goav) - Comphrensive Go bindings for FFmpeg.
* `   159` [gst](https://github.com/ziutek/gst) - Go bindings for GStreamer.
* `    13` [libgosubs](https://github.com/wargarblgarbl/libgosubs) - Subtitle format support for go. Supports .srt, .ttml, and .ass.
* `   174` [libvlc-go](https://github.com/adrg/libvlc-go) - Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player).
* `   767` [m3u8](https://github.com/grafov/m3u8) - Parser and generator library of M3U8 playlists for Apple HLS.
* `    49` [v4l](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go.

## Web Frameworks

*Full stack web frameworks.*

* [aah](https://aahframework.org) - Scalable, performant, rapid development Web framework for Go.
* `   340` [Aero](https://github.com/aerogo/aero) - High-performance web framework for Go, reaches top scores in Lighthouse.
* `   395` [Air](https://github.com/aofei/air) - An ideally refined web framework for Go.
* `    71` [appy](https://github.com/appist/appy) - An opinionated productive web framework that helps scaling business easier.
* `    17` [Banjo](https://github.com/nsheremet/banjo) - Very simple and fast web framework for Go.
* `    31` [Beego](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language.
* [Buffalo](http://gobuffalo.io) - Bringing the productivity of Rails to Go!
* ` 18858` [Echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework.
* ` 10960` [Fiber](https://github.com/gofiber/fiber) - An Express.js inspired web framework build on Fasthttp.
* `    56` [Fireball](https://github.com/zpatrick/fireball) - More "natural" feeling web framework.
* `   184` [Flamingo](https://github.com/i-love-flamingo/flamingo) - Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc.
* `   136` [Flamingo Commerce](https://github.com/i-love-flamingo/flamingo-commerce) - Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications.
* `   405` [Gearbox](https://github.com/abahmed/gearbox) - A web framework written in Go with a focus on high performance and memory optimization.
* ` 44570` [Gin](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.
* `   145` [Ginrpc](https://github.com/xxjwxc/ginrpc) - Gin parameter automatic binding tool,gin rpc tools.
* `  3325` [Gizmo](https://github.com/NYTimes/gizmo) - Microservice toolkit used by the New York Times.
* `  3450` [go-json-rest](https://github.com/ant0ine/go-json-rest) - Quick and easy way to setup a RESTful JSON API.
* `   126` [go-rest](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go.
* `  4089` [Goa](https://github.com/goadesign/goa) - Goa provides a holistic approach for developing remote APIs and microservices in Go.
* `    44` [goa](https://github.com/goa-go/goa) - goa is just like koajs for golang, it is a flexible, light, high-performance and extensible web framework based on middleware.
* `    73` [Golax](https://github.com/fulldump/golax) - A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more.
* `   246` [Golf](https://github.com/dinever/golf) - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library.
* `   311` [Gondola](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster.
* `   438` [gongular](https://github.com/mustafaakin/gongular) - Fast Go web framework with input mapping/validation and (DI) Dependency Injection.
* `    19` [goweb](https://github.com/twharmon/goweb) - Web framework with routing, websockets, logging, middleware, static file server (optional gzip), and automatic TLS.
* `   767` [Goyave](https://github.com/System-Glitch/goyave) - Feature-complete web framework aimed at clean code and fast development, with powerful built-in functionalities.
* `   142` [hiboot](https://github.com/hidevopsio/hiboot) - hiboot is a high performance web application framework with auto configuration and dependency injection support.
* `  3113` [Macaron](https://github.com/go-macaron/macaron) - Macaron is a high productive and modular design web framework in Go.
* `   354` [mango](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333.
* `    73` [Microservice](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang.
* `   410` [neo](https://github.com/ivpusic/neo) - Neo is minimal and fast Go Web Framework with extremely simple API.
* `    69` [patron](https://github.com/beatlabs/patron) - Patron is a microservice framework following best cloud practices with a focus on productivity.
* `    31` [Resoursea](https://github.com/resoursea/api) - REST framework for quickly writing resource based services.
* [REST Layer](http://rest-layer.io) - Framework to build REST/GraphQL API on top of databases with mostly configuration over code.
* ` 12075` [Revel](https://github.com/revel/revel) - High-productivity web framework for the Go language.
* `    31` [rex](https://github.com/goanywhere/rex) - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`.
* `    53` [rux](https://github.com/gookit/rux) - Simple and fast web framework for build golang HTTP applications.
* `   838` [tango](https://github.com/lunny/tango) - Micro & pluggable web framework for Go.
* `  1000` [tigertonic](https://github.com/rcrowley/go-tigertonic) - Go framework for building JSON web services inspired by Dropwizard.
* `   120` [uAdmin](https://github.com/uadmin/uadmin) - Fully featured web framework for Golang, inspired by Django.
* `  2178` [utron](https://github.com/gernest/utron) - Lightweight MVC framework for Go(Golang).
* `    74` [vox](https://github.com/aisk/vox) - A golang web framework for humans, inspired by Koa heavily.
* `   147` [WebGo](https://github.com/bnkamalesh/webgo) - A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc).
* `    61` [YARF](https://github.com/yarf-framework/yarf) - Fast micro-framework designed to build REST APIs and web services in a fast and simple way.

### Middlewares

#### Actual middlewares

* `    18` [client-timing](https://github.com/posener/client-timing) - An HTTP client for Server-Timing header.
* `  1683` [CORS](https://github.com/rs/cors) - Easily add CORS capabilities to your API.
* `    36` [formjson](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST.
* `   377` [go-fault](https://github.com/github/go-fault) - Fault injection middleware for Go.
* `   786` [go-server-timing](https://github.com/mitchellh/go-server-timing) - Add/parse Server-Timing header.
* `  1195` [Limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go.
* `   109` [ln-paywall](https://github.com/philippgille/ln-paywall) - Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin).
* `  1822` [Tollbooth](https://github.com/didip/tollbooth) - Rate limit HTTP request handler.
* `    76` [XFF](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends.

#### Libraries for creating HTTP middlewares

* `  2180` [alice](https://github.com/justinas/alice) - Painless middleware chaining for Go.
* `     7` [catena](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain").
* `    64` [chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware").
* `    59` [go-wrap](https://github.com/go-on/wrap) - Small middlewares package for net/http.
* `    94` [gores](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs.
* `   291` [interpose](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang.
* `    69` [mediary](https://github.com/HereMobilityDevelopers/mediary) - add interceptors to `http.Client` to allow dumping/shaping/tracing/... of requests/responses.
* `   209` [muxchain](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http.
* `  6871` [negroni](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang.
* `  1401` [render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses.
* [renderer](https://github.com/thedevsaddam/renderer) - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go.
* `    95` [rye](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context.
* `   575` [stats](https://github.com/thoas/stats) - Go middleware that stores various information about your web application.

### Routers

* `   115` [alien](https://github.com/gernest/alien) - Lightweight and fast http router from outer space.
* `    48` [bellt](https://github.com/GuilhermeCaruso/bellt) - A simple Go HTTP router.
* `  1263` [Bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer.
* `    97` [Bxog](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters.
* `  8664` [chi](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context.
* `   864` [fasthttprouter](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`.
* `    19` [FastRouter](https://github.com/razonyang/fastrouter) - a fast, flexible HTTP router written in Go.
* `  1435` [gocraft/web](https://github.com/gocraft/web) - Mux and middleware package in Go.
* `   841` [Goji](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`.
* `     7` [goroute](https://github.com/goroute/route) - Simple yet powerful HTTP request multiplexer.
* `    87` [GoRouter](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`.
* `   157` [gowww/router](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface.
* ` 12207` [httprouter](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework.
* `   468` [httptreemux](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter.
* `   382` [lars](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks.
* ` 13414` [mux](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang.
* `   390` [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs.
* `   111` [pure](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation.
* `   351` [Siesta](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers.
* `   265` [vestigo](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications.
* `   100` [violetear](https://github.com/nbari/violetear) - Go HTTP router.
* `    88` [xmux](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support.
* `   489` [xujiajun/gorouter](https://github.com/xujiajun/gorouter) - A simple and fast HTTP router for Go.

## WebAssembly

* `   422` [dom](https://github.com/dennwc/dom) - DOM library.
* `   105` [go-canvas](https://github.com/markfarnan/go-canvas) - Library to use HTML5 Canvas, with all drawing within go code.
* `  7291` [tinygo](https://github.com/tinygo-org/tinygo) - Go compiler for small places. Microcontrollers, WebAssembly, and command-line tools. Based on LLVM.
* `    44` [vert](https://github.com/norunners/vert) - Interop between Go and JS values.
* `    70` [wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) - Run Go WASM tests in your browser.
* `    68` [webapi](https://github.com/gowebapi/webapi) - Bindings for DOM and HTML generated from WebIDL.

## Windows

* `   112` [d3d9](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9.
* `   699` [go-ole](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang.
* `     4` [gosddl](https://github.com/MonaxGT/gosddl) - Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL.

## XML

*Libraries and tools for manipulating XML.*

* `    16` [XML-Comp](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags.
* `    27` [xml2map](https://github.com/sbabiv/xml2map) - XML to MAP converter written Golang.
* `    16` [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module.
* `   361` [xpath](https://github.com/antchfx/xpath) - XPath package for Go.
* `   154` [xquery](https://github.com/antchfx/xquery) - XQuery lets you extract data from HTML/XML documents using XPath expression.
* `   437` [zek](https://github.com/miku/zek) - Generate a Go struct from XML.

# Tools

*Go software and plugins.*

## Code Analysis

* `   170` [apicompat](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes.
* `   221` [dupl](https://github.com/mibk/dupl) - Tool for code clone detection.
* `  1622` [errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs.
* `  1004` [gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time.
* `   109` [go-checkstyle](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments.
* `   403` [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects.
* `   838` [go-critic](https://github.com/go-critic/go-critic) - source code linter that brings checks that are currently not implemented in other linters.
* `   451` [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) - An easy way to find outdated dependencies of your Go projects.
* `    44` [go-outdated](https://github.com/firstrow/go-outdated) - Console application that displays outdated packages.
* `   485` [goast-viewer](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer.
* [GoCover.io](http://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* `    84` [golines](https://github.com/segmentio/golines) - Formatter that automatically shortens long lines in Go code.
* `  3775` [GoLint](https://github.com/golang/lint) - Golint is a linter for Go source code.
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* `   297` [GoPlantUML](https://github.com/jfeliu007/goplantuml) - Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them.
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
* `  3601` [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - gosimple is a linter for Go source code that specialises on simplifying code.
* `   243` [gostatus](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages.
* `    66` [lint](https://github.com/surullabs/lint) - Run linters as part of go test.
* `   779` [php-parser](https://github.com/z7zmey/php-parser) - A Parser for PHP written in Go.
* `  3601` [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
* `    14` [tarp](https://github.com/verygoodsoftwarenotvirus/tarp) - tarp finds functions and methods without direct unit tests in Go source code.
* `   238` [tickgit](https://github.com/augmentable-dev/tickgit) - CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author.
* `   306` [unconvert](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source.
* `  3601` [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - unused checks Go code for unused constants, variables, functions and types.
* [validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags.

## Editor Plugins

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
* `    33` [go-language-server](https://github.com/theia-ide/go-language-server) - A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol.
* `  1129` [go-mode](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs.
* `  1514` [go-plus](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting.
* `  4903` [gocode](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language.
* `    22` [goimports-reviser](https://github.com/incu6us/goimports-reviser) - Formatting tool for imports.
* [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) - This extension adds benchmark profiling support for the Go language to VS Code.
* `  3391` [GoSublime](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features.
* `    19` [gounit-vim](https://github.com/hexdigest/gounit-vim) - Vim plugin for generating Go tests based on the function's or method's signature.
* `    16` [theia-go-extension](https://github.com/theia-ide/theia-go-extension) - Go language support for the Theia IDE.
* `    87` [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save.
* ` 12985` [vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim.
* `  1292` [vscode-go](https://github.com/golang/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language.
* `   178` [Watch](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes.

## Go Generate Tools

* `    36` [generic](https://github.com/usk81/generic) - flexible data type for Go.
* `  1349` [genny](https://github.com/cheekybits/genny) - Elegant generics for Go.
* `    65` [gocontracts](https://github.com/Parquery/gocontracts) - brings design-by-contract to Go by synchronizing the code with the documentation.
* `   111` [gonerics](http://github.com/bouk/gonerics) - Idiomatic Generics in Go.
* `  2965` [gotests](https://github.com/cweill/gotests) - Generate Go tests from your source code.
* `    44` [gounit](https://github.com/hexdigest/gounit) - Generate Go tests using your own templates.
* `    77` [hasgo](https://github.com/DylanMeeus/hasgo) - Generate Haskell inspired functions for your slices.
* `   182` [re2dfa](https://github.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code.
* [TOML-to-Go](https://xuri.me/toml-to-go) - Translates TOML into a Go type in the browser instantly.
* `    62` [xgen](https://github.com/xuri/xgen) - XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator.

## Go Tools

* `   107` [colorgo](https://github.com/songgao/colorgo) - Wrapper around `go` command for colorized `go build` output.
* `   573` [depth](https://github.com/KyleBanks/depth) - Visualize dependency trees of any package by analyzing imports.
* [gb](https://getgb.io/) - An easy to use project based build tool for the Go programming language.
* `    22` [generator-go-lang](https://github.com/axelspringer/generator-go-lang) - A [Yeoman](http://yeoman.io) generator to get new Go projects started.
* [gilbert](https://go-gilbert.github.io) - Build system and task runner for Go projects.
* `  2984` [go-callvis](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format.
* `    37` [go-james](https://github.com/pieterclaerhout/go-james) - Go project skeleton creator, builds and tests your projects without the manual setup.
* `    37` [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - Bash completion for go and wgo.
* `  5968` [go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API.
* `   171` [godbg](https://github.com/tylerwince/godbg) - Implementation of Rusts `dbg!` macro for quick and easy debugging during development.
* `    15` [gomodrun](https://github.com/dustinblackman/gomodrun/) - Go tool that executes and caches binaries included in go.mod files.
* `    95` [gothanks](https://github.com/psampaz/gothanks) - GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers.
* `    39` [igo](https://github.com/rocketlaunchr/igo) - An igo to go transpiler (new language features for Go language!)
* `  4596` [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.
* `   516` [richgo](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations.
* `   207` [rts](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses.
* `   127` [typex](https://github.com/dtgorski/typex) - Examine Go types and their transitive dependencies, alternatively export results as TypeScript value objects (or types) declaration.

## Software Packages

*Software written in Go.*

### DevOps Tools

* `   160` [abbreviate](https://github.com/dnnrly/abbreviate) - abbreviate is a tool turning long strings in to shorter ones with configurable seperaters, for example to embed branch names in to deployment stack IDs.
* `     3` [aptly](https://github.com/smira/aptly) - aptly is a Debian repository management tool.
* `   491` [aurora](https://github.com/xuri/aurora) - Cross-platform web-based Beanstalkd queue server console.
* `    26` [awsenv](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile.
* `   190` [Blast](https://github.com/dave/blast) - A simple tool for API load testing and batch jobs.
* `  2444` [bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool.
* `  3090` [bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework.
* `   467` [cassowary](https://github.com/rogerwelin/cassowary) - Modern cross-platform HTTP load-testing tool written in Go.
* `    14` [DepCharge](https://github.com/centerorbit/depcharge) - Helps orchestrating the execution of commands across the many dependencies in larger projects.
* `    92` [Dockerfile-Generator](https://github.com/ozankasikci/dockerfile-generator) - A go library and an executable that produces valid Dockerfiles using various input channels.
* `   232` [dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart).
* `    30` [drone-jenkins](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI.
* `    77` [drone-scp](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI.
* `    54` [Dropship](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn.
* `   167` [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`.
* `  1689` [fac](https://github.com/mkchoi212/fac) - Command-line user interface to fix git merge conflicts.
* `  4286` [gaia](https://github.com/gaia-pipeline/gaia) - Build powerful pipelines in any programming language.
* ` 22968` [Gitea](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven.
* [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) - Migrate all your GitHub repositories, issues, milestones and labels to your Gitea instance.
* `    79` [go-furnace](https://github.com/go-furnace/go-furnace) - Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean.
* `   781` [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update.
* `   177` [gobrew](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go.
* `   224` [godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application.
* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* `   324` [gonative](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.
* `   467` [govvv](https://github.com/ahmetalpbalkan/govvv) - “go build” wrapper to easily add version information into Go binaries.
* `  3940` [gox](https://github.com/mitchellh/gox) - Dead simple, no frills Go cross compile tool.
* `  1659` [goxc](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging.
* `   151` [grapes](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease.
* `  5876` [GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions.
* `  9975` [Hey](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application.
* `   228` [jcli](https://github.com/jenkins-zh/jenkins-cli) - Jenkins CLI allows you manage your Jenkins as an easy way.
* `  1593` [kala](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler.
* `   142` [kcli](https://github.com/cswank/kcli) - Command line tool for inspecting kafka topics/partitions/messages.
* ` 73234` [kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google.
* `   272` [lstags](https://github.com/ivanilves/lstags) - Tool and API to sync Docker images across different registries.
* `    24` [lwc](https://github.com/timdp/lwc) - A live-updating version of the UNIX wc command.
* `   222` [manssh](https://github.com/xwjdsh/manssh) - manssh is a command line tool for managing your ssh alias config easily.
* ` 59301` [Moby](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems.
* `   281` [Mora](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data.
* `   169` [ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB.
* ` 12428` [Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
* `   258` [Pewpew](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester.
* `  2176` [Pomerium](https://github.com/pomerium/pomerium) - Pomerium is an identity-aware access proxy.
* `    31` [Rodent](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies.
* `    28` [s3-proxy](https://github.com/oxyno-zeta/s3-proxy) - S3 Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth).
* `  1079` [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.
* `   510` [s5cmd](https://github.com/peak/s5cmd) - Blazing fast S3 and local filesystem execution tool.
* `   640` [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker).
* `  1670` [script](https://github.com/bitfield/script) - Making it easy to write shell-like scripts in Go for DevOps and system administration tasks.
* `     6` [sg](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response.
* `   663` [skm](https://github.com/TimothyYe/skm) - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily!
* `  1432` [StatusOK](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected.
* `   130` [terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) - Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed.
* ` 32096` [traefik](https://github.com/containous/traefik) - Reverse proxy and load balancer with support for multiple backends.
* `   293` [trubka](https://github.com/xitonix/trubka) - A CLI tool to manage and troubleshoot Apache Kafka clusters with the ability of generically publishing/consuming protocol buffer and plain text events to/from Kafka.
* `   332` [uTask](https://github.com/ovh/utask) - Automation engine that models and executes business processes declared in yaml.
* ` 16097` [Vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000!
* `  6069` [webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.
* [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
* `   108` [winrm-cli](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines.

### Other Software

* [Better Go Playground](https://goplay.tools) - Go playground with syntax highlight, code completion and other features.
* `  1487` [borg](https://github.com/crufter/borg) - Terminal based search engine for bash snippets.
* `    72` [boxed](https://github.com/tejo/boxed) - Dropbox based blog engine.
* `   234` [Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go.
* `  1871` [Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
* `  6813` [Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections.
* `  7285` [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul.
* ` 11155` [croc](https://github.com/schollz/croc) - Easily and securely send files or folders from one computer to another.
* [Docker](http://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
* `  1239` [Documize](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools.
* `    61` [dp](https://github.com/scryinfo/dp) - Through SDK for data exchange with blockchain, developers can get easy access to DAPP development.
* `  5778` [drive](https://github.com/odeke-em/drive) - Google Drive client for the commandline.
* `  3531` [Duplicacy](https://github.com/gilbertchen/duplicacy) - A cross-platform network and cloud backup tool based on the idea of lock-free deduplication.
* `   471` [Gebug](https://github.com/moshebe/gebug) - A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly.
* `   588` [gfile](https://github.com/Antonito/gfile) - Securely transfer files between two computers, without any third party, over WebRTC.
* `   889` [Go Package Store](https://github.com/shurcooL/Go-Package-Store) - App that displays updates for the Go packages in your GOPATH.
* `   418` [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client.
* `  2277` [GoBoy](https://github.com/Humpheh/goboy) - Nintendo Game Boy Color emulator written in Go.
* `   443` [gocc](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go.
* `    13` [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at function list.
* [GoLand](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
* ` 13719` [Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.
* `   505` [Guora](https://github.com/meloalright/guora) - A self-hosted Quora like web application written in Go.
* [hugo](http://gohugo.io/) - Fast and Modern Static Website Engine.
* `   300` [ide](https://github.com/thestrukture/ide) - Browser accessible IDE. Designed for Go with Go.
* `   312` [ipe](https://github.com/dimiro1/ipe) - Open source Pusher server implementation compatible with Pusher client libraries written in GO.
* `   153` [joincap](https://github.com/assafmo/joincap) - Command-line utility for merging multiple pcap files together.
* [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
* `   694` [Leaps](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms.
* `  2097` [lgo](https://github.com/yunabe/lgo) - Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility.
* [limetext](https://limetext.github.io) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* `  6278` [LiteIDE](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE.
* `   468` [mockingjay](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests.
* `  2399` [myLG](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go.
* `    21` [naclpipe](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go.
* `  4653` [nes](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go.
* `   143` [Orbit](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates.
* `   753` [peg](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator.
* ` 11582` [restic](https://github.com/restic/restic) - De-duplicating backup program.
* `  1953` [scc](https://github.com/boyter/scc) - Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates.
* ` 11232` [Seaweed File System](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek.
* `   683` [shell2http](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control).
* `  1795` [snap](https://github.com/intelsdi-x/snap) - Powerful telemetry framework.
* `    15` [Snitch](https://github.com/lucasgomide/snitch) - Simple way to notify your team and many tools when someone has deployed any application via Tsuru.
* `  2222` [Stack Up](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers.
* [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
* `   155` [tcpprobe](https://github.com/mehrdadrad/tcpprobe) - TCP tool for network performance and path monitoring, including socket statistics.
* `    17` [term-quiz](https://github.com/crazcalm/term-quiz) - Quizzes for your terminal.
* `  5049` [toxiproxy](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests.
* [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
* `   100` [vaku](https://github.com/lingrino/vaku) - CLI & API for folder-based functions in Vault like copy, move, and search.
* `   751` [vFlow](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector.
* `   296` [wellington](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass).
* `   174` [woke](https://github.com/get-woke/woke) - Detect non-inclusive language in your source code.

# Resources

*Where to discover new Go libraries.*

## Benchmarks

* `    90` [autobench](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions.
* `    21` [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results.
* `   135` [go-benchmarks](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches.
* `  1458` [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison.
* `     4` [go-json-benchmark](https://github.com/zerosnake0/go-json-benchmark) - Go JSON benchmark.
* `  1381` [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark.
* `  1071` [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods.
* `    55` [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language.
* `    54` [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities.
* `   105` [gospeed](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs.
* `    19` [kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark.
* `   975` [skynet](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark.
* `   207` [speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language.

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

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [For the Love of Go](https://bitfieldconsulting.com/books) - A series of introductory books for Go beginners.
* [Go 101](https://go101.org) - A book focusing on Go syntax/semantics and all kinds of details.
* [Go Bootcamp](http://golangbootcamp.com)
* `    18` [Go Succinctly](https://github.com/thedevsir/gosuccinctly) - in Persian.
* `  8709` [GoBooks](https://github.com/dariubs/GoBooks) - A curated list of Go books.
* [How To Code in Go eBook](https://www.digitalocean.com/community/books/how-to-code-in-go-ebook) - A 600 page introduction to Go aimed at first time developers.
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [Spaceship Go A Journey to the Standard Library](https://blasrodri.github.io/spaceship-go-gh-pages/)
* [The Go Programming Language](http://www.gopl.io/)
* `  7379` [The Golang Standard Library by Example (Chinese)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example)
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)
* [Writing A Compiler In Go](https://compilerbook.com)
* [Writing An Interpreter In Go](https://interpreterbook.com)

## Gophers

* `  2124` [Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack) - Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster.
* `    36` [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) - Go gopher Vector Data [.ai, .svg].
* `    82` [gopher-logos](https://github.com/GolangUA/gopher-logos) - adorable gopher logos.
* `   487` [gopher-stickers](https://github.com/tenntenn/gopher-stickers)
* `   371` [gopher-vector](https://github.com/golang-samples/gopher-vector)
* `   576` [gophericons](https://github.com/shalakhin/gophericons)
* `   470` [gopherize.me](https://github.com/matryer/gopherize.me) - Gopherize yourself.
* `  2337` [gophers](https://github.com/ashleymcnamara/gophers) - Gopher artworks by Ashley McNamara.
* `  2241` [gophers](https://github.com/egonelbre/gophers) - Free gophers.
* `    54` [gophers](https://github.com/rogeralsing/gophers) - random gopher graphics.
* `    77` [gophers](https://github.com/sillecelik/go-gopher) - Gopher amigurumi toy pattern.

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
* [Golang Korea](https://www.meetup.com/GDG-Golang-Korea/)
* [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
* [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
* [Golang Marseille](https://www.meetup.com/fr-FR/Golang-Marseille/)
* [Golang Melbourne](https://www.meetup.com/golang-mel/)
* [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
* [Golang New York](https://www.meetup.com/nycgolang/)
* [Golang North East](https://www.meetup.com/en-AU/Golang-North-East/)
* [Golang Paris](https://www.meetup.com/Golang-Paris/)
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

* `   987` [bahlo/go-styleguide](https://github.com/bahlo/go-styleguide)
* ` 19652` [CockroachDB](https://github.com/cockroachdb/cockroach/blob/master/docs/style.md)
* [GitLab](https://docs.gitlab.com/ee/development/go_guide/)
* ` 11379` [Hyperledger](https://github.com/hyperledger/fabric/blob/release-1.4/docs/source/style-guides/go-style.rst)
* `  2391` [Magnetico](https://github.com/boramalper/magnetico/wiki/magnetico-Design-Specification)
* [Sourcegraph](https://about.sourcegraph.com/handbook/engineering/go_style_guide)
* [Thanos](https://thanos.io/tip/contributing/coding-style-guide.md/)
* `  8135` [Uber](https://github.com/uber-go/guide/blob/master/style.md)

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

* [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
* ` 19724` [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them are looking for Go hackers.
* ` 27065` [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists.
* [CodinGame](https://www.codingame.com/) - Learn Go by solving interactive tasks using small games as practical examples.
* [Go Blog](http://blog.golang.org) - The official Go blog.
* [Go Challenge](http://golang-challenge.org/) - Learn Go by solving problems and getting feedback from Go experts.
* [Go Code Club](https://www.youtube.com/watch?v=nvoIPQYdx9g&list=PLEcwzBXTPUE_YQR7R0BRtHBYJ0LN3Y0i3) - A group of Gophers read and discuss a different Go project every week.
* [Go Community on Hashnode](https://hashnode.com/n/go) - Community of Gophers on Hashnode.
* [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
* [Go In 5 Minutes](https://www.goin5minutes.com/) - 5 minute screencasts focused on getting one thing done.
* ` 80491` [Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki.
* [Go Report Card](https://goreportcard.com) - A report card for your Go package.
* [go.dev](https://go.dev/) - A hub for Go developers.
* `    38` [gocryforhelp](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go.
* [godoc.org](https://godoc.org/) - Documentation for open source Go packages.
* [Golang Developer Jobs](https://golangjob.xyz) - Developer Jobs exclusivly for Golang related Roles.
* [Golang Flow](https://golangflow.io) - Post Updates, News, Packages and more.
* [Golang News](https://golangnews.com) - Links and news about Go programming.
* `   142` [golang-graphics](https://github.com/mholt/golang-graphics) - Collection of Go images, graphics, and art.
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
* [Gophercises](https://gophercises.com/) - Free coding exercises for budding gophers.
* [gowalker.org](https://gowalker.org) - Go Project API documentation.
* [json2go](https://m-zajac.github.io/json2go) - Advanced JSON to Go struct conversion - online tool.
* [justforfunc](https://www.youtube.com/c/justforfunc) - Youtube channel dedicated to Go programming language tips and tricks, hosted by Francesc Campoy [@francesc](https://twitter.com/francesc).
* [Lille Gophers](https://lille-gophers.loscrackitos.codes/) - Golang talks community in Lille, France ([@LilleGophers](https://twitter.com/LilleGophers)).
* [Made with Golang](https://madewithgolang.com/?ref=awesome-go)
* [r/Golang](https://www.reddit.com/r/golang) - News about Go.
* [studygolang](https://studygolang.com) - The community of studygolang in China.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.
* [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

### Tutorials

* [50 Shades of Go](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - Traps, Gotchas, and Common Mistakes for New Golang Devs.
* [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) - Building a Golang site for e-commerce (demo included).
* [A Tour of Go](http://tour.golang.org/) - Interactive tour of Go.
* ` 36567` [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang.
* [Building and Testing a REST API in Go with Gorilla Mux and PostgreSQL](https://semaphoreci.com/community/tutorials/building-and-testing-a-rest-api-in-go-with-gorilla-mux-and-postgresql) - We’ll write an API with the help of the powerful Gorilla Mux.
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) - How to cache slow database queries.
* [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - How to cancel MySQL queries.
* `    41` [Design Patterns in Go](https://github.com/shubhamzanwar/design-patterns) - Collection of programming design patterns implemented in Go.
* `   707` [Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) - A little e-book on Ethereum Development with Go.
* [Games With Go](http://gameswithgo.org/) - A video series teaching programming and game development.
* [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
* `  5026` [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card.
* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
* [Go Playground for iOS](https://codeplayground.app) - Interactively edit & play Go snippets on your mobile device.
* [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
* ` 14319` [go-patterns](https://github.com/tmrts/go-patterns) - Curated list of Go design patterns, recipes and idioms.
* `   211` [goapp](https://github.com/bnkamalesh/goapp) - An opinionated guideline to structure & develop a Go web application/service.
* `  1493` [Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) - Examples of Golang compared to Node.js for learning.
* [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
* [GolangCode](https://golangcode.com/) - Collection of code snippets and tutorials to help tackle every day issues.
* [GopherSnippets](https://gophersnippets.com/) - Code snippets with tests and testable examples for the Go programming language.
* [Hackr.io](https://hackr.io/tutorials/learn-golang) - Learn Go from the best online golang tutorials submitted & voted by the golang programming community.
* [How to Benchmark: dbq vs sqlx vs GORM](https://medium.com/@rocketlaunchr.cloud/how-to-benchmark-dbq-vs-sqlx-vs-gorm-e814caacecb5) - Learn how to benchmark in Go. As a case-study, we will benchmark dbq, sqlx and GORM.
* [How To Deploy a Go Web Application with Docker](https://semaphoreci.com/community/tutorials/how-to-deploy-a-go-web-application-with-docker) - Learn how to use Docker for Go development and how to build production Docker images.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
* ` 12547` [Learn Go with TDD](https://github.com/quii/learn-go-with-tests) - Learn Go with test-driven development.
* [Learning Golang - From zero to hero](https://milapneupane.com.np/2019/07/06/learning-golang-from-zero-to-hero/) - Getting started with golang for beginner.
* [package main](https://www.youtube.com/packagemain) - YouTube channel about Programming in Go.
* [Programming with Google Go](https://www.coursera.org/specializations/google-golang) - Coursera Specialization to learn about Go from scratch.
* [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
* `  1163` [Working with Go](https://github.com/mkaz/working-with-go) - Intro to go for experienced programmers.
* [Your basic Go](http://yourbasic.org/golang) - Huge collection of tutorials and how to's.
