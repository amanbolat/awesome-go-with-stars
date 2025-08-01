
# About
This repository is a clone of [Awesome Go](https://github.com/avelino/awesome-go) but with stars.
All repositories are sorted by star count. Stars are updated every day automatically.
## Contents

- [Awesome Go](#awesome-go)
  - [Contents](#contents)
  - [Actor Model](#actor-model)
  - [Artificial Intelligence](#artificial-intelligence)
  - [Audio and Music](#audio-and-music)
  - [Authentication and Authorization](#authentication-and-authorization)
  - [Blockchain](#blockchain)
  - [Bot Building](#bot-building)
  - [Build Automation](#build-automation)
  - [Command Line](#command-line)
    - [Advanced Console UIs](#advanced-console-uis)
    - [Standard CLI](#standard-cli)
  - [Configuration](#configuration)
  - [Continuous Integration](#continuous-integration)
  - [CSS Preprocessors](#css-preprocessors)
  - [Data Integration Frameworks](#data-integration-frameworks)
  - [Data Structures and Algorithms](#data-structures-and-algorithms)
    - [Bit-packing and Compression](#bit-packing-and-compression)
    - [Bit Sets](#bit-sets)
    - [Bloom and Cuckoo Filters](#bloom-and-cuckoo-filters)
    - [Data Structure and Algorithm Collections](#data-structure-and-algorithm-collections)
    - [Iterators](#iterators)
    - [Maps](#maps)
    - [Miscellaneous Data Structures and Algorithms](#miscellaneous-data-structures-and-algorithms)
    - [Nullable Types](#nullable-types)
    - [Queues](#queues)
    - [Sets](#sets)
    - [Text Analysis](#text-analysis)
    - [Trees](#trees)
    - [Pipes](#pipes)
  - [Database](#database)
    - [Caches](#caches)
    - [Databases Implemented in Go](#databases-implemented-in-go)
    - [Database Schema Migration](#database-schema-migration)
    - [Database Tools](#database-tools)
    - [SQL Query Builders](#sql-query-builders)
  - [Database Drivers](#database-drivers)
    - [Interfaces to Multiple Backends](#interfaces-to-multiple-backends)
    - [Relational Database Drivers](#relational-database-drivers)
    - [NoSQL Database Drivers](#nosql-database-drivers)
    - [Search and Analytic Databases](#search-and-analytic-databases)
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
    - [Microsoft Excel](#microsoft-excel)
    - [Microsoft Word](#microsoft-word)
  - [Miscellaneous](#miscellaneous)
    - [Dependency Injection](#dependency-injection)
    - [Project Layout](#project-layout)
    - [Strings](#strings)
    - [Uncategorized](#uncategorized)
  - [Natural Language Processing](#natural-language-processing)
    - [Language Detection](#language-detection)
    - [Morphological Analyzers](#morphological-analyzers)
    - [Slugifiers](#slugifiers)
    - [Tokenizers](#tokenizers)
    - [Translation](#translation)
    - [Transliteration](#transliteration)
  - [Networking](#networking)
    - [HTTP Clients](#http-clients)
  - [OpenGL](#opengl)
  - [ORM](#orm)
  - [Package Management](#package-management)
  - [Performance](#performance)
  - [Query Language](#query-language)
  - [Reflection](#reflection)
  - [Resource Embedding](#resource-embedding)
  - [Science and Data Analysis](#science-and-data-analysis)
  - [Security](#security)
  - [Serialization](#serialization)
  - [Server Applications](#server-applications)
  - [Stream Processing](#stream-processing)
  - [Template Engines](#template-engines)
  - [Testing](#testing)
    - [Testing Frameworks](#testing-frameworks)
    - [Mock](#mock)
    - [Fuzzing and delta-debugging/reducing/shrinking](#fuzzing-and-delta-debuggingreducingshrinking)
    - [Selenium and browser control tools](#selenium-and-browser-control-tools)
    - [Fail injection](#fail-injection)
  - [Text Processing](#text-processing)
    - [Formatters](#formatters)
    - [Markup Languages](#markup-languages)
    - [Parsers/Encoders/Decoders](#parsersencodersdecoders)
    - [Regular Expressions](#regular-expressions)
    - [Sanitation](#sanitation)
    - [Scrapers](#scrapers)
    - [RSS](#rss)
    - [Utility/Miscellaneous](#utilitymiscellaneous)
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
  - [Webhooks Server](#webhooks-server)
  - [Windows](#windows)
  - [Workflow Frameworks](#workflow-frameworks)
  - [XML](#xml)
  - [Zero Trust](#zero-trust)
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
    - [E-books for purchase](#e-books-for-purchase)
    - [Free e-books](#free-e-books)
  - [Gophers](#gophers)
  - [Meetups](#meetups)
  - [Style Guides](#style-guides)
  - [Social Media](#social-media)
    - [Twitter](#twitter)
    - [Reddit](#reddit)
  - [Websites](#websites)
    - [Tutorials](#tutorials)
    - [Guided Learning](#guided-learning)

**[⬆ back to top](#contents)**

## Actor Model

*Libraries for building actor-based programs.*

- <code>&nbsp;&nbsp;5274</code> [ProtoActor](https://github.com/asynkron/protoactor-go) - Proto Actor - Ultra fast distributed actors for Go, C# and Java/Kotlin.
- <code>&nbsp;&nbsp;4041</code> [Ergo](https://github.com/ergo-services/ergo) - An actor-based Framework with network transparency for creating event-driven architecture in Golang. Inspired by Erlang.
- <code>&nbsp;&nbsp;2003</code> [Hollywood](https://github.com/anthdm/hollywood) - Blazingly fast and light-weight Actor engine written in Golang.
- <code>&nbsp;&nbsp;&nbsp;272</code> [Goakt](https://github.com/Tochemey/goakt) - Fast and Distributed Actor framework using protocol buffers as message for Golang.

## Artificial Intelligence

*Libraries for building programs that leverage AI.*

- <code>148423</code> [Ollama](https://github.com/jmorganca/ollama) - Run large language models locally.
- <code>&nbsp;34292</code> [LocalAI](https://github.com/mudler/LocalAI) - Open Source OpenAI alternative, self-host AI models.
- <code>&nbsp;&nbsp;7274</code> [langchaingo](https://github.com/tmc/langchaingo) - LangChainGo is a framework for developing applications powered by language models.
- <code>&nbsp;&nbsp;&nbsp;650</code> [chromem-go](https://github.com/philippgille/chromem-go) - Embeddable vector database for Go with Chroma-like interface and zero third-party dependencies. In-memory with optional persistence.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;81</code> [OllamaFarm](https://github.com/presbrey/ollamafarm) - Manage, load-balance, and failover packs of Ollamas
- [fun](https://gitlab.com/tozd/go/fun) - The simplest but powerful way to use large language models (LLMs) in Go.

**[⬆ back to top](#contents)**

## Audio and Music

*Libraries for manipulating audio.*

- <code>&nbsp;&nbsp;1747</code> [Oto](https://github.com/hajimehoshi/oto) - A low-level library to play sound on multiple platforms.
- <code>&nbsp;&nbsp;&nbsp;782</code> [PortAudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library.
- <code>&nbsp;&nbsp;&nbsp;378</code> [GoAudio](https://github.com/DylanMeeus/GoAudio) - Native Go Audio Processing Library.
- <code>&nbsp;&nbsp;&nbsp;350</code> [id3v2](https://github.com/bogem/id3v2) - ID3 decoding and encoding library for Go.
- <code>&nbsp;&nbsp;&nbsp;343</code> [malgo](https://github.com/gen2brain/malgo) - Mini audio library.
- <code>&nbsp;&nbsp;&nbsp;337</code> [flac](https://github.com/mewkiz/flac) - Native Go FLAC encoder/decoder with support for FLAC streams.
- <code>&nbsp;&nbsp;&nbsp;131</code> [gaad](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser.
- <code>&nbsp;&nbsp;&nbsp;129</code> [minimp3](https://github.com/tosone/minimp3) - Lightweight MP3 decoder library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> [gosamplerate](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go.

**[⬆ back to top](#contents)**

## Authentication and Authorization

*Libraries for implementing authentication and authorization.*

- <code>&nbsp;18949</code> [casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, and ABAC.
- <code>&nbsp;&nbsp;8338</code> [jwt-go](https://github.com/golang-jwt/jwt) - A full featured implementation of JSON Web Tokens (JWT). This library supports the parsing and verification as well as the generation and signing of JWTs.
- <code>&nbsp;&nbsp;6146</code> [goth](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box.
- <code>&nbsp;&nbsp;5906</code> [spicedb](https://github.com/authzed/spicedb) - A Zanzibar-inspired database that enables fine-grained authorization.
- <code>&nbsp;&nbsp;5662</code> [oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine, and App Engine support.
- <code>&nbsp;&nbsp;5087</code> [keto](https://github.com/ory/keto) - Open Source (Go) implementation of "Zanzibar: Google's Consistent, Global Authorization System". Ships gRPC, REST APIs, newSQL, and an easy and granular permission language. Supports ACL, RBAC, and other access models.
- <code>&nbsp;&nbsp;4024</code> [authboss](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure it, and start building your app without having to build an authentication system each time.
- <code>&nbsp;&nbsp;3951</code> [openfga](https://github.com/openfga/openfga) - Implementation of fine-grained authorization based on the "Zanzibar: Google's Consistent, Global Authorization System" paper. Backed by [CNCF](https://www.cncf.io/).
- <code>&nbsp;&nbsp;2383</code> [scs](https://github.com/alexedwards/scs) - Session Manager for HTTP servers.
- <code>&nbsp;&nbsp;2162</code> [jwx](https://github.com/lestrrat-go/jwx) - Go module implementing various JWx (JWA/JWE/JWK/JWS/JWT, otherwise known as JOSE) technologies
- <code>&nbsp;&nbsp;1929</code> [osin](https://github.com/openshift/osin) - Golang OAuth2 server library.
- <code>&nbsp;&nbsp;1927</code> [loginsrv](https://github.com/tarent/loginsrv) - JWT login microservice with pluggable backends such as OAuth2 (Github), htpasswd, osiam.
- <code>&nbsp;&nbsp;1917</code> [gologin](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers.
- <code>&nbsp;&nbsp;1637</code> [gorbac](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang.
- <code>&nbsp;&nbsp;1622</code> [oidc](https://github.com/zitadel/oidc) - Easy to use OpenID Connect client and server library written for Go and certified by the OpenID Foundation
- <code>&nbsp;&nbsp;&nbsp;902</code> [paseto](https://github.com/o1egl/paseto) - Golang implementation of Platform-Agnostic Security Tokens (PASETO).
- <code>&nbsp;&nbsp;&nbsp;687</code> [jwt](https://github.com/cristalhq/jwt) - Safe, simple, and fast JSON Web Tokens for Go.
- <code>&nbsp;&nbsp;&nbsp;590</code> [go-guardian](https://github.com/shaj13/go-guardian) - Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token, and Certificate based authentication.
- <code>&nbsp;&nbsp;&nbsp;424</code> [go-jose](https://github.com/go-jose/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.
- <code>&nbsp;&nbsp;&nbsp;363</code> [jwt](https://github.com/pascaldekloe/jwt) - Lightweight JSON Web Token (JWT) library.
- <code>&nbsp;&nbsp;&nbsp;269</code> [jeff](https://github.com/abraithwaite/jeff) - Simple, flexible, secure, and idiomatic web session management with pluggable backends.
- <code>&nbsp;&nbsp;&nbsp;258</code> [gosession](https://github.com/Kwynto/gosession) - This is quick session for net/http in GoLang. This package is perhaps the best implementation of the session mechanism, or at least it tries to become one.
- <code>&nbsp;&nbsp;&nbsp;234</code> [jwt-auth](https://github.com/adam-hanna/jwt-auth) - JWT middleware for Golang http servers with many configuration options.
- <code>&nbsp;&nbsp;&nbsp;157</code> [goiabada](https://github.com/leodip/goiabada) - An open-source authentication and authorization server supporting OAuth2 and OpenID Connect.
- <code>&nbsp;&nbsp;&nbsp;140</code> [otpgen](https://github.com/grijul/otpgen) - Library to generate TOTP/HOTP codes.
- <code>&nbsp;&nbsp;&nbsp;128</code> [sessionup](https://github.com/swithek/sessionup) - Simple, yet effective HTTP session management and identification package.
- <code>&nbsp;&nbsp;&nbsp;123</code> [sjwt](https://github.com/brianvoe/sjwt) - Simple jwt generator and parser.
- <code>&nbsp;&nbsp;&nbsp;118</code> [session](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;91</code> [branca](https://github.com/essentialkaos/branca) - branca token <code>&nbsp;&nbsp;&nbsp;230</code> [specification implementation](https://github.com/tuupola/branca-spec) for Golang 1.15+.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;82</code> [securecookie](https://github.com/chmike/securecookie) - Efficient secure cookie encoding/decoding.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;78</code> [sessions](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;76</code> [otpgo](https://github.com/jltorresm/otpgo) - Time-Based One-Time Password (TOTP) and HMAC-Based One-Time Password (HOTP) library for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> [scope](https://github.com/SonicRoshan/scope) - Easily Manage OAuth2 Scopes In Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [cookiestxt](https://github.com/mengzhuo/cookiestxt) - provides a parser of cookies.txt file format.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [permissions](https://github.com/xyproto/permissions) - Library for keeping track of users, login states, and permissions. Uses secure cookies and bcrypt.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [x509proxy](https://github.com/vkuznet/x509proxy) - Library to handle X509 proxy certificates.

**[⬆ back to top](#contents)**

## Blockchain

*Tools for building blockchains.*

- <code>&nbsp;49419</code> [go-ethereum](https://github.com/ethereum/go-ethereum) - Official Go implementation of the Ethereum protocol.
- <code>&nbsp;16612</code> [kubo](https://github.com/ipfs/kubo) - A blockchain framework implemented in Go. It provides content-addressable storage which can be used for decentralized storage in DApps. It is based on the IPFS protocol.
- <code>&nbsp;&nbsp;7983</code> [lnd](https://github.com/lightningnetwork/lnd) - A complete implementation of a Lightning Network node.
- <code>&nbsp;&nbsp;6677</code> [cosmos-sdk](https://github.com/cosmos/cosmos-sdk) - A Framework for Building Public Blockchains in the Cosmos Ecosystem.
- <code>&nbsp;&nbsp;5816</code> [tendermint](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.
- <code>&nbsp;&nbsp;1369</code> [solana-go](https://github.com/gagliardetto/solana-go) - Go library to interface with Solana JSON RPC and WebSocket interfaces.
- <code>&nbsp;&nbsp;&nbsp;980</code> [gno](https://github.com/gnolang/gno) - A comprehensive smart contract suite built with Golang and Gnolang, a deterministic, purpose-built Go variant for blockchains.
- <code>&nbsp;&nbsp;&nbsp;765</code> [cometbft](https://github.com/cometbft/cometbft) - A distributed, Byzantine fault-tolerant, deterministic state machine replication engine. It is a fork of Tendermint Core and implements the Tendermint consensus algorithm.
- <code>&nbsp;&nbsp;&nbsp;451</code> [gossamer](https://github.com/ChainSafe/gossamer) - A Go implementation of the Polkadot Host.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> [gosemble](https://github.com/LimeChain/gosemble) - A Go-based framework for building Polkadot/Substrate-compatible runtimes.

**[⬆ back to top](#contents)**

## Bot Building

*Libraries for building and working with bots.*

- <code>&nbsp;&nbsp;6228</code> [telegram-bot-api](https://github.com/go-telegram-bot-api/telegram-bot-api) - Simple and clean Telegram bot client.
- <code>&nbsp;&nbsp;4411</code> [telebot](https://github.com/tucnak/telebot) - Telegram bot framework is written in Go.
- <code>&nbsp;&nbsp;2023</code> [wayback](https://github.com/wabarc/wayback) - A bot for Telegram, Mastodon, Slack, and other messaging platforms archives webpages.
- <code>&nbsp;&nbsp;1263</code> [bot](https://github.com/go-telegram/bot) - Zero-dependencies Telegram Bot library with additional UI components
- <code>&nbsp;&nbsp;&nbsp;747</code> [telego](https://github.com/mymmrac/telego) - Telegram Bot API library for Golang with full one-to-one API implementation.
- <code>&nbsp;&nbsp;&nbsp;537</code> [arikawa](https://github.com/diamondburned/arikawa) - A library and framework for the Discord API.
- <code>&nbsp;&nbsp;&nbsp;406</code> [echotron](https://github.com/NicoNex/echotron) - An elegant and concurrent library for Telegram Bots in Go.
- <code>&nbsp;&nbsp;&nbsp;378</code> [go-twitch-irc](https://github.com/gempir/go-twitch-irc) - Library to write bots for twitch.tv chat
- <code>&nbsp;&nbsp;&nbsp;264</code> [go-sarah](https://github.com/oklahomer/go-sarah) - Framework to build a bot for desired chat services including LINE, Slack, Gitter, and more.
- <code>&nbsp;&nbsp;&nbsp;199</code> [slack-bot](https://github.com/innogames/slack-bot) - Ready to use Slack Bot for lazy developers: Custom commands, Jenkins, Jira, Bitbucket, Github...
- <code>&nbsp;&nbsp;&nbsp;120</code> [go-tg](https://github.com/mr-linch/go-tg) - Generated from official docs Go client library for accessing Telegram Bot API, with batteries for building complex bots included.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;55</code> [slacker](https://github.com/slack-io/slacker) - Easy to use framework to create Slack bots.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> [micha](https://github.com/onrik/micha) - Go Library for Telegram bot api.
- [go-joe](https://joe-bot.net) - A general-purpose bot library inspired by Hubot but written in Go.

**[⬆ back to top](#contents)**

## Build Automation

*Libraries and tools help with build automation.*

- <code>&nbsp;21273</code> [air](https://github.com/cosmtrek/air) - Air - Live reload for Go apps.
- <code>&nbsp;13256</code> [Task](https://github.com/go-task/task) - simple "Make" alternative.
- <code>&nbsp;&nbsp;4459</code> [realize](https://github.com/tockins/realize) - Go build a system with file watchers and live to reload. Run, build and watch file changes with custom paths.
- <code>&nbsp;&nbsp;4418</code> [mage](https://github.com/magefile/mage) - Mage is a make/rake-like build tool using Go.
- <code>&nbsp;&nbsp;1728</code> [mmake](https://github.com/tj/mmake) - Modern Make.
- <code>&nbsp;&nbsp;1309</code> [xc](https://github.com/joerdav/xc) - Task runner with README.md defined tasks, executable markdown.
- <code>&nbsp;&nbsp;&nbsp;630</code> [goyek](https://github.com/goyek/goyek) - Create build pipelines in Go.
- <code>&nbsp;&nbsp;&nbsp;314</code> [taskctl](https://github.com/taskctl/taskctl) - Concurrent task runner.
- <code>&nbsp;&nbsp;&nbsp;235</code> [1build](https://github.com/gopinath-langote/1build) - Command line tool to frictionlessly manage project-specific commands.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;83</code> [gaper](https://github.com/maxclaus/gaper) - Builds and restarts a Go project when it crashes or some watched file changes.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;43</code> [anko](https://github.com/GuilhermeCaruso/anko) - Simple application watcher for multiple programming languages.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [gob](https://github.com/kcmvp/gob) - [Gradle](https://docs.gradle.org/)/[Maven](https://maven.apache.org/) like build tool for Go projects.
- [gilbert](https://go-gilbert.github.io) - Build system and task runner for Go projects.

**[⬆ back to top](#contents)**

## Command Line

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

- <code>&nbsp;33820</code> [bubbletea](https://github.com/charmbracelet/bubbletea) - Go framework to build terminal apps, based on The Elm Architecture.
- <code>&nbsp;19729</code> [fx](https://github.com/antonmedv/fx) - Terminal JSON viewer & processor.
- <code>&nbsp;13395</code> [termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by <code>&nbsp;15629</code> [blessed-contrib](https://github.com/yaronn/blessed-contrib).
- <code>&nbsp;10319</code> [gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces.
- <code>&nbsp;&nbsp;9354</code> [lipgloss](https://github.com/charmbracelet/lipgloss) - Declaratively define styles for color, format and layout in the terminal.
- <code>&nbsp;&nbsp;6671</code> [bubbles](https://github.com/charmbracelet/bubbles) - TUI components for bubbletea.
- <code>&nbsp;&nbsp;5393</code> [go-prompt](https://github.com/c-bata/go-prompt) - Library for building a powerful interactive prompt, inspired by <code>&nbsp;&nbsp;9863</code> [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).
- <code>&nbsp;&nbsp;5197</code> [pterm](https://github.com/pterm/pterm) - A library to beautify console output on every platform with many combinable components.
- <code>&nbsp;&nbsp;4733</code> [termbox-go](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces.
- <code>&nbsp;&nbsp;4452</code> [progressbar](https://github.com/schollz/progressbar) - Basic thread-safe progress bar that works in every OS.
- <code>&nbsp;&nbsp;2856</code> [termdash](https://github.com/mum4k/termdash) - Go terminal dashboard based on **termbox-go** and inspired by <code>&nbsp;13395</code> [termui](https://github.com/gizak/termui).
- <code>&nbsp;&nbsp;2855</code> [asciigraph](https://github.com/guptarohit/asciigraph) - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies.
- <code>&nbsp;&nbsp;2452</code> [spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options.
- <code>&nbsp;&nbsp;2421</code> [mpb](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications.
- <code>&nbsp;&nbsp;2132</code> [uiprogress](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications.
- <code>&nbsp;&nbsp;1874</code> [termenv](https://github.com/muesli/termenv) - Advanced ANSI style & color support for your terminal applications.
- <code>&nbsp;&nbsp;1708</code> [uilive](https://github.com/gosuri/uilive) - Library for updating terminal output in real time.
- <code>&nbsp;&nbsp;1554</code> [gookit/color](https://github.com/gookit/color) - Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows.
- <code>&nbsp;&nbsp;1463</code> [aurora](https://github.com/logrusorgru/aurora) - ANSI terminal colors that support fmt.Printf/Sprintf.
- <code>&nbsp;&nbsp;&nbsp;866</code> [go-isatty](https://github.com/mattn/go-isatty) - isatty for golang.
- <code>&nbsp;&nbsp;&nbsp;795</code> [go-colorable](https://github.com/mattn/go-colorable) - Colorable writer for windows.
- <code>&nbsp;&nbsp;&nbsp;741</code> [uitable](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data.
- <code>&nbsp;&nbsp;&nbsp;571</code> [box-cli-maker](https://github.com/Delta456/box-cli-maker) - Make Highly Customized Boxes for your CLI.
- <code>&nbsp;&nbsp;&nbsp;556</code> [gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text.
- <code>&nbsp;&nbsp;&nbsp;544</code> [simpletable](https://github.com/alexeyco/simpletable) - Simple tables in a terminal with Go.
- <code>&nbsp;&nbsp;&nbsp;508</code> [bubble-table](https://github.com/Evertras/bubble-table) - An interactive table component for bubbletea.
- <code>&nbsp;&nbsp;&nbsp;466</code> [chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output.
- <code>&nbsp;&nbsp;&nbsp;450</code> [yacspin](https://github.com/theckman/yacspin) - Yet Another CLi Spinner package, for working with terminal spinners.
- <code>&nbsp;&nbsp;&nbsp;359</code> [tabby](https://github.com/cheynewallace/tabby) - A tiny library for super simple Golang tables.
- <code>&nbsp;&nbsp;&nbsp;216</code> [go-colortext](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals.
- <code>&nbsp;&nbsp;&nbsp;107</code> [cfmt](https://github.com/mingrammer/cfmt) - Contextual fmt inspired by bootstrap color classes.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;70</code> [cfmt](https://github.com/i582/cfmt) - Simple and convenient formatted stylized output fully compatible with fmt library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> [marker](https://github.com/cyucelen/marker) - Easiest way to match and mark strings for colorful terminal outputs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> [ctc](https://github.com/wzshiming/ctc) - The non-invasive cross-platform terminal color library does not need to modify the Print method.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> [table](https://github.com/tomlazar/table) - Small library for terminal color based tables.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [go-palette](https://github.com/abusomani/go-palette) - Go library that provides elegant and convenient style definitions using ANSI colors. Fully compatible & wraps the [fmt library](https://pkg.go.dev/fmt) for nice terminal layouts.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> [go-ataman](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> [crab-config-files-templating](https://github.com/alfiankan/crab-config-files-templating) - Dynamic configuration file templating tool for kubernetes manifest or general configuration files.

**[⬆ back to top](#contents)**

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

- <code>&nbsp;41306</code> [cobra](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions.
- <code>&nbsp;23379</code> [urfave/cli](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).
- <code>&nbsp;&nbsp;6075</code> [elvish](https://github.com/elves/elvish) - An expressive programming language and a versatile interactive shell.
- <code>&nbsp;&nbsp;3541</code> [kingpin](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands (superseded by `kong`; see below).
- <code>&nbsp;&nbsp;2897</code> [Dnote](https://github.com/dnote/dnote) - A simple command line notebook with multi-device sync.
- <code>&nbsp;&nbsp;2667</code> [go-flags](https://github.com/jessevdk/go-flags) - go command line option parser.
- <code>&nbsp;&nbsp;2616</code> [pflag](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.
- <code>&nbsp;&nbsp;2170</code> [go-arg](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go.
- <code>&nbsp;&nbsp;1377</code> [ops](https://github.com/nanovms/ops) - Unikernel Builder/Orchestrator.
- <code>&nbsp;&nbsp;1377</code> [carapace-bin](https://github.com/rsteube/carapace-bin) - Multi-shell multi-command argument completer.
- <code>&nbsp;&nbsp;1070</code> [liner](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces.
- <code>&nbsp;&nbsp;&nbsp;939</code> [complete](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion.
- <code>&nbsp;&nbsp;&nbsp;886</code> [mow.cli](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation.
- <code>&nbsp;&nbsp;&nbsp;864</code> [flaggy](https://github.com/integrii/flaggy) - A robust and idiomatic flags package with excellent subcommand support.
- <code>&nbsp;&nbsp;&nbsp;777</code> [carapace](https://github.com/rsteube/carapace) - Command argument completion generator for spf13/cobra.
- <code>&nbsp;&nbsp;&nbsp;729</code> [mkideal/cli](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang struct tags.
- <code>&nbsp;&nbsp;&nbsp;623</code> [argparse](https://github.com/akamensky/argparse) - Command line argument parser inspired by Python's argparse module.
- <code>&nbsp;&nbsp;&nbsp;224</code> [wmenu](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompt users to make choices.
- <code>&nbsp;&nbsp;&nbsp;218</code> [climax](https://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.
- <code>&nbsp;&nbsp;&nbsp;193</code> [clîr](https://github.com/leaanthony/clir) - A Simple and Clear CLI library. Dependency free.
- <code>&nbsp;&nbsp;&nbsp;181</code> [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - cli application framework with auto configuration and dependency injection.
- <code>&nbsp;&nbsp;&nbsp;176</code> [commandeer](https://github.com/jaffee/commandeer) - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags.
- <code>&nbsp;&nbsp;&nbsp;162</code> [sflags](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin, and other libraries.
- <code>&nbsp;&nbsp;&nbsp;148</code> [job](https://github.com/liujianping/job) - JOB, make your short-term command as a long-term job.
- <code>&nbsp;&nbsp;&nbsp;140</code> [cmdr](https://github.com/hedzr/cmdr) - A POSIX/GNU style, getopt-like command-line UI Go library.
- <code>&nbsp;&nbsp;&nbsp;131</code> [teris-io/cli](https://github.com/teris-io/cli) - Simple and complete API for building command line interfaces in Go.
- <code>&nbsp;&nbsp;&nbsp;129</code> [ukautz/clif](https://github.com/ukautz/clif) - Small command line interface framework.
- <code>&nbsp;&nbsp;&nbsp;128</code> [acmd](https://github.com/cristalhq/acmd) - Simple, useful, and opinionated CLI package in Go.
- <code>&nbsp;&nbsp;&nbsp;121</code> [env](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs.
- <code>&nbsp;&nbsp;&nbsp;119</code> [readline](https://github.com/reeflective/readline) - Shell library with modern and easy to use UI features.
- <code>&nbsp;&nbsp;&nbsp;109</code> [version](https://github.com/mszostok/version) - Collects and displays CLI version information in multiple formats along with upgrade notice.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;97</code> [console](https://github.com/reeflective/console) Closed-loop application library for Cobra commands, with oh-my-posh prompts, and more.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> [wlog](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> [command-chain](https://github.com/rainu/go-command-chain) - A go library for configure and run command chains - such as pipelining in unix shells.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;66</code> [gocmd](https://github.com/devfacet/gocmd) - Go library for building command line applications.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;62</code> [strumt](https://github.com/antham/strumt) - Library to create prompt chain.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;61</code> [go-getoptions](https://github.com/DavidGamba/go-getoptions) - Go option parser inspired by the flexibility of Perl’s GetOpt::Long.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> [flagvar](https://github.com/sgreben/flagvar) - A collection of flag argument types for Go's standard `flag` package.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;44</code> [cmd](https://github.com/posener/cmd) - Extends the standard `flag` package to support sub commands and more in idiomatic way.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> [mcli](https://github.com/jxskiss/mcli) - A minimal but very powerful cli library for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> [argv](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> [go-readline-ny](https://github.com/nyaosorg/go-readline-ny) - A customizable line-editing library with Emacs keybindings, Unicode support, completion, and syntax highlighting. Used in NYAGOS shell.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> [hashicorp/cli](https://github.com/hashicorp/cli) - Go library for implementing command-line interfaces.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> [sand](https://github.com/Zaba505/sand) - Simple API for creating interpreters and so much more.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> [ts](https://github.com/liujianping/ts) - Timestamp convert & compare tool.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> [carapace-spec](https://github.com/rsteube/carapace-spec) - Define simple completions using a spec file.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> [subcmd](https://github.com/bobg/subcmd) - Another approach to parsing and running subcommands. Works alongside the standard `flag` package.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [getopt](https://github.com/jon-codes/getopt) - An accurate Go `getopt`, validated against the GNU libc implementation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> [goopt](https://github.com/napalu/goopt) - A declarative, struct-tag based CLI framework for Go, with a broad feature set such as hierarchical commands/flags, i18n, shell completion, and validation.

**[⬆ back to top](#contents)**

## Configuration

*Libraries for configuration parsing.*

- <code>&nbsp;29005</code> [viper](https://github.com/spf13/viper) - Go configuration with fangs.
- <code>&nbsp;&nbsp;9586</code> [godotenv](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`).
- <code>&nbsp;&nbsp;8435</code> [sonic](https://github.com/bytedance/sonic) - A blazingly fast JSON serializing & deserializing library.
- <code>&nbsp;&nbsp;5663</code> [env](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults).
- <code>&nbsp;&nbsp;5290</code> [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - Go library for managing configuration data from environment variables.
- <code>&nbsp;&nbsp;3516</code> [ini](https://github.com/go-ini/ini) - Go package to read and write INI files.
- <code>&nbsp;&nbsp;3362</code> [koanf](https://github.com/knadh/koanf) - Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line.
- <code>&nbsp;&nbsp;2739</code> [kong](https://github.com/alecthomas/kong) - Command-line parser with support for arbitrarily complex command-line structures and additional sources of configuration such as YAML, JSON, TOML, etc (successor to `kingpin`).
- <code>&nbsp;&nbsp;1879</code> [cleanenv](https://github.com/ilyakaznacheev/cleanenv) - Minimalistic configuration reader (from files, ENV, and wherever you want).
- <code>&nbsp;&nbsp;&nbsp;854</code> [xdg](https://github.com/adrg/xdg) - Go implementation of the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/latest/) and [XDG user directories](https://wiki.archlinux.org/index.php/XDG_user_directories).
- <code>&nbsp;&nbsp;&nbsp;644</code> [konfig](https://github.com/lalamove/konfig) - Composable, observable and performant config handling for Go for the distributed processing era.
- <code>&nbsp;&nbsp;&nbsp;595</code> [aconfig](https://github.com/cristalhq/aconfig) - Simple, useful and opinionated config loader.
- <code>&nbsp;&nbsp;&nbsp;559</code> [gookit/config](https://github.com/gookit/config) - application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge.
- <code>&nbsp;&nbsp;&nbsp;504</code> [confita](https://github.com/heetch/confita) - Load configuration in cascade from multiple backends into a struct.
- <code>&nbsp;&nbsp;&nbsp;383</code> [fig](https://github.com/kkyr/fig) - Tiny library for reading configuration from a file and from environment variables (with validation & defaults).
- <code>&nbsp;&nbsp;&nbsp;365</code> [GoLobby/Config](https://github.com/golobby/config) - GoLobby Config is a lightweight yet powerful configuration manager for the Go programming language.
- <code>&nbsp;&nbsp;&nbsp;338</code> [hjson](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments.
- <code>&nbsp;&nbsp;&nbsp;338</code> [config](https://github.com/JeremyLoy/config) - Cloud native application configuration. Bind ENV to structs in only two lines.
- <code>&nbsp;&nbsp;&nbsp;337</code> [konf](https://github.com/nil-go/konf) - The simplest API for reading/watching config from file, env, flag and clouds (e.g. AWS, Azure, GCP).
- <code>&nbsp;&nbsp;&nbsp;274</code> [store](https://github.com/tucnak/store) - Lightweight configuration manager for Go.
- <code>&nbsp;&nbsp;&nbsp;244</code> [envconfig](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables.
- <code>&nbsp;&nbsp;&nbsp;214</code> [joshbetz/config](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP.
- <code>&nbsp;&nbsp;&nbsp;192</code> [zerocfg](https://github.com/chaindead/zerocfg) - Zero-effort, concise configuration management that avoids boilerplate and repetitive code, supports multiple sources with priority overrides.
- <code>&nbsp;&nbsp;&nbsp;134</code> [harvester](https://github.com/beatlabs/harvester) - Harvester, a easy to use static and dynamic configuration package supporting seeding, env vars and Consul integration.
- <code>&nbsp;&nbsp;&nbsp;118</code> [onion](https://github.com/goraz/onion) - Layer based configuration for Go, Supports JSON, TOML, YAML, properties, etcd, env, and encryption using PGP.
- <code>&nbsp;&nbsp;&nbsp;108</code> [configuration](https://github.com/BoRuDar/configuration) - Library for initializing configuration structs from env variables, files, flags and 'default' tag.
- <code>&nbsp;&nbsp;&nbsp;100</code> [envh](https://github.com/antham/envh) - Helpers to manage environment variables.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;94</code> [configuro](https://github.com/sherifabdlnaby/configuro) - opinionated configuration loading & validation framework from ENV and Files focused towards 12-Factor compliant applications.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> [hocon](https://github.com/gurkankaymak/hocon) - Configuration library for working with the HOCON(a human-friendly JSON superset) format, supports features like environment variables, referencing other values, comments and multiple files.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;72</code> [env](https://github.com/junk1tm/env) - A lightweight package for loading environment variables into structs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;72</code> [uConfig](https://github.com/omeid/uconfig) - Lightweight, zero-dependency, and extendable configuration management.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;68</code> [gofigure](https://github.com/ian-kent/gofigure) - Go application configuration made easy.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;62</code> [go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) - Go package that fetches parameters from AWS System Manager - Parameter Store.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> [config](https://github.com/num30/config) - configure your app using file, environment variables, or flags in two lines of code
- <code>&nbsp;&nbsp;&nbsp;&nbsp;55</code> [configure](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep your config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> [go-cfg](https://github.com/dsbasko/go-cfg) - The library provides a unified way to read configuration data into a structure from various sources, such as env, flags, and configuration files (.json, .yaml, .toml, .env).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;43</code> [go-up](https://github.com/ufoscout/go-up) - A simple configuration library with recursive placeholders resolution and no magic.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;42</code> [genv](https://github.com/sakirsensoy/genv) - Read environment variables easily with dotenv support.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> [ingo](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> [confiq](https://github.com/greencoda/confiq) - Structured data format to config struct decoder library for Go - supporting multiple data formats
- <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> [mini](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> [conflate](https://github.com/the4thamigo-uk/conflate) - Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> [bcl](https://github.com/wkhere/bcl) - BCL is a configuration language similar to HCL.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> [go-ssm-config](https://github.com/ianlopshire/go-ssm-config) - Go utility for loading configuration parameters from AWS SSM (Parameter Store).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> [nasermirzaei89/env](https://github.com/nasermirzaei89/env) - Simple useful package for read environment variables.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [go-array](https://github.com/deatil/go-array) - A Go package that read or set data from map, slice or json.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> [ini](https://github.com/wlevene/ini) - INI Parser & Write Library, Unmarshal to Struct, Marshal to Json, Write File, watch file.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> [yamagiconf](https://github.com/romshark/yamagiconf) - The "safe subset" of YAML for Go configs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> [go-ini](https://github.com/subpop/go-ini) - A Go package that marshals and unmarshals INI-files.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [envyaml](https://github.com/yuseferi/envyaml) - Yaml with environment variables reader. it helps to have secrets as environment variable but load them configs as structured Yaml.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> [typenv](https://github.com/diegomarangoni/typenv) - Minimalistic, zero dependency, typed environment variables library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [go-conf](https://github.com/ThomasObenaus/go-conf) - Simple library for application configuration based on annotated structs. It supports reading the configuration from environment variables, config files and command line parameters.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [piper](https://github.com/Yiling-J/piper) - Viper wrapper with config inheritance and key generation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> [gonfig](https://github.com/milad-abbasi/gonfig) - Tag-based configuration parser which loads values from different providers into typesafe struct.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> [nfigure](https://github.com/muir/nfigure) - Per-library struct-tag based configuration from command lines (Posix & Go-style); environment, JSON, YAML
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> [swap](https://github.com/oblq/swap) - Instantiate/configure structs recursively, based on build environment. (YAML, TOML, JSON and env).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [env](https://github.com/syntaqx/env) - An environment utility package with support for unmarshaling into structs
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [hedzr/store](https://github.com/hedzr/store) - Extensible, high-performance configuration management library, optimized for hierarchical data.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> [GoCfg](https://github.com/Jagerente/gocfg) - Config manager with Struct Tags based contracts, custom value providers, parsers, and documentation generation. Customizable yet simple.

**[⬆ back to top](#contents)**

## Continuous Integration

*Tools for help with continuous integration.*

- <code>&nbsp;33035</code> [drone](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go.
- <code>&nbsp;&nbsp;5304</code> [woodpecker](https://github.com/woodpecker-ci/woodpecker) - Woodpecker is a community fork of the Drone CI system.
- <code>&nbsp;&nbsp;4742</code> [CDS](https://github.com/ovh/cds) - Enterprise-Grade CI/CD and DevOps Automation Open Source Platform.
- <code>&nbsp;&nbsp;2568</code> [muffet](https://github.com/raviqqe/muffet) - Fast website link checker in Go, see <code>&nbsp;&nbsp;2854</code> [alternatives](https://github.com/lycheeverse/lychee#features).
- <code>&nbsp;&nbsp;&nbsp;952</code> [abstruse](https://github.com/bleenco/abstruse) - Abstruse is a distributed CI platform.
- <code>&nbsp;&nbsp;&nbsp;791</code> [goveralls](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system.
- <code>&nbsp;&nbsp;&nbsp;573</code> [gotestfmt](https://github.com/GoTestTools/gotestfmt) - go test output for humans.
- <code>&nbsp;&nbsp;&nbsp;161</code> [go-test-coverage](https://github.com/vladopajic/go-test-coverage) - Tool and GitHub action which reports issues when test coverage is below set threshold.
- <code>&nbsp;&nbsp;&nbsp;115</code> [overalls](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;65</code> [gomason](https://github.com/nikogura/gomason) - Test, Build, Sign, and Publish your go binaries from a clean workspace.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> [dot](https://github.com/opnlabs/dot) - A minimal, local first continuous integration system that uses Docker to run jobs concurrently in stages.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [roveralls](https://github.com/LawrenceWoodman/roveralls) - Recursive coverage testing tool.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [go-beautiful-html-coverage](https://github.com/gha-common/go-beautiful-html-coverage) - A GitHub Action to track code coverage in your pull requests, with a beautiful HTML preview, for free.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [go-fuzz-action](https://github.com/jidicula/go-fuzz-action) - Use Go 1.18's built-in fuzz testing in GitHub Actions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [go-semver-release](https://github.com/s0ders/go-semver-release) - Automate the semantic versioning of Git repositories.
- [Bencher](https://bencher.dev/) - A suite of continuous benchmarking tools designed to catch performance regressions in CI.

**[⬆ back to top](#contents)**

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

- <code>&nbsp;&nbsp;&nbsp;212</code> [go-libsass](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project.

**[⬆ back to top](#contents)**

## Data Integration Frameworks

*Frameworks for performing ELT / ETL*

- <code>&nbsp;&nbsp;8423</code> [Benthos](https://github.com/benthosdev/benthos) - A message streaming bridge between a range of protocols.
- <code>&nbsp;&nbsp;6164</code> [CloudQuery](http://github.com/cloudquery/cloudquery) - A high-performance ELT data integration framework with pluggable architecture.
- <code>&nbsp;&nbsp;1054</code> [omniparser](https://github.com/jf-tech/omniparser) - A versatile ETL library that parses text input (CSV/txt/JSON/XML/EDI/X12/EDIFACT/etc) in streaming fashion and transforms data into JSON output using data-driven schema.

**[⬆ back to top](#contents)**

## Data Structures and Algorithms

### Bit-packing and Compression

- <code>&nbsp;&nbsp;2743</code> [roaring](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets.
- <code>&nbsp;&nbsp;&nbsp;232</code> [binpacker](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream.
- <code>&nbsp;&nbsp;&nbsp;164</code> [bit](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions.
- <code>&nbsp;&nbsp;&nbsp;100</code> [crunch](https://github.com/superwhiskers/crunch) - Go package implementing buffers for handling various datatypes easily.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;46</code> [bingo](https://github.com/iancmcc/bingo) - Fast, zero-allocation, lexicographical-order-preserving packing of native types to bytes.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> [go-ef](https://github.com/amallia/go-ef) - A Go implementation of the Elias-Fano encoding.

### Bit Sets

- <code>&nbsp;&nbsp;1437</code> [bitset](https://github.com/bits-and-blooms/bitset) - Go package implementing bitsets.
- <code>&nbsp;&nbsp;&nbsp;347</code> [bitmap](https://github.com/kelindar/bitmap) - Dense, zero-allocation, SIMD-enabled bitmap/bitset in Go.

### Bloom and Cuckoo Filters

- <code>&nbsp;&nbsp;2632</code> [bloom](https://github.com/bits-and-blooms/bloom) - Go package implementing Bloom filters.
- <code>&nbsp;&nbsp;1617</code> [boomfilters](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams.
- <code>&nbsp;&nbsp;1183</code> [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go.
- <code>&nbsp;&nbsp;&nbsp;301</code> [cuckoo-filter](https://github.com/linvon/cuckoo-filter) - Cuckoo filter: a comprehensive cuckoo filter, which is configurable and space optimized compared with other implements, and all features mentioned in original paper are available.
- <code>&nbsp;&nbsp;&nbsp;147</code> [bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go.
- <code>&nbsp;&nbsp;&nbsp;141</code> [ring](https://github.com/TheTannerRyan/ring) - Go implementation of a high performance, thread safe bloom filter.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;87</code> [bloom](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> [bloomfilter](https://github.com/OldPanda/bloomfilter) - Yet another Bloomfilter implementation in Go, compatible with Java's Guava library.

### Data Structure and Algorithm Collections

- <code>&nbsp;17050</code> [gods](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.
- <code>&nbsp;&nbsp;7821</code> [go-datastructures](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures.
- <code>&nbsp;&nbsp;1103</code> [gostl](https://github.com/liyue201/gostl) - Data structure and algorithm library for go, designed to provide functions similar to C++ STL.
- <code>&nbsp;&nbsp;&nbsp;824</code> [algorithms](https://github.com/shady831213/algorithms) - Algorithms and data structures.CLRS study.

### Iterators

- <code>&nbsp;&nbsp;&nbsp;191</code> [iter](https://github.com/disksing/iter) - Go implementation of C++ STL iterators and algorithms.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [goterator](https://github.com/yaa110/goterator) - Iterator implementation to provide map and reduce functionalities.

### Maps

See also [Database](#database) for more complex key-value stores, and [Trees](#trees) for additional ordered map implementations.

- <code>&nbsp;&nbsp;&nbsp;&nbsp;97</code> [cmap](https://github.com/lrita/cmap) - a thread-safe concurrent map for go, support using `interface{}` as key and auto scale up shards.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> [goradd/maps](https://github.com/goradd/maps) - Go 1.18+ generic map interface for maps; safe maps; ordered maps; ordered, safe maps; etc.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> [dict](https://github.com/srfrog/dict) - Python-like dictionaries (dict) for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [go-shelve](https://github.com/lucmq/go-shelve) - A persistent, map-like object for the Go programming language. Supports multiple embedded key-value stores.

### Miscellaneous Data Structures and Algorithms

- <code>&nbsp;&nbsp;3216</code> [gota](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go.
- <code>&nbsp;&nbsp;&nbsp;986</code> [hyperloglog](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.
- <code>&nbsp;&nbsp;&nbsp;358</code> [go-geoindex](https://github.com/hailocab/go-geoindex) - In-memory geo index.
- <code>&nbsp;&nbsp;&nbsp;137</code> [go-rquad](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding.
- <code>&nbsp;&nbsp;&nbsp;105</code> [gogu](https://github.com/esimov/gogu) - A comprehensive, reusable and efficient concurrent-safe generics utility functions and data structures library.
- <code>&nbsp;&nbsp;&nbsp;100</code> [go-rampart](https://github.com/francesconi/go-rampart) - Determine how intervals relate to each other.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;93</code> [go-tuple](https://github.com/barweiss/go-tuple) - Generic tuple implementation for Go 1.18+.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;83</code> [go-generics](https://github.com/bobg/go-generics) - Generic slice, map, set, iterator, and goroutine utilities.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;80</code> [fsm](https://github.com/cocoonspace/fsm) - Finite-State Machine package.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;70</code> [hide](https://github.com/emvi/hide) - ID type with marshalling to/from hash to prevent sending IDs to clients.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> [count-min-log](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;57</code> [concurrent-writer](https://github.com/free/concurrent-writer) - Highly concurrent drop-in replacement for `bufio.Writer`.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;52</code> [genfuncs](https://github.com/nwillc/genfuncs) - Go 1.18+ generics package inspired by Kotlin's Sequence and Map.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;46</code> [go18ds](https://github.com/daichi-m/go18ds) - Go Data Structures using Go 1.18 generics.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> [quadtree](https://github.com/s0rg/quadtree) - Generic, zero-alloc, 100%-test covered quadtree.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> [slices](https://github.com/twharmon/slices) - Pure, generic functions for slices.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> [gofal](https://github.com/xxjwxc/gofal) - fractional api for Go.

### Nullable Types

- <code>&nbsp;&nbsp;&nbsp;&nbsp;87</code> [nan](https://github.com/kak-tus/nan) - Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;46</code> [typ](https://github.com/gurukami/typ) - Null Types, Safe primitive type conversion and fetching value from complex structures.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> [null](https://github.com/emvi/null) - Nullable Go types that can be marshalled/unmarshalled to/from JSON.

### Queues

- <code>&nbsp;&nbsp;5882</code> [hatchet](https://github.com/hatchet-dev/hatchet) - Distributed, Fault-tolerant task queue.
- <code>&nbsp;&nbsp;&nbsp;694</code> [deque](https://github.com/gammazero/deque) - Fast ring-buffer deque (double-ended queue).
- <code>&nbsp;&nbsp;&nbsp;431</code> [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) - Concurrent FIFO queue.
- <code>&nbsp;&nbsp;&nbsp;312</code> [queue](https://github.com/adrianbrad/queue) - Multiple thread-safe, generic queue implementations for Go.
- <code>&nbsp;&nbsp;&nbsp;201</code> [deque](https://github.com/edwingeng/deque) - A highly optimized double-ended queue.
- <code>&nbsp;&nbsp;&nbsp;133</code> [memlog](https://github.com/embano1/memlog) - An easy to use, lightweight, thread-safe and append-only in-memory data structure inspired by Apache Kafka.
- [dqueue](https://github.com/vodolaz095/dqueue) - Simple, in memory, zero dependency and battle tested, thread-safe deferred queue.

### Sets

- <code>&nbsp;&nbsp;4560</code> [golang-set](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;52</code> [goset](https://github.com/zoumo/goset) - A useful Set collection implementation for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> [set](https://github.com/StudioSol/set) - Simple set data structure implementation in Go using LinkedHashMap.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> [dsu](https://github.com/ihebu/dsu) - Disjoint Set data structure implementation in Go.

### Text Analysis

- <code>&nbsp;10476</code> [bleve](https://github.com/blevesearch/bleve) - Modern text indexing library for go.
- <code>&nbsp;&nbsp;&nbsp;776</code> [trie](https://github.com/derekparker/trie) - Trie implementation in Go.
- <code>&nbsp;&nbsp;&nbsp;522</code> [go-edlib](https://github.com/hbollon/go-edlib) - Go string comparison and edit distance algorithms library (Levenshtein, LCS, Hamming, Damerau levenshtein, Jaro-Winkler, etc.) compatible with Unicode.
- <code>&nbsp;&nbsp;&nbsp;424</code> [levenshtein](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go.
- <code>&nbsp;&nbsp;&nbsp;395</code> [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;89</code> [levenshtein](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;43</code> [ptrie](https://github.com/viant/ptrie) - An implementation of prefix tree.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> [mspm](https://github.com/BlackRabbitt/mspm) - Multi-String Pattern Matching Algorithm for information retrieval.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [parsefields](https://github.com/MonaxGT/parsefields) - Tools for parse JSON-like logs for collecting unique fields and events.

### Trees

- <code>&nbsp;&nbsp;&nbsp;287</code> [skiplist](https://github.com/MauriceGit/skiplist) - Very fast Go Skiplist implementation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;84</code> [skiplist](https://github.com/gansidui/skiplist) - Skiplist implementation in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;64</code> [treemap](https://github.com/igrmk/treemap) - Generic key-sorted map using a red-black tree under the hood.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> [hashsplit](http://github.com/bobg/hashsplit) - Split byte streams into chunks, and arrange chunks into trees, with boundaries determined by content, not position.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> [treap](https://github.com/perdata/treap) - Persistent, fast ordered map using tree heaps.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> [merkle](https://github.com/bobg/merkle) - Space-efficient computation of Merkle root hashes and inclusion proofs.

### Pipes

- <code>&nbsp;&nbsp;&nbsp;&nbsp;58</code> [pipeline](https://github.com/hyfather/pipeline) - An implementation of pipelines with fan-in and fan-out.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> [ordered-concurrently](https://github.com/tejzpr/ordered-concurrently) - Go module that processes work concurrently and returns output in a channel in the order of input.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> [parapipe](https://github.com/nazar256/parapipe) - FIFO Pipeline which parallels execution on each stage while maintaining the order of messages and results.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [pipelines](https://github.com/nxdir-s/pipelines) - Generic pipeline functions for concurrent processing.

**[⬆ back to top](#contents)**

## Database

### Caches

*Data stores with expiring records, in-memory distributed data stores, or in-memory subsets of file-based databases.*

- <code>&nbsp;13224</code> [groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
- <code>&nbsp;&nbsp;7891</code> [BigCache](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data.
- <code>&nbsp;&nbsp;6331</code> [ristretto](https://github.com/dgraph-io/ristretto) - A high performance memory-bound Go cache.
- <code>&nbsp;&nbsp;2716</code> [gocache](https://github.com/eko/gocache) - A complete Go cache library with multiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more.
- <code>&nbsp;&nbsp;2700</code> [GCache](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC.
- <code>&nbsp;&nbsp;2268</code> [otter](https://github.com/maypok86/otter) - A high performance lockless cache for Go. Many times faster than Ristretto and friends.
- <code>&nbsp;&nbsp;2247</code> [fastcache](https://github.com/VictoriaMetrics/fastcache) - fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead.
- <code>&nbsp;&nbsp;2161</code> [cache2go](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts.
- <code>&nbsp;&nbsp;1230</code> [sturdyc](https://github.com/viccon/sturdyc) - A caching library with advanced concurrency features designed to make I/O heavy applications robust and highly performant.
- <code>&nbsp;&nbsp;1123</code> [ttlcache](https://github.com/jellydator/ttlcache) - An in-memory cache with item expiration and generics.
- <code>&nbsp;&nbsp;&nbsp;496</code> [EchoVault](https://github.com/EchoVault/EchoVault) - Embeddable Distributed in-memory data store compatible with Redis clients.
- <code>&nbsp;&nbsp;&nbsp;373</code> [cachego](https://github.com/faabiosr/cachego) - Golang Cache component for multiple drivers.
- <code>&nbsp;&nbsp;&nbsp;338</code> [theine](https://github.com/Yiling-J/theine-go) - High performance, near optimal in-memory cache with proactive TTL expiration and generics.
- <code>&nbsp;&nbsp;&nbsp;246</code> [go-freelru](https://github.com/elastic/go-freelru) A GC-less, fast and generic LRU hashmap library with optional locking, sharding, eviction and expiration.
- <code>&nbsp;&nbsp;&nbsp;226</code> [pocache](https://github.com/naughtygopher/pocache) - Pocache is a minimal cache package which focuses on a preemptive optimistic caching strategy.
- <code>&nbsp;&nbsp;&nbsp;194</code> [cache](https://github.com/akyoto/cache) - In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage.
- <code>&nbsp;&nbsp;&nbsp;160</code> [bcache](https://github.com/iwanbk/bcache) - Eventually consistent distributed in-memory cache Go library.
- <code>&nbsp;&nbsp;&nbsp;157</code> [go-cache](https://github.com/viney-shih/go-cache) - A flexible multi-layer Go caching library to deal with in-memory and shared cache by adopting Cache-Aside pattern.
- <code>&nbsp;&nbsp;&nbsp;125</code> [imcache](https://github.com/erni27/imcache) - A generic in-memory cache Go library. It supports expiration, sliding expiration, max entries limit, eviction callbacks and sharding.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;98</code> [go-mcache](https://github.com/OrlovEvgeny/go-mcache) - Fast in-memory key:value store/cache library. Pointer caches.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;75</code> [timedmap](https://github.com/zekroTJA/timedmap) - Map with expiring key-value pairs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> [couchcache](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> [2q](https://github.com/floatdrop/2q) - 2Q in-memory cache implementation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) - BigCache with clustering support and individual item expiration.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> [icache](https://github.com/mdaliyan/icache) - A High Performance, Generic, thread-safe, zero-dependency cache package.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [coherence-go-client](https://github.com/oracle/coherence-go-client) - Full implementation of Oracle Coherence cache API for Go applications using gRPC as network transport.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [gdcache](https://github.com/ulovecode/gdcache) - A pure non-intrusive cache library implemented by golang, you can use it to implement your own distributed cache.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> [nscache](https://github.com/no-src/nscache) - A Go caching framework that supports multiple data source drivers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> [gocache](https://github.com/yuseferi/gocache) - A data race free Go ache library with high performance and auto pruge functionality
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [ttlcache](https://github.com/cheshir/ttlcache) - In-memory key value storage with TTL for each record.

### Databases Implemented in Go

- <code>&nbsp;59740</code> [prometheus](https://github.com/prometheus/prometheus) - Monitoring system and time series database.
- <code>&nbsp;38811</code> [tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1.
- <code>&nbsp;36309</code> [Milvus](https://github.com/milvus-io/milvus) - Milvus is a vector database for embedding management, analytics and search.
- <code>&nbsp;31139</code> [cockroach](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore.
- <code>&nbsp;30394</code> [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
- <code>&nbsp;21056</code> [dgraph](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database.
- <code>&nbsp;18941</code> [dolt](https://github.com/dolthub/dolt) - Dolt – It's Git for Data.
- <code>&nbsp;16818</code> [rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite.
- <code>&nbsp;14862</code> [badger](https://github.com/dgraph-io/badger) - Fast key-value store in Go.
- <code>&nbsp;14664</code> [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL.
- <code>&nbsp;10589</code> [DiceDB](https://github.com/DiceDB/dice) - An open-source, fast, reactive, in-memory database optimized for modern hardware. Higher throughput and lower median latencies, making it ideal for modern workloads.
- <code>&nbsp;&nbsp;8987</code> [bbolt](https://github.com/etcd-io/bbolt) - An embedded key/value database for Go.
- <code>&nbsp;&nbsp;8794</code> [immudb](https://github.com/codenotary/immudb) - immudb is a lightweight, high-speed immutable database for systems and applications written in Go.
- <code>&nbsp;&nbsp;6288</code> [goleveldb](https://github.com/syndtr/goleveldb) - Implementation of the <code>&nbsp;37944</code> [LevelDB](https://github.com/google/leveldb) key/value database in Go.
- <code>&nbsp;&nbsp;5412</code> [pebble](https://github.com/cockroachdb/pebble) - RocksDB/LevelDB inspired key-value database in Go.
- <code>&nbsp;&nbsp;4840</code> [rosedb](https://github.com/roseduan/rosedb) - An embedded k-v database based on LSM+WAL, supports string, list, hash, set, zset.
- <code>&nbsp;&nbsp;4754</code> [buntdb](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.
- <code>&nbsp;&nbsp;4127</code> [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
- <code>&nbsp;&nbsp;4094</code> [redka](https://github.com/nalgeon/redka) - Redis re-implemented with SQLite.
- <code>&nbsp;&nbsp;3735</code> [godis](https://github.com/hdt3213/godis) - A Golang implemented high-performance Redis server and cluster.
- <code>&nbsp;&nbsp;3491</code> [nutsdb](https://github.com/xujiajun/nutsdb) - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as list, set, sorted set.
- <code>&nbsp;&nbsp;3040</code> [LinDB](https://github.com/lindb/lindb) - LinDB is a scalable, high performance, high availability distributed time series database.
- <code>&nbsp;&nbsp;2728</code> [tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang.
- <code>&nbsp;&nbsp;2214</code> [lotusdb](https://github.com/flower-corp/lotusdb) - Fast k/v database compatible with lsm and b+tree.
- <code>&nbsp;&nbsp;1522</code> [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) - CovenantSQL is a SQL database on blockchain.
- <code>&nbsp;&nbsp;1491</code> [column](https://github.com/kelindar/column) - High-performance, columnar, embeddable in-memory store with bitmap indexing and transactions.
- <code>&nbsp;&nbsp;1444</code> [diskv](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store.
- <code>&nbsp;&nbsp;1346</code> [pogreb](https://github.com/akrylysov/pogreb) - Embedded key-value store for read-heavy workloads.
- <code>&nbsp;&nbsp;1316</code> [Databunker](https://github.com/paranoidguy/databunker) - Personally identifiable information (PII) storage service built to comply with GDPR and CCPA.
- <code>&nbsp;&nbsp;1239</code> [objectbox-go](https://github.com/objectbox/objectbox-go) - High-performance embedded Object Database (NoSQL) with Go API.
- <code>&nbsp;&nbsp;1020</code> [eliasdb](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.
- <code>&nbsp;&nbsp;1009</code> [moss](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go.
- <code>&nbsp;&nbsp;&nbsp;767</code> [clover](https://github.com/ostafen/clover) - A lightweight document-oriented NoSQL database written in pure Golang.
- <code>&nbsp;&nbsp;&nbsp;419</code> [levigo](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB.
- <code>&nbsp;&nbsp;&nbsp;373</code> [pudge](https://github.com/recoilme/pudge) - Fast and simple key/value store written using Go's standard library.
- <code>&nbsp;&nbsp;&nbsp;263</code> [Vasto](https://github.com/chrislusf/vasto) - A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption.
- <code>&nbsp;&nbsp;&nbsp;207</code> [piladb](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures.
- <code>&nbsp;&nbsp;&nbsp;189</code> [libradb](https://github.com/amit-davidson/LibraDB) - LibraDB is a simple database with less than 1000 lines of code for learning.
- <code>&nbsp;&nbsp;&nbsp;124</code> [unitdb](https://github.com/unit-io/unitdb) - Fast timeseries database for IoT, realtime messaging applications. Access unitdb with pubsub over tcp or websocket using github.com/unit-io/unitd application.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;97</code> [hare](https://github.com/jameycribbs/hare) - A simple database management system that stores each table as a text file of line-delimited JSON.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> [Coffer](https://github.com/claygod/coffer) - Simple ACID key-value database that supports transactions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> [rotom](https://github.com/xgzlucario/rotom) - A tiny Redis server built with Golang, compatible with RESP protocols.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> [tempdb](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items.
- [Bitcask](https://git.mills.io/prologic/bitcask) - Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL).

### Database Schema Migration

- <code>&nbsp;17106</code> [migrate](https://github.com/golang-migrate/migrate) - Database migrations. CLI and Golang library.
- <code>&nbsp;12812</code> [bytebase](https://github.com/bytebase/bytebase) - Safe database schema change and version control for DevOps teams.
- <code>&nbsp;&nbsp;8858</code> [goose](https://github.com/pressly/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.
- <code>&nbsp;&nbsp;7144</code> [atlas](https://github.com/ariga/atlas) - A Database Toolkit. A CLI designed to help companies better work with their data.
- <code>&nbsp;&nbsp;6189</code> [dbmate](https://github.com/amacneil/dbmate) - A lightweight, framework-agnostic database migration tool.
- <code>&nbsp;&nbsp;3355</code> [sql-migrate](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata.
- <code>&nbsp;&nbsp;1494</code> [soda](https://github.com/gobuffalo/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
- <code>&nbsp;&nbsp;1327</code> [skeema](https://github.com/skeema/skeema) - Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools.
- <code>&nbsp;&nbsp;1111</code> [gormigrate](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM.
- <code>&nbsp;&nbsp;1033</code> [goavro](https://github.com/linkedin/goavro) - A Go package that encodes and decodes Avro data.
- <code>&nbsp;&nbsp;&nbsp;178</code> [migrator](https://github.com/lopezator/migrator) - Dead simple Go database migration library.
- <code>&nbsp;&nbsp;&nbsp;149</code> [darwin](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go.
- <code>&nbsp;&nbsp;&nbsp;121</code> [sqlize](https://github.com/sunary/sqlize) - Database migration generator. Allows generate sql migration from model and existing sql by differ them.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;86</code> [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) - A Go package to help write migrations with go-pg/pg.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> [avro](https://github.com/khezen/avro) - Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;42</code> [schema](https://github.com/adlio/schema) - Library to embed schema migrations for database/sql-compatible databases inside your Go binaries.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> [go-fixtures](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang's excellent built-in database/sql library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> [migrator](https://github.com/larapulse/migrator) - MySQL database migrator designed to run migrations to your features and manage database schema update with intuitive go code.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [libschema](https://github.com/muir/libschema) - Define your migrations separately in each library. Migrations for open source libraries. MySQL & PostgreSQL.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [gorm-seeder](https://github.com/Kachit/gorm-seeder) - Simple database seeder for Gorm ORM.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [go-pg-migrate](https://github.com/lawzava/go-pg-migrate) - CLI-friendly package for go-pg migrations management.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> [godfish](https://github.com/rafaelespinoza/godfish) - Database migration manager, works with native query language. Support for cassandra, mysql, postgres, sqlite3.

### Database Tools

- <code>&nbsp;19910</code> [vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.
- <code>&nbsp;&nbsp;8961</code> [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser.
- <code>&nbsp;&nbsp;4802</code> [go-mysql](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication.
- <code>&nbsp;&nbsp;4382</code> [pREST](https://github.com/prest/prest) - Simplify and accelerate development, ⚡ instant, realtime, high-performance on any Postgres application, existing or new.
- <code>&nbsp;&nbsp;1373</code> [chproxy](https://github.com/Vertamedia/chproxy) - HTTP proxy for ClickHouse database.
- <code>&nbsp;&nbsp;1196</code> [pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) - Advanced scheduling for PostgreSQL.
- <code>&nbsp;&nbsp;&nbsp;555</code> [rdb](https://github.com/HDT3213/rdb) - Redis RDB file parser for secondary development and memory analysis.
- <code>&nbsp;&nbsp;&nbsp;502</code> [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) - Collects small inserts and sends big requests to ClickHouse servers.
- <code>&nbsp;&nbsp;&nbsp;306</code> [wescale](https://github.com/wesql/wescale) - WeScale is a database proxy designed to enhance the scalability, performance, security, and resilience of your applications.
- <code>&nbsp;&nbsp;&nbsp;264</code> [gatewayd](https://github.com/gatewayd-io/gatewayd) - Cloud-native database gateway and framework for building data-driven applications. Like API gateways, for databases.
- <code>&nbsp;&nbsp;&nbsp;208</code> [onedump](https://github.com/liweiyi88/onedump) - Database backup from different drivers to different destinations with one command and configuration.
- <code>&nbsp;&nbsp;&nbsp;198</code> [octillery](https://github.com/knocknote/octillery) - Go package for sharding databases ( Supports every ORM or raw SQL ).
- <code>&nbsp;&nbsp;&nbsp;110</code> [dbbench](https://github.com/sj14/dbbench) - Database benchmarking tool with support for several databases and scripts.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;63</code> [gorm-multitenancy](https://github.com/bartventer/gorm-multitenancy) - Multi-tenancy support for GORM managed databases.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [dg](https://github.com/codingconcepts/dg) - A fast data generator that produces CSV files from generated relational data.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [prep](https://github.com/hexdigest/prep) - Use prepared SQL statements without changing your code.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> [database-gateway](https://github.com/kazhuravlev/database-gateway) - Running SQL in production with ACLs, logs, and shared links.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [rwdb](https://github.com/andizzle/rwdb) - rwdb provides read replica capability for multiple database servers setup.
- [hasql](https://golang.yandex/hasql) - Library for accessing multi-host SQL database installations.

### SQL Query Builders

*Libraries for building and using SQL.*

- <code>&nbsp;15641</code> [sqlc](https://github.com/kyleconroy/sqlc) - Generate type-safe code from SQL.
- <code>&nbsp;&nbsp;7538</code> [Squirrel](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries.
- <code>&nbsp;&nbsp;3842</code> [xo](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.
- <code>&nbsp;&nbsp;3300</code> [jet](https://github.com/go-jet/jet) - Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure.
- <code>&nbsp;&nbsp;2546</code> [goqu](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library.
- <code>&nbsp;&nbsp;1636</code> [gendry](https://github.com/didi/gendry) - Non-invasive SQL builder and powerful data binder.
- <code>&nbsp;&nbsp;&nbsp;749</code> [Dotsql](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use them with ease.
- <code>&nbsp;&nbsp;&nbsp;655</code> [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities.
- <code>&nbsp;&nbsp;&nbsp;430</code> [sqlingo](https://github.com/lqs/sqlingo) - A lightweight DSL to build SQL in Go.
- <code>&nbsp;&nbsp;&nbsp;413</code> [dbq](https://github.com/rocketlaunchr/dbq) - Zero boilerplate database operations for Go.
- <code>&nbsp;&nbsp;&nbsp;281</code> [sqrl](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance.
- <code>&nbsp;&nbsp;&nbsp;201</code> [sq](https://github.com/bokwoon95/go-structured-query) - Type-safe SQL builder and struct mapper for Go.
- <code>&nbsp;&nbsp;&nbsp;181</code> [sqlf](https://github.com/leporo/sqlf) - Fast SQL query builder.
- <code>&nbsp;&nbsp;&nbsp;181</code> [buildsqlx](https://github.com/arthurkushman/buildsqlx) - Go database query builder library for PostgreSQL.
- <code>&nbsp;&nbsp;&nbsp;174</code> [bqb](https://github.com/nullism/bqb) - Lightweight and easy to learn query builder.
- <code>&nbsp;&nbsp;&nbsp;126</code> [igor](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;94</code> [builq](https://github.com/cristalhq/builq) - Easily build SQL queries in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> [godbal](https://github.com/xujiajun/godbal) - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> [gosql](https://github.com/twharmon/gosql) - SQL Query builder with better null values support.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [qry](https://github.com/HnH/qry) - Tool that generates constants from files with raw SQL queries.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> [Hotcoal](https://github.com/motrboat/hotcoal) - Secure your handcrafted SQL against injection.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [ormlite](https://github.com/pupizoid/ormlite) - Lightweight package containing some ORM-like features and helpers for sqlite databases.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [sg](https://github.com/go-the-way/sg) - A SQL Gen for generating standard SQLs(supports: CRUD) written in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> [patcher](https://github.com/Jacobbrewer1/patcher) - Powerful SQL Query builder that automatically generates SQL queries from structs.
- [Squalus](https://gitlab.com/qosenergy/squalus) - Thin layer over the Go SQL package that makes it easier to perform queries.

**[⬆ back to top](#contents)**

## Database Drivers

### Interfaces to Multiple Backends

- <code>&nbsp;14948</code> [cayley](https://github.com/google/cayley) - Graph database with support for multiple backends.
- <code>&nbsp;&nbsp;&nbsp;804</code> [gokv](https://github.com/philippgille/gokv) - Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more).
- <code>&nbsp;&nbsp;&nbsp;321</code> [go-transaction-manager](https://github.com/avito-tech/go-transaction-manager) - Transaction manager with multiple adapters (sql, sqlx, gorm, mongo, ...) controls transaction boundaries.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> [dsc](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> [dynamo](https://github.com/fogfish/dynamo) - A simple key-value abstraction to store algebraic and linked-data data types at AWS storage services: AWS DynamoDB and AWS S3.

### Relational Database Drivers

- <code>&nbsp;14963</code> [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go.
- <code>&nbsp;12241</code> [pgx](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql.
- <code>&nbsp;&nbsp;9562</code> [pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql.
- <code>&nbsp;&nbsp;8603</code> [go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that uses database/sql.
- <code>&nbsp;&nbsp;1858</code> [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go.
- <code>&nbsp;&nbsp;&nbsp;749</code> [go-sqlite3](https://github.com/ncruces/go-sqlite3) - This Go module is compatible with the database/sql driver. It allows embedding SQLite into your application, provides direct access to its C API, supports SQLite VFS, and also includes a GORM driver.
- <code>&nbsp;&nbsp;&nbsp;658</code> [sqlhooks](https://github.com/qustavo/sqlhooks) - Attach hooks to any database/sql driver.
- <code>&nbsp;&nbsp;&nbsp;635</code> [go-oci8](https://github.com/mattn/go-oci8) - Oracle driver for go that uses database/sql.
- <code>&nbsp;&nbsp;&nbsp;560</code> [godror](https://github.com/godror/godror) - Oracle driver for Go, using the ODPI-C driver.
- <code>&nbsp;&nbsp;&nbsp;452</code> [Sqinn-Go](https://github.com/cvilsmeier/sqinn-go) - SQLite with pure Go.
- <code>&nbsp;&nbsp;&nbsp;340</code> [KSQL](https://github.com/VinGarcia/ksql) - A Simple and Powerful Golang SQL Library
- <code>&nbsp;&nbsp;&nbsp;282</code> [surrealdb.go](https://github.com/surrealdb/surrealdb.go) - SurrealDB Driver for Go.
- <code>&nbsp;&nbsp;&nbsp;245</code> [firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go.
- <code>&nbsp;&nbsp;&nbsp;167</code> [ydb-go-sdk](https://github.com/ydb-platform/ydb-go-sdk) - native and database/sql driver YDB (Yandex Database)
- <code>&nbsp;&nbsp;&nbsp;167</code> [go-rqlite](https://github.com/rqlite/gorqlite) - A Go client for rqlite, providing easy-to-use abstractions for working with the rqlite API.
- <code>&nbsp;&nbsp;&nbsp;149</code> [go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that uses database/sql.
- <code>&nbsp;&nbsp;&nbsp;122</code> [avatica](https://github.com/apache/calcite-avatica-go) - Apache Avatica/Phoenix SQL driver for database/sql.
- <code>&nbsp;&nbsp;&nbsp;113</code> [gofreetds](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](https://www.freetds.org).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> [bgc](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [pig](https://github.com/alexeyco/pig) - Simple <code>&nbsp;12241</code> [pgx](https://github.com/jackc/pgx) wrapper to execute and <code>&nbsp;&nbsp;1450</code> [scan](https://github.com/georgysavva/scany) query results easily.
- [sqlite](https://pkg.go.dev/modernc.org/sqlite) - Package sqlite is a sql/database driver using a CGo-free port of the C SQLite3 library.

### NoSQL Database Drivers

- <code>&nbsp;21150</code> [redis](https://github.com/redis/go-redis) - Redis client for Golang.
- <code>&nbsp;&nbsp;9841</code> [redigo](https://github.com/gomodule/redigo) - Redigo is a Go client for the Redis database.
- <code>&nbsp;&nbsp;8415</code> [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - Official MongoDB driver for the Go language.
- <code>&nbsp;&nbsp;2739</code> [rueidis](http://github.com/rueian/rueidis) - Fast Redis RESP3 client with auto pipelining and server-assisted client side caching.
- <code>&nbsp;&nbsp;1969</code> [mgo](https://github.com/globalsign/mgo) - (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.
- <code>&nbsp;&nbsp;1826</code> [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language.
- <code>&nbsp;&nbsp;1653</code> [gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB.
- <code>&nbsp;&nbsp;1330</code> [qmgo](https://github.com/qiniu/qmgo) - The MongoDB driver for Go. It‘s based on official MongoDB driver but easier to use like Mgo.
- <code>&nbsp;&nbsp;&nbsp;762</code> [mgm](https://github.com/kamva/mgm) - MongoDB model-based ODM for Go (based on official MongoDB driver).
- <code>&nbsp;&nbsp;&nbsp;449</code> [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language.
- <code>&nbsp;&nbsp;&nbsp;446</code> [redeo](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services.
- <code>&nbsp;&nbsp;&nbsp;390</code> [neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang.
- <code>&nbsp;&nbsp;&nbsp;373</code> [gocb](https://github.com/couchbase/gocb) - Official Couchbase Go SDK.
- <code>&nbsp;&nbsp;&nbsp;343</code> [go-rejson](https://github.com/nitishm/go-rejson) - Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease.
- <code>&nbsp;&nbsp;&nbsp;325</code> [Kivik](https://github.com/go-kivik/kivik) - Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases.
- <code>&nbsp;&nbsp;&nbsp;323</code> [go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go.
- <code>&nbsp;&nbsp;&nbsp;202</code> [go-mongox](https://github.com/chenmingyong0423/go-mongox) - A Go Mongo library based on the official driver, featuring streamlined document operations, generic binding of structs to collections, built-in CRUD, aggregation, automated field updates, struct validation, hooks, and plugin-based programming.
- <code>&nbsp;&nbsp;&nbsp;113</code> [godis](https://github.com/piaohao/godis) - redis client implement by golang, inspired by jedis.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;72</code> [arangolite](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;57</code> [go-pilosa](https://github.com/pilosa/go-pilosa) - Go client library for Pilosa.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> [forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> [goriak](https://github.com/zegl/goriak) - Go language driver for Riak KV.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> [gocosmos](https://github.com/btnguyen2k/gocosmos) - REST client and standard `database/sql` driver for Azure Cosmos DB.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [gomemcached](https://github.com/aliexpressru/gomemcached) - A binary Memcached client for Go with support for sharding using consistent hashing, along with SASL.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> [xredis](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [godscache](https://github.com/defcronyke/godscache) - A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [asc](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go.
- [gocql](https://gocql.github.io) - Go language driver for Apache Cassandra.

### Search and Analytic Databases

- <code>&nbsp;&nbsp;7478</code> [elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go.
- <code>&nbsp;&nbsp;5926</code> [go-elasticsearch](https://github.com/elastic/go-elasticsearch) - Official Elasticsearch client for Go.
- <code>&nbsp;&nbsp;3108</code> [clickhouse-go](https://github.com/ClickHouse/clickhouse-go/) - ClickHouse SQL client for Go with a `database/sql` compatibility.
- <code>&nbsp;&nbsp;1192</code> [elasticsql](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go.
- <code>&nbsp;&nbsp;1028</code> [zoekt](https://github.com/sourcegraph/zoekt) - Fast trigram based code search.
- <code>&nbsp;&nbsp;&nbsp;941</code> [elastigo](https://github.com/mattbaird/elastigo) - Elasticsearch client library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;92</code> [skizze](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> [effdsl](https://github.com/sdqri/effdsl) - Elasticsearch query builder for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> [goes](https://github.com/OwnLocal/goes) - Library to interact with Elasticsearch.

**[⬆ back to top](#contents)**

## Date and Time

*Libraries for working with dates and times.*

- <code>&nbsp;&nbsp;5111</code> [carbon](https://github.com/dromara/carbon) - A simple, semantic and developer-friendly time package for golang.
- <code>&nbsp;&nbsp;4556</code> [now](https://github.com/jinzhu/now) - Now is a time toolkit for golang.
- <code>&nbsp;&nbsp;2096</code> [dateparse](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance.
- <code>&nbsp;&nbsp;&nbsp;783</code> [carbon](https://github.com/uniplaces/carbon) - Simple Time extension with a lot of util methods, ported from PHP Carbon library.
- <code>&nbsp;&nbsp;&nbsp;504</code> [durafmt](https://github.com/hako/durafmt) - Time duration formatting library for Go.
- <code>&nbsp;&nbsp;&nbsp;227</code> [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang).
- <code>&nbsp;&nbsp;&nbsp;210</code> [gostradamus](https://github.com/bykof/gostradamus) - A Go package for working with dates.
- <code>&nbsp;&nbsp;&nbsp;192</code> [timeutil](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package.
- <code>&nbsp;&nbsp;&nbsp;169</code> [go-sunrise](https://github.com/nathan-osman/go-sunrise) - Calculate the sunrise and sunset times for a given location.
- <code>&nbsp;&nbsp;&nbsp;151</code> [iso8601](https://github.com/relvacode/iso8601) - Efficiently parse ISO8601 date-times without regex.
- <code>&nbsp;&nbsp;&nbsp;140</code> [date](https://github.com/rickb777/date) - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day.
- <code>&nbsp;&nbsp;&nbsp;116</code> [go-str2duration](https://github.com/xhit/go-str2duration) - Convert string to duration. Support time.Duration returned string and more.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;83</code> [timespan](https://github.com/SaidinWoT/timespan) - For interacting with intervals of time, defined as a start time and a duration.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> [feiertage](https://github.com/wlbr/feiertage) - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving...
- <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> [go-anytime](https://github.com/ijt/go-anytime) - Parse dates/times like "next dec 22nd at 3pm" and ranges like "from today until next thursday" without knowing the format in advance.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> [kair](https://github.com/GuilhermeCaruso/kair) - Date and Time - Golang Formatting Library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [cronrange](https://github.com/1set/cronrange) - Parses Cron-style time range expressions, checks if the given time is within any ranges.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> [approx](https://github.com/goschtalt/approx) - A Duration extension supporting parsing/printing durations in days, weeks and years.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [strftime](https://github.com/awoodbeck/strftime) - C99-compatible strftime formatter.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> [tuesday](https://github.com/osteele/tuesday) - Ruby-compatible Strftime function.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [go-week](https://github.com/stoewer/go-week) - An efficient package to work with ISO8601 week dates.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> [go-datebin](https://github.com/deatil/go-datebin) - A simple datetime parse pkg.

**[⬆ back to top](#contents)**

## Distributed Systems

*Packages that help with building Distributed Systems.*

- <code>&nbsp;31549</code> [go-zero](https://github.com/tal-tech/go-zero) - A web and rpc framework. It's born to ensure the stability of the busy sites with resilient design. Builtin goctl greatly improves the development productivity.
- <code>&nbsp;27189</code> [go-kit](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.
- <code>&nbsp;24667</code> [Kratos](https://github.com/go-kratos/kratos) - A modular-designed and easy-to-use microservices framework in Go.
- <code>&nbsp;22425</code> [go-micro](https://github.com/micro/go-micro) - A distributed systems development framework.
- <code>&nbsp;22061</code> [grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC.
- <code>&nbsp;17619</code> [NATS](https://github.com/nats-io/nats-server) - NATS is a simple, secure, and performant communications system for digital systems, services, and devices.
- <code>&nbsp;12276</code> [micro](https://github.com/micro/micro) - A distributed systems runtime for the cloud and beyond.
- <code>&nbsp;&nbsp;8718</code> [raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp.
- <code>&nbsp;&nbsp;8234</code> [rpcx](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo.
- <code>&nbsp;&nbsp;7575</code> [Kitex](https://github.com/cloudwego/kitex) - A high-performance and strong-extensibility Golang RPC framework that helps developers build microservices. If the performance and extensibility are the main concerns when you develop microservices, Kitex can be a good choice.
- <code>&nbsp;&nbsp;6592</code> [lura](https://github.com/luraproject/lura) - Ultra performant API Gateway framework with middlewares.
- <code>&nbsp;&nbsp;5825</code> [torrent](https://github.com/anacrolix/torrent) - BitTorrent client package.
- <code>&nbsp;&nbsp;5206</code> [dragonboat](https://github.com/lni/dragonboat) - A feature complete and high performance multi-group Raft library in Go.
- <code>&nbsp;&nbsp;4410</code> [evans](https://github.com/ktr0731/evans) - Evans: more expressive universal gRPC client.
- <code>&nbsp;&nbsp;3961</code> [emitter-io](https://github.com/emitter-io/emitter) - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love.
- <code>&nbsp;&nbsp;3531</code> [gleam](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed.
- <code>&nbsp;&nbsp;3217</code> [glow](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go.
- <code>&nbsp;&nbsp;2685</code> [Dragonfly](https://github.com/dragonflyoss/Dragonfly2) - Provide efficient, stable and secure file distribution and image acceleration based on p2p technology to be the best practice and standard solution in cloud native architectures.
- <code>&nbsp;&nbsp;2611</code> [liftbridge](https://github.com/liftbridge-io/liftbridge) - Lightweight, fault-tolerant message streams for NATS.
- <code>&nbsp;&nbsp;2342</code> [go-eagle](https://github.com/go-eagle/eagle) - A Go framework for the API or Microservice with handy scaffolding tools.
- <code>&nbsp;&nbsp;2261</code> [sponge](https://github.com/zhufuyi/sponge) - A distributed development framework that integrates automatic code generation, gin and grpc frameworks, base development frameworks.
- <code>&nbsp;&nbsp;1653</code> [redis-lock](https://github.com/bsm/redislock) - Simplified distributed locking implementation using Redis.
- <code>&nbsp;&nbsp;1595</code> [mochi mqtt](https://github.com/mochi-co/mqtt) - Fully spec compliant, embeddable high-performance MQTT v5/v3 broker for IoT, smarthome, and pubsub.
- <code>&nbsp;&nbsp;1262</code> [hprose](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now.
- <code>&nbsp;&nbsp;1203</code> [go-doudou](https://github.com/unionj-cloud/go-doudou) - A gossip protocol and OpenAPI 3.0 spec based decentralized microservice framework. Built-in go-doudou cli focusing on low-code and rapid dev can power up your productivity.
- <code>&nbsp;&nbsp;1067</code> [arpc](https://github.com/lesismal/arpc) - More effective network communication, support two-way-calling, notify, broadcast.
- <code>&nbsp;&nbsp;1064</code> [K8gb](https://github.com/k8gb-io/k8gb) - A cloud native Kubernetes Global Balancer.
- <code>&nbsp;&nbsp;1057</code> [rain](https://github.com/cenkalti/rain) - BitTorrent client and library.
- <code>&nbsp;&nbsp;1002</code> [trpc-go](https://github.com/trpc-group/trpc-go) - The Go language implementation of tRPC, which is a pluggable, high-performance RPC framework.
- <code>&nbsp;&nbsp;&nbsp;885</code> [raft](https://github.com/etcd-io/raft) - Go implementation of the Raft consensus protocol, by CoreOS.
- <code>&nbsp;&nbsp;&nbsp;854</code> [ringpop-go](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications.
- <code>&nbsp;&nbsp;&nbsp;751</code> [go-health](https://github.com/InVisionApp/go-health) - Library for enabling asynchronous dependency health checks in your service.
- <code>&nbsp;&nbsp;&nbsp;741</code> [consistent](https://github.com/buraksezer/consistent) - Consistent hashing with bounded loads.
- <code>&nbsp;&nbsp;&nbsp;708</code> [gorpc](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load.
- <code>&nbsp;&nbsp;&nbsp;688</code> [Temporal](https://github.com/temporalio/sdk-go) - Durable execution system for making code fault-tolerant and simple.
- <code>&nbsp;&nbsp;&nbsp;639</code> [opentelemetry-go-auto-instrumentation](https://github.com/alibaba/opentelemetry-go-auto-instrumentation) - OpenTelemetry Compile-Time Instrumentation for Golang.
- <code>&nbsp;&nbsp;&nbsp;557</code> [go-sundheit](https://github.com/AppsFlyer/go-sundheit) - A library built to provide support for defining async service health checks for golang services.
- <code>&nbsp;&nbsp;&nbsp;516</code> [digota](https://github.com/digota/digota) - grpc ecommerce microservice.
- <code>&nbsp;&nbsp;&nbsp;387</code> [go-jump](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function.
- <code>&nbsp;&nbsp;&nbsp;381</code> [sleuth](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using <code>&nbsp;10405</code> [ZeroMQ](https://github.com/zeromq/libzmq)).
- <code>&nbsp;&nbsp;&nbsp;357</code> [jsonrpc](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation.
- <code>&nbsp;&nbsp;&nbsp;335</code> [Tarmac](https://github.com/tarmac-project/tarmac) - Framework for writing functions, microservices, or monoliths with WebAssembly
- <code>&nbsp;&nbsp;&nbsp;333</code> [dht](https://github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation.
- <code>&nbsp;&nbsp;&nbsp;189</code> [jsonrpc](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0.
- <code>&nbsp;&nbsp;&nbsp;163</code> [outboxer](https://github.com/italolelis/outboxer) - Outboxer is a go library that implements the outbox pattern.
- <code>&nbsp;&nbsp;&nbsp;107</code> [doublejump](https://github.com/edwingeng/doublejump) - A revamped Google's jump consistent hash.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;94</code> [Semaphore](https://github.com/jexia/semaphore) - A straightforward (micro) service orchestrator.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;86</code> [dot](https://github.com/dotchain/dot/) - distributed sync using operational transformation/OT.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;79</code> [outbox](https://github.com/oagudo/outbox) - Lightweight library for the transactional outbox pattern in Go, not tied to any specific relational database or broker.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;73</code> [celeriac](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> [capillaries](https://github.com/capillariesio/capillaries) - distributed batch data processing framework.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;64</code> [go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) - MySQL based distributed lock.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;63</code> [flowgraph](https://github.com/vectaport/flowgraph) - flow-based programming package.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> [drmaa](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> [go-pdu](https://github.com/pdupub/go-pdu) - A decentralized identity-based social network.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> [committer](https://github.com/vadiminshakov/committer) - A distributed transactions management system (2PC/3PC implementation).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> [consistenthash](https://github.com/mbrostami/consistenthash) - Consistent hashing with configurable replicas.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> [gmsec](https://github.com/gmsec/micro) - A Go distributed systems development framework.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [dynatomic](https://github.com/tylfin/dynatomic) - A library for using DynamoDB as an atomic counter.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> [failured](https://github.com/andy2046/failured) - adaptive accrual failure detector for distributed systems.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [bedrock](https://github.com/z5labs/bedrock) - Provides a minimal, modular and composable foundation for quickly developing services and more use case specific frameworks in Go.
- [pjrpc](https://gitlab.com/pjrpc/pjrpc) - Golang JSON-RPC Server-Client with Protobuf spec.
- [pglock](https://cirello.io/pglock) - PostgreSQL-backed distributed locking implementation.
- [resgate](https://resgate.io/) - Realtime API Gateway for building REST, real time, and RPC APIs, where all clients are synchronized seamlessly.
- [dynamolock](https://cirello.io/dynamolock) - DynamoDB-backed distributed locking implementation.

**[⬆ back to top](#contents)**

## Dynamic DNS

*Tools for updating dynamic DNS records.*

- <code>&nbsp;&nbsp;1600</code> [GoDNS](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go.
- <code>&nbsp;&nbsp;&nbsp;263</code> [DDNS](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend.
- [dyndns](https://gitlab.com/alcastle/dyndns) - Background Go process to regularly and automatically check your IP Address and make updates to (one or many) Dynamic DNS records for Google domains whenever your address changes.

**[⬆ back to top](#contents)**

## Email

*Libraries and tools that implement email creation and sending.*

- <code>&nbsp;15121</code> [MailHog](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface.
- <code>&nbsp;&nbsp;7435</code> [Mailpit](https://github.com/axllent/mailpit) - Email and SMTP testing tool for developers.
- <code>&nbsp;&nbsp;5621</code> [Maddy](https://github.com/foxcpp/maddy) - All-in-one (SMTP, IMAP, DKIM, DMARC, MTA-STS, DANE) email server
- <code>&nbsp;&nbsp;5121</code> [mox](https://github.com/mjl-/mox) - Modern full-featured secure mail server for low-maintenance, self-hosted email.
- <code>&nbsp;&nbsp;2909</code> [hermes](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails.
- <code>&nbsp;&nbsp;2748</code> [email](https://github.com/jordan-wright/email) - A robust and flexible email library for Go.
- <code>&nbsp;&nbsp;2215</code> [go-imap](https://github.com/emersion/go-imap) - IMAP library for clients and servers.
- <code>&nbsp;&nbsp;1419</code> [email-verifier](https://github.com/AfterShip/email-verifier) - A Go library for email verification without sending any emails.
- <code>&nbsp;&nbsp;1067</code> [go-mail](https://github.com/wneessen/go-mail) - A simple Go library for sending mails in Go.
- <code>&nbsp;&nbsp;1024</code> [SendGrid](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email.
- <code>&nbsp;&nbsp;&nbsp;732</code> [mailgun-go](https://github.com/mailgun/mailgun-go) - Go library for sending mail with the Mailgun API.
- <code>&nbsp;&nbsp;&nbsp;681</code> [go-simple-mail](https://github.com/xhit/go-simple-mail) - Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send.
- <code>&nbsp;&nbsp;&nbsp;420</code> [go-message](https://github.com/emersion/go-message) - Streaming library for the Internet Message Format and mail messages.
- <code>&nbsp;&nbsp;&nbsp;252</code> [douceur](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails.
- <code>&nbsp;&nbsp;&nbsp;224</code> [Hectane](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API.
- <code>&nbsp;&nbsp;&nbsp;171</code> [go-premailer](https://github.com/vanng822/go-premailer) - Inline styling for HTML mail in Go.
- <code>&nbsp;&nbsp;&nbsp;153</code> [smtpmock](https://github.com/mocktools/go-smtp-mock) - Lightweight configurable multithreaded fake SMTP server. Mimic any SMTP behaviour for your test environment.
- <code>&nbsp;&nbsp;&nbsp;143</code> [mailchain](https://github.com/mailchain/mailchain) - Send encrypted emails to blockchain addresses written in Go.
- <code>&nbsp;&nbsp;&nbsp;123</code> [truemail-go](https://github.com/truemail-rb/truemail-go) - Configurable Golang email validator/verifier. Verify email via Regex, DNS, SMTP and even more.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;97</code> [go-dkim](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;75</code> [smtp](https://github.com/mailhog/smtp) - SMTP server protocol state machine.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;72</code> [go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) - Golang library for providing a canonical representation of email address.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> [go-email-validator](https://github.com/go-email-validator/go-email-validator) - Modular email validator for syntax, disposable, smtp, etc... checking.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> [mailx](https://github.com/valord577/mailx) - Mailx is a library that makes it easier to send email via SMTP. It is an enhancement of the golang standard library `net/smtp`.
- [chasquid](https://blitiri.com.ar/p/chasquid) - SMTP server written in Go.

**[⬆ back to top](#contents)**

## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

- <code>&nbsp;&nbsp;9831</code> [FrankenPHP](https://github.com/dunglas/frankenphp) - PHP embedded in Go, with a `net/http` handler.
- <code>&nbsp;&nbsp;7071</code> [expr](https://github.com/antonmedv/expr) - Expression evaluation engine for Go: fast, non-Turing complete, dynamic typing, static typing.
- <code>&nbsp;&nbsp;6683</code> [gopher-lua](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go.
- <code>&nbsp;&nbsp;6320</code> [goja](https://github.com/dop251/goja) - ECMAScript 5.1(+) implementation in Go.
- <code>&nbsp;&nbsp;3678</code> [tengo](https://github.com/d5/tengo) - Bytecode compiled script language for Go.
- <code>&nbsp;&nbsp;3316</code> [go-lua](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go.
- <code>&nbsp;&nbsp;2626</code> [cel-go](https://github.com/google/cel-go) - Fast, portable, non-Turing complete expression evaluation with gradual typing.
- <code>&nbsp;&nbsp;2508</code> [starlark-go](https://github.com/google/starlark-go) - Go implementation of Starlark: Python-like language with deterministic evaluation and hermetic execution.
- <code>&nbsp;&nbsp;1673</code> [metacall](https://github.com/metacall/core) - Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, WebAssembly, Java, Cobol and more.
- <code>&nbsp;&nbsp;1599</code> [Wa/凹语言](https://github.com/wa-lang/wa) - The Wa Programming Language embedded in Go.
- <code>&nbsp;&nbsp;1534</code> [go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API.
- <code>&nbsp;&nbsp;1527</code> [anko](https://github.com/mattn/anko) - Scriptable interpreter written in Go.
- <code>&nbsp;&nbsp;&nbsp;943</code> [go-php](https://github.com/deuill/go-php) - PHP bindings for Go.
- <code>&nbsp;&nbsp;&nbsp;797</code> [gval](https://github.com/PaesslerAG/gval) - A highly customizable expression language written in Go.
- <code>&nbsp;&nbsp;&nbsp;778</code> [go-duktape](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go.
- <code>&nbsp;&nbsp;&nbsp;678</code> [prolog](https://github.com/ichiban/prolog) - Embeddable Prolog.
- <code>&nbsp;&nbsp;&nbsp;675</code> [golua](https://github.com/aarzilli/golua) - Go bindings for Lua C API.
- <code>&nbsp;&nbsp;&nbsp;525</code> [gisp](https://github.com/jcla1/gisp) - Simple LISP in Go.
- <code>&nbsp;&nbsp;&nbsp;139</code> [gentee](https://github.com/gentee/gentee) - Embeddable scripting programming language.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;79</code> [binder](https://github.com/alexeyco/binder) - Go to Lua binding library, based on <code>&nbsp;&nbsp;6683</code> [gopher-lua](https://github.com/yuin/gopher-lua).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> [ecal](https://github.com/krotik/ecal) - A simple embeddable scripting language which supports concurrent event processing.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> [purl](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> [starlet](https://github.com/1set/starlet) - Go wrapper for <code>&nbsp;&nbsp;2508</code> [starlark-go](https://github.com/google/starlark-go) that simplifies script execution, offers data conversion, and useful Starlark libraries and extensions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> [ngaro](https://github.com/db47h/ngaro) - Embeddable Ngaro VM implementation enabling scripting in Retro.
- [goal](https://codeberg.org/anaseto/goal) - An embeddable scripting array language.

**[⬆ back to top](#contents)**

## Error Handling

*Libraries for handling errors.*

- <code>&nbsp;&nbsp;2479</code> [go-multierror](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error.
- <code>&nbsp;&nbsp;2259</code> [errors](https://github.com/cockroachdb/errors) - Go error library with error portability over the network.
- <code>&nbsp;&nbsp;1694</code> [eris](https://github.com/rotisserie/eris) - A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors.
- <code>&nbsp;&nbsp;1257</code> [errorx](https://github.com/joomcode/errorx) - A feature rich error package with stack traces, composition of errors and more.
- <code>&nbsp;&nbsp;1148</code> [multierr](https://github.com/uber-go/multierr) - Package for representing a list of errors as a single error.
- <code>&nbsp;&nbsp;1093</code> [tracerr](https://github.com/ztrue/tracerr) - Golang errors with stack trace and source fragments.
- <code>&nbsp;&nbsp;&nbsp;716</code> [oops](https://github.com/samber/oops) - Error handling with context, stack trace and source fragments.
- <code>&nbsp;&nbsp;&nbsp;461</code> [errlog](https://github.com/snwfdhmp/errlog) - Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place.
- <code>&nbsp;&nbsp;&nbsp;359</code> [emperror](https://github.com/emperror/emperror) - Error handling tools and best practices for Go libraries and applications.
- <code>&nbsp;&nbsp;&nbsp;289</code> [Fault](https://github.com/Southclaws/fault) - An ergonomic mechanism for wrapping errors in order to facilitate structured metadata and context for error values.
- <code>&nbsp;&nbsp;&nbsp;201</code> [errors](https://github.com/emperror/errors) - Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;74</code> [errors](https://github.com/naughtygopher/errors) - Drop-in replacement for builtin Go errors. This is a minimal error handling package with custom error types, user friendly messages, Unwrap & Is. With very easy to use and straightforward helper functions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> [exception](https://github.com/rbrahul/exception) - A simple utility package for exception handling with try-catch in Golang.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [Falcon](https://github.com/SonicRoshan/falcon) - A Simple Yet Highly Powerful Package For Error Handling.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [errors](https://github.com/PumpkinSeed/errors) - The most simple error wrapper with awesome performance and minimal memory overhead.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> [errors](https://github.com/neuronlabs/errors) - Simple golang error handling with classification primitives.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> [metaerr](https://github.com/quantumcycle/metaerr) - A library to create your custom error builders producing structured errors with metadata from different sources and optional stacktraces.
- [errors](https://gitlab.com/tozd/go/errors) - Providing errors with a stack trace and optional structured details. Compatible with github.com/pkg/errors API but does not use it internally.

**[⬆ back to top](#contents)**

## File Handling

*Libraries for handling files and file systems.*

- <code>&nbsp;&nbsp;7848</code> [pdfcpu](https://github.com/pdfcpu/pdfcpu) - PDF processor.
- <code>&nbsp;&nbsp;6284</code> [afero](https://github.com/spf13/afero) - FileSystem Abstraction System for Go.
- <code>&nbsp;&nbsp;4653</code> [gdu](https://github.com/dundee/gdu) - Disk usage analyzer with console interface.
- <code>&nbsp;&nbsp;1134</code> [go-wkhtmltopdf](https://github.com/SebastiaanKlippert/go-wkhtmltopdf) - A package to convert an HTML template to a PDF file.
- <code>&nbsp;&nbsp;&nbsp;915</code> [notify](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal.
- <code>&nbsp;&nbsp;&nbsp;762</code> [copy](https://github.com/otiai10/copy) - Copy directory recursively.
- <code>&nbsp;&nbsp;&nbsp;514</code> [gofs](https://github.com/no-src/gofs) - A cross-platform real-time file synchronization tool out of the box.
- <code>&nbsp;&nbsp;&nbsp;348</code> [vfs](https://github.com/C2FO/vfs) - A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS.
- <code>&nbsp;&nbsp;&nbsp;337</code> [afs](https://github.com/viant/afs) - Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go.
- <code>&nbsp;&nbsp;&nbsp;276</code> [iso9660](https://github.com/kdomanski/iso9660) - A package for reading and creating ISO9660 disk images
- <code>&nbsp;&nbsp;&nbsp;270</code> [go-exiftool](https://github.com/barasher/go-exiftool) - Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...).
- <code>&nbsp;&nbsp;&nbsp;127</code> [go-csv-tag](https://github.com/artonge/go-csv-tag) - Load csv file using tag.
- <code>&nbsp;&nbsp;&nbsp;120</code> [parquet](https://github.com/parsyl/parquet) - Read and write [parquet](https://parquet.apache.org) files.
- <code>&nbsp;&nbsp;&nbsp;111</code> [checksum](https://github.com/codingsince1985/checksum) - Compute message digest, like MD5, SHA256, SHA1, CRC or BLAKE2s, for large files.
- <code>&nbsp;&nbsp;&nbsp;103</code> [skywalker](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease.
- <code>&nbsp;&nbsp;&nbsp;101</code> [fastwalk](https://github.com/charlievieth/fastwalk) - Fast parallel directory traversal library (used by <code>&nbsp;72477</code> [fzf](https://github.com/junegunn/fzf)).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;75</code> [opc](https://github.com/qmuntal/opc) - Load Open Packaging Conventions (OPC) files for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> [gulter](https://github.com/adelowo/gulter) - A simple HTTP middleware to automatically handle all your file upload needs
- <code>&nbsp;&nbsp;&nbsp;&nbsp;60</code> [baraka](https://github.com/xis/baraka) - A library to process http file uploads easily.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> [go-gtfs](https://github.com/artonge/go-gtfs) - Load gtfs files in go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [flop](https://github.com/homedepot/flop) - File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> [gut/yos](https://github.com/1set/gut) - Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> [todotxt](https://github.com/1set/todotxt) - Go library for Gina Trapani's [*todo.txt*](http://todotxt.org/) files, supports parsing and manipulating of task lists in the <code>&nbsp;&nbsp;2877</code> [*todo.txt* format](https://github.com/todotxt/todo.txt).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> [higgs](https://github.com/dastoori/higgs) - A tiny cross-platform Go library to hide/unhide files and directories.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) - Copy files for humans.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [pathtype](https://github.com/jonchun/pathtype) - Treat paths as their own type instead of using strings.

**[⬆ back to top](#contents)**

## Financial

*Packages for accounting and finance.*

- <code>&nbsp;&nbsp;6876</code> [decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers.
- <code>&nbsp;&nbsp;5363</code> [ticker](https://github.com/achannarasappa/ticker) - Terminal stock watcher and stock position tracker.
- <code>&nbsp;&nbsp;1783</code> [go-money](https://github.com/rhymond/go-money) - Implementation of Fowler's Money pattern.
- <code>&nbsp;&nbsp;1387</code> [bbgo](https://github.com/c9s/bbgo) - A crypto trading bot framework written in Go. Including common crypto exchange API, standard indicators, back-testing and many built-in strategies.
- <code>&nbsp;&nbsp;&nbsp;997</code> [ledger](https://github.com/formancehq/ledger) - A programmable financial ledger that provides a foundation for money-moving applications.
- <code>&nbsp;&nbsp;&nbsp;899</code> [accounting](https://github.com/leekchan/accounting) - money and currency formatting for golang.
- <code>&nbsp;&nbsp;&nbsp;868</code> [techan](https://github.com/sdcoffey/techan) - Technical analysis library with advanced market analysis and trading strategies.
- <code>&nbsp;&nbsp;&nbsp;597</code> [currency](https://github.com/bojanz/currency) - Handles currency amounts, provides currency information and formatting.
- <code>&nbsp;&nbsp;&nbsp;506</code> [orderbook](https://github.com/i25959341/orderbook) - Matching Engine for Limit Order Book in Golang.
- <code>&nbsp;&nbsp;&nbsp;499</code> [ach](https://github.com/moov-io/ach) - A reader, writer, and validator for Automated Clearing House (ACH) files.
- <code>&nbsp;&nbsp;&nbsp;186</code> [go-finance](https://github.com/alpeb/go-finance) - Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations.
- <code>&nbsp;&nbsp;&nbsp;179</code> [decimal](https://github.com/govalues/decimal) - Immutable decimal numbers with panic-free arithmetic.
- <code>&nbsp;&nbsp;&nbsp;149</code> [udecimal](https://github.com/quagmt/udecimal) - High performance, high precision, zero allocation fixed-point decimal library for financial applications.
- <code>&nbsp;&nbsp;&nbsp;144</code> [ofxgo](https://github.com/aclindsa/ofxgo) - Query OFX servers and/or parse the responses (with example command-line client).
- <code>&nbsp;&nbsp;&nbsp;140</code> [sleet](https://github.com/BoltApp/sleet) - One unified interface for multiple Payment Service Providers (PsP) to process online payment.
- <code>&nbsp;&nbsp;&nbsp;136</code> [transaction](https://github.com/claygod/transaction) - Embedded transactional database of accounts, running in multithreaded mode.
- <code>&nbsp;&nbsp;&nbsp;115</code> [vat](https://github.com/dannyvankooten/vat) - VAT number validation & EU VAT rates.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;94</code> [go-finnhub](https://github.com/m1/go-finnhub) - Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;88</code> [payme](https://github.com/jovandeginste/payme) - QR code generator (ASCII & PNG) for SEPA payments.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;62</code> [currency](https://github.com/naughtygopher/currency) - High performant & accurate currency computation package.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> [money](https://github.com/govalues/money) - Immutable monetary amounts and exchange rates with panic-free arithmetic.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> [fpmoney](https://github.com/nikolaydubina/fpmoney) - Fast and simple ISO4217 fixed-point decimal money.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;32</code> [fpdecimal](https://github.com/nikolaydubina/fpdecimal) - Fast and precise serialization and arithmetic for small fixed-point decimals
- <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> [go-finance](https://github.com/pieterclaerhout/go-finance) - Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> [go-nowpayments](https://github.com/matm/go-nowpayments) - Library for the crypto NOWPayments API.
- [swift](https://code.pfad.fr/swift/) - Offline validity check of IBAN (International Bank Account Number) and retrieval of BIC (for some countries).

**[⬆ back to top](#contents)**

## Forms

*Libraries for working with forms.*

- <code>&nbsp;&nbsp;1687</code> [nosurf](https://github.com/justinas/nosurf) - CSRF protection middleware for Go.
- <code>&nbsp;&nbsp;1134</code> [gorilla/csrf](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services.
- <code>&nbsp;&nbsp;&nbsp;855</code> [form](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support.
- <code>&nbsp;&nbsp;&nbsp;368</code> [httpin](https://github.com/ggicci/httpin) - Decode an HTTP request into a custom struct, including querystring, forms, HTTP headers, etc.
- <code>&nbsp;&nbsp;&nbsp;325</code> [conform](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags.
- <code>&nbsp;&nbsp;&nbsp;192</code> [formam](https://github.com/monoculum/formam) - decode form's values into a struct.
- <code>&nbsp;&nbsp;&nbsp;142</code> [forms](https://github.com/albrow/forms) - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;78</code> [qs](https://github.com/sonh/qs) - Go module for encoding structs into URL query parameters.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;44</code> [checker](https://github.com/cinar/checker) - Checker helps validating user input through rules defined in struct tags or directly through functions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;32</code> [bind](https://github.com/robfig/bind) - Bind form data to any Go values.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> [queryparam](https://github.com/tomwright/queryparam) - Decode `url.Values` into usable struct values of standard or custom types.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [gbind](https://github.com/bdjimmy/gbind) - Bind data to any Go value. Can use built-in and custom expression binding capabilities; supports data validation

**[⬆ back to top](#contents)**

## Functional

*Packages to support functional programming in Go.*

- <code>&nbsp;&nbsp;3043</code> [mo](https://github.com/samber/mo) - Monads and popular FP abstractions, based on Go 1.18+ Generics (Option, Result, Either...).
- <code>&nbsp;&nbsp;1302</code> [go-underscore](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities.
- <code>&nbsp;&nbsp;&nbsp;509</code> [go-functional](https://github.com/BooleanCat/go-functional) - Functional programming in Go using generics
- <code>&nbsp;&nbsp;&nbsp;351</code> [fpGo](https://github.com/TeaEntityLab/fpGo) - Monad, Functional Programming features for Golang.
- <code>&nbsp;&nbsp;&nbsp;315</code> [fp-go](https://github.com/repeale/fp-go) - Collection of Functional Programming helpers powered by Golang 1.18+ generics.
- <code>&nbsp;&nbsp;&nbsp;151</code> [gofp](https://github.com/rbrahul/gofp) - A lodash like powerful utility library for Golang.
- <code>&nbsp;&nbsp;&nbsp;146</code> [fuego](https://github.com/seborama/fuego) - Functional Experiment in Go.
- <code>&nbsp;&nbsp;&nbsp;117</code> [underscore](https://github.com/rjNemo/underscore) - Functional programming helpers for Go 1.18 and beyond.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> [valor](https://github.com/phelmkamp/valor) - Generic option and result types that optionally contain a value.

**[⬆ back to top](#contents)**

## Game Development

*Awesome game development libraries.*

- <code>&nbsp;12292</code> [Ebitengine](https://github.com/hajimehoshi/ebiten) - dead simple 2D game engine in Go.
- <code>&nbsp;&nbsp;5434</code> [Leaf](https://github.com/name5566/leaf) - Lightweight game server framework.
- <code>&nbsp;&nbsp;3068</code> [nano](https://github.com/lonng/nano) - Lightweight, facility, high performance golang based game server framework.
- <code>&nbsp;&nbsp;2977</code> [g3n](https://github.com/g3n/engine) - Go 3D Game Engine.
- <code>&nbsp;&nbsp;2659</code> [goworld](https://github.com/xiaonanln/goworld) - Scalable game server engine, featuring space-entity framework and hot-swapping.
- <code>&nbsp;&nbsp;2610</code> [Pitaya](https://github.com/topfreegames/pitaya) - Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK.
- <code>&nbsp;&nbsp;2306</code> [go-sdl2](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/).
- <code>&nbsp;&nbsp;2115</code> [raylib-go](https://github.com/gen2brain/raylib-go) - Go bindings for [raylib](https://www.raylib.com/), a simple and easy-to-use library to learn videogames programming.
- <code>&nbsp;&nbsp;1802</code> [engo](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm.
- <code>&nbsp;&nbsp;1632</code> [Oak](https://github.com/oakmound/oak) - Pure Go game engine.
- <code>&nbsp;&nbsp;1460</code> [termloop](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox.
- <code>&nbsp;&nbsp;1285</code> [gonet](https://github.com/xtaci/gonet) - Game server skeleton implemented with golang.
- <code>&nbsp;&nbsp;&nbsp;621</code> [Harfang3D](https://github.com/harfang3d/harfang3d) - 3D engine for the Go language, works on Windows and Linux (<code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> [Harfang on Go.dev](https://github.com/harfang3d/harfang-go)).
- <code>&nbsp;&nbsp;&nbsp;618</code> [go-astar](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm.
- <code>&nbsp;&nbsp;&nbsp;341</code> [Pixel](https://github.com/gopxl/pixel) - Hand-crafted 2D game library in Go.
- <code>&nbsp;&nbsp;&nbsp;325</code> [go3d](https://github.com/ungerik/go3d) - Performance oriented 2D/3D math package for Go.
- <code>&nbsp;&nbsp;&nbsp;198</code> [tile](https://github.com/kelindar/tile) - Data-oriented and cache-friendly 2D Grid library (TileMap), includes pathfinding, observers and import/export.
- <code>&nbsp;&nbsp;&nbsp;151</code> [ecs](https://github.com/andygeiss/ecs) - Build your own Game-Engine based on the Entity Component System concept in Golang.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;97</code> [Ark](https://github.com/mlange-42/ark) - Archetype-based Entity Component System (ECS) for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;92</code> [prototype](https://github.com/gonutz/prototype) - Cross-platform (Windows/Linux/Mac) library for creating desktop games using a minimal API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> [fantasyname](https://github.com/s0rg/fantasyname) - Fantasy names generator.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> [grid](https://github.com/s0rg/grid) - Generic 2D grid with ray-casting, shadow-casting and path finding.

**[⬆ back to top](#contents)**

## Generators

*Tools that generate Go code.*

- <code>&nbsp;&nbsp;7433</code> [oapi-codegen](https://github.com/deepmap/oapi-codegen) - This package contains a set of utilities for generating Go boilerplate code for services based on OpenAPI 3.0 API definitions.
- <code>&nbsp;&nbsp;3595</code> [go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go.
- <code>&nbsp;&nbsp;3529</code> [jennifer](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates.
- <code>&nbsp;&nbsp;1265</code> [goderive](https://github.com/awalterschulze/goderive) - Derives functions from input types
- <code>&nbsp;&nbsp;1240</code> [GoWrap](https://github.com/hexdigest/gowrap) - Generate decorators for Go interfaces using simple templates.
- <code>&nbsp;&nbsp;&nbsp;851</code> [go-enum](https://github.com/abice/go-enum) - Code generation for enums from code comments.
- <code>&nbsp;&nbsp;&nbsp;735</code> [goverter](https://github.com/jmattheis/goverter) - Generate converters by defining an interface.
- <code>&nbsp;&nbsp;&nbsp;431</code> [interfaces](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions.
- <code>&nbsp;&nbsp;&nbsp;396</code> [copygen](https://github.com/switchupcb/copygen) - Generate any code based on Go types, including type-to-type converters (copy code) without reflection by default.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> [convergen](https://github.com/reedom/convergen) - Feature rich type-to-type copy code generator.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> [generis](https://github.com/senselogic/GENERIS) - Code generation tool providing generics, free-form macros, conditional compilation and HTML templating.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> [typeregistry](https://github.com/xiaoxin01/typeregistry) - A library to create type dynamically.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> [go-enum-encoding](https://github.com/nikolaydubina/go-enum-encoding) - Code generation for enum encoding from code comments.

**[⬆ back to top](#contents)**

## Geographic

*Geographic tools and servers*

- <code>&nbsp;&nbsp;9426</code> [Tile38](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing.
- <code>&nbsp;&nbsp;1771</code> [S2 geometry](https://github.com/golang/geo) - S2 geometry library in Go.
- <code>&nbsp;&nbsp;&nbsp;740</code> [mbtileserver](https://github.com/consbio/mbtileserver) - A simple Go-based server for map tiles stored in mbtiles format.
- <code>&nbsp;&nbsp;&nbsp;524</code> [geoos](https://github.com/spatial-go/geoos) - A library provides spatial data and geometric algorithms.
- <code>&nbsp;&nbsp;&nbsp;414</code> [osm](https://github.com/paulmach/osm) - Library for reading, writing and working with OpenStreetMap data and APIs.
- <code>&nbsp;&nbsp;&nbsp;358</code> [H3](https://github.com/uber/h3-go) - Go bindings for H3, a hierarchical hexagonal geospatial indexing system.
- <code>&nbsp;&nbsp;&nbsp;168</code> [godal](https://github.com/airbusgeo/godal) - Go wrapper for GDAL.
- <code>&nbsp;&nbsp;&nbsp;150</code> [simplefeatures](https://github.com/peterstace/simplefeatures) - simplesfeatures is a 2D geometry library that provides Go types that model geometries, as well as algorithms that operate on them.
- <code>&nbsp;&nbsp;&nbsp;140</code> [WGS84](https://github.com/wroge/wgs84) - Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;93</code> [geoserver](https://github.com/hishamkaram/geoserver) - geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> [gismanager](https://github.com/hishamkaram/gismanager) - Publish Your GIS Data(Vector Data) to PostGIS and Geoserver.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> [pbf](https://github.com/maguro/pbf) - OpenStreetMap PBF golang encoder/decoder.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> [S2 geojson](https://github.com/pantrif/s2-geojson) - Convert geojson to s2 cells & demonstrating some S2 geometry features on map.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> [Web-Mercator-Projection](https://github.com/jorelosorio/web-mercator-projection) A project to easily use and convert LonLat, Point and Tile to display info, markers, etc, in a map using the Web Mercator Projection.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> [H3 GeoJSON](https://github.com/mmadfox/go-geojson2h3) - Conversion utilities between H3 indexes and GeoJSON.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> [H3GeoDist](https://github.com/mmadfox/go-h3geo-dist) - Distribution of Uber H3geo cells by virtual nodes.

**[⬆ back to top](#contents)**

## Go Compilers

*Tools for compiling Go to other languages and vice-versa.*

- <code>&nbsp;12996</code> [gopherjs](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript.
- <code>&nbsp;&nbsp;2456</code> [bunster](https://github.com/yassinebenaid/bunster) - Compile shell scripts to Go.
- <code>&nbsp;&nbsp;&nbsp;374</code> [c4go](https://github.com/Konstantin8105/c4go) - Transpile C code to Go code.
- <code>&nbsp;&nbsp;&nbsp;138</code> [go2hx](https://github.com/go2hx/go2hx) - Compiler from Go to Haxe to Javascript/C++/Java/C#.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;93</code> [esp32](https://github.com/andygeiss/esp32-transpiler) - Transpile Go into Arduino code.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> [f4go](https://github.com/Konstantin8105/f4go) - Transpile FORTRAN 77 code to Go code.

**[⬆ back to top](#contents)**

## Goroutines

*Tools for managing and working with Goroutines.*

- <code>&nbsp;13867</code> [ants](https://github.com/panjf2000/ants) - A high-performance and low-cost goroutine pool in Go.
- <code>&nbsp;10027</code> [conc](https://github.com/sourcegraph/conc) - `conc` is your toolbelt for structured concurrency in go, making common tasks easier and safer.
- <code>&nbsp;&nbsp;4004</code> [tunny](https://github.com/Jeffail/tunny) - Goroutine pool for golang.
- <code>&nbsp;&nbsp;2834</code> [goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker.
- <code>&nbsp;&nbsp;1915</code> [pond](https://github.com/alitto/pond) - Minimalistic and High-performance goroutine worker pool written in Go.
- <code>&nbsp;&nbsp;1689</code> [rill](https://github.com/destel/rill) - Go toolkit for clean, composable, channel-based concurrency.
- <code>&nbsp;&nbsp;1404</code> [workerpool](https://github.com/gammazero/workerpool) - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued.
- <code>&nbsp;&nbsp;&nbsp;744</code> [grpool](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool.
- <code>&nbsp;&nbsp;&nbsp;729</code> [pool](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation.
- <code>&nbsp;&nbsp;&nbsp;526</code> [gowp](https://github.com/xxjwxc/gowp) - gowp is concurrency limiting goroutine pool.
- <code>&nbsp;&nbsp;&nbsp;390</code> [flowmatic](https://github.com/carlmjohnson/flowmatic) - Structured concurrency made easy.
- <code>&nbsp;&nbsp;&nbsp;269</code> [routine](https://github.com/timandy/routine) - `routine` is a `ThreadLocal` for go library. It encapsulates and provides some easy-to-use, non-competitive, high-performance `goroutine` context access interfaces, which can help you access coroutine context information more gracefully.
- <code>&nbsp;&nbsp;&nbsp;268</code> [go-floc](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease.
- <code>&nbsp;&nbsp;&nbsp;253</code> [async](https://github.com/reugn/async) - An alternative sync library for Go (Future, Promise, Locks).
- <code>&nbsp;&nbsp;&nbsp;239</code> [go-actor](https://github.com/vladopajic/go-actor) - A tiny library for writing concurrent programs using actor model.
- <code>&nbsp;&nbsp;&nbsp;222</code> [go-flow](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order.
- <code>&nbsp;&nbsp;&nbsp;212</code> [artifex](https://github.com/borderstech/artifex) - Simple in-memory job queue for Golang using worker-based dispatching.
- <code>&nbsp;&nbsp;&nbsp;177</code> [semaphore](https://github.com/marusama/semaphore) - Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations).
- <code>&nbsp;&nbsp;&nbsp;166</code> [go-workers](https://github.com/catmullet/go-workers) - Easily and safely run workers for large data processing pipelines.
- <code>&nbsp;&nbsp;&nbsp;165</code> [neilotoole/errgroup](https://github.com/neilotoole/errgroup) - Drop-in alternative to `sync/errgroup`, limited to a pool of N worker goroutines.
- <code>&nbsp;&nbsp;&nbsp;153</code> [cyclicbarrier](https://github.com/marusama/cyclicbarrier) - CyclicBarrier for golang.
- <code>&nbsp;&nbsp;&nbsp;139</code> [async](https://github.com/studiosol/async) - A safe way to execute functions asynchronously, recovering them in case of panic.
- <code>&nbsp;&nbsp;&nbsp;123</code> [gollback](https://github.com/vardius/gollback) - asynchronous simple function utilities, for managing execution of closures and callbacks.
- <code>&nbsp;&nbsp;&nbsp;105</code> [Hunch](https://github.com/AaronJan/Hunch) - Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive.
- <code>&nbsp;&nbsp;&nbsp;104</code> [threadpool](https://github.com/shettyh/threadpool) - Golang threadpool implementation.
- <code>&nbsp;&nbsp;&nbsp;103</code> [semaphore](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;92</code> [worker-pool](https://github.com/vardius/worker-pool) - goworker is a Go simple async worker pool.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;90</code> [gpool](https://github.com/Sherifabdlnaby/gpool) - manages a resizeable pool of context-aware goroutines to bound concurrency.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;73</code> [goccm](https://github.com/zenthangplus/goccm) - Go Concurrency Manager package limits the number of goroutines that allowed to run concurrently.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;70</code> [gowl](https://github.com/hamed-yousefi/gowl) - Gowl is a process management and process monitoring tool at once. An infinite worker pool gives you the ability to control the pool and processes and monitor their status.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;69</code> [nursery](https://github.com/arunsworld/nursery) - Structured concurrency in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;62</code> [routine](https://github.com/x-mod/routine) - go routine control with context, support: Main, Go, Pool and some useful Executors.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> [gohive](https://github.com/loveleshsharma/gohive) - A highly performant and easy to use Goroutine pool for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> [kyoo](https://github.com/dirkaholic/kyoo) - Provides an unlimited job queue and concurrent worker pools.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) - Like `sync.WaitGroup` with error handling and concurrency control.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> [parallel-fn](https://github.com/rafaeljesus/parallel-fn) - Run functions in parallel.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> [go-trylock](https://github.com/subchen/go-trylock) - TryLock support on read-write lock for Golang.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> [channelify](https://github.com/ddelizia/channelify) - Transform your function to return channels for easy and powerful parallel processing.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> [stl](https://github.com/ssgreg/stl) - Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> [execpool](https://github.com/hexdigest/execpool) - A pool built around exec.Cmd that spins up a given number of processes in advance and attaches stdin and stdout to them when needed. Very similar to FastCGI or Apache Prefork MPM but works for any command.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [breaker](https://github.com/kamilsk/breaker) - Flexible mechanism to make execution flow interruptible.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> [concurrency-limiter](https://github.com/vivek-ng/concurrency-limiter) - Concurrency limiter with support for timeouts, dynamic priority and context cancellation of goroutines.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> [conexec](https://github.com/ITcathyh/conexec) - A concurrent toolkit to help execute funcs concurrently in an efficient and safe way. It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) - Manage a pool of goroutines using this lightweight library with a simple API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> [async](https://github.com/yaitoo/async) - An asynchronous task package with async/await style for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> [go-workerpool](https://github.com/zenthangplus/go-workerpool) - Inspired from Java Thread Pool, Go WorkerPool aims to control heavy Go Routines.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> [async-job](https://github.com/lab210-dev/async-job) - AsyncJob is an asynchronous queue job manager with light code, clear and speed.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [hands](https://github.com/duanckham/hands) - A process controller used to control the execution and return strategies of multiple goroutines.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> [go-accumulator](https://github.com/nar10z/go-accumulator) - Solution for accumulation of events and their subsequent processing.
- [oversight](https://pkg.go.dev/cirello.io/oversight) - Oversight is a complete implementation of the Erlang supervision trees.

**[⬆ back to top](#contents)**

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

- <code>&nbsp;26865</code> [fyne](https://github.com/fyne-io/fyne) - Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android.
- <code>&nbsp;13251</code> [webview](https://github.com/zserge/webview) - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux).
- <code>&nbsp;10697</code> [qt](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi).
- <code>&nbsp;&nbsp;8739</code> [app](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress.
- <code>&nbsp;&nbsp;8351</code> [ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform.
- <code>&nbsp;&nbsp;6994</code> [walk](https://github.com/lxn/walk) - Windows application library kit for Go.
- <code>&nbsp;&nbsp;5289</code> [DarwinKit](https://github.com/progrium/darwinkit) - Build native macOS applications using Go.
- <code>&nbsp;&nbsp;2603</code> [go-sciter](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform.
- <code>&nbsp;&nbsp;2177</code> [gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3.
- <code>&nbsp;&nbsp;2057</code> [Cogent Core](https://github.com/cogentcore/core) - A framework for building 2D and 3D apps that run on macOS, Windows, Linux, iOS, Android, and the web.
- <code>&nbsp;&nbsp;1231</code> [Spot](https://github.com/roblillack/spot) - Reactive, cross-platform desktop GUI toolkit.
- <code>&nbsp;&nbsp;&nbsp;504</code> [energy](https://github.com/energye/energy) - Cross-platform based on LCL(Native System UI Control Library) and CEF(Chromium Embedded Framework) (Windows/ macOS / Linux)
- <code>&nbsp;&nbsp;&nbsp;439</code> [gowd](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform.
- <code>&nbsp;&nbsp;&nbsp;434</code> [cimgui-go](https://github.com/AllenDang/cimgui-go) - Auto generated Go wrapper for <code>&nbsp;67277</code> [Dear ImGui](https://github.com/ocornut/imgui) via <code>&nbsp;&nbsp;1696</code> [cimgui](https://github.com/cimgui/cimgui).
- <code>&nbsp;&nbsp;&nbsp;281</code> [unison](https://github.com/richardwilkes/unison) - A unified graphical user experience toolkit for Go desktop applications. macOS, Windows, and Linux are supported.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [goradd/html5tag](https://github.com/goradd/html5tag) - Library for outputting HTML5 tags.
- [Goey](https://bitbucket.org/rj/goey/src/master/) - Cross platform UI toolkit aggregator for Windows / Linux / Mac. GTK, Cocoa, Windows API
- [go-gtk](https://mattn.github.io/go-gtk/) - Go bindings for GTK.
- [Wails](https://wails.io) - Mac, Windows, Linux desktop apps with HTML UI using built-in OS HTML renderer.
- [gio](https://gioui.org) - Gio is a library for writing cross-platform immediate mode GUI-s in Go. Gio supports all the major platforms: Linux, macOS, Windows, Android, iOS, FreeBSD, OpenBSD and WebAssembly.

*Interaction*

- <code>&nbsp;10289</code> [robotgo](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other.
- <code>&nbsp;&nbsp;3535</code> [systray](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area.
- <code>&nbsp;&nbsp;&nbsp;830</code> [zenity](https://github.com/ncruces/zenity) - Cross-platform Go library and CLI to create simple dialogs that interact graphically with the user.
- <code>&nbsp;&nbsp;&nbsp;589</code> [gosx-notifier](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go.
- <code>&nbsp;&nbsp;&nbsp;256</code> [trayhost](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) - OSX Sleep/Wake notifications in golang.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) - OSX library to notify about any (pluggable) activity on your machine.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> [AppIndicator Go](https://github.com/gopherlibs/appindicator) - Go bindings for libappindicator3 C library.

**[⬆ back to top](#contents)**

## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

- <code>&nbsp;&nbsp;4611</code> [arduino-cli](https://github.com/arduino/arduino-cli) - Official Arduino CLI and library. Can run standalone, or be incorporated into larger Go projects.
- <code>&nbsp;&nbsp;2250</code> [go-rpio](https://github.com/stianeikeland/go-rpio) - GPIO for Go, doesn't require cgo.
- <code>&nbsp;&nbsp;1769</code> [ghw](https://github.com/jaypipes/ghw) - Golang hardware discovery/inspection library.
- <code>&nbsp;&nbsp;1086</code> [emgo](https://github.com/ziutek/emgo) - Go-like language for programming embedded systems (e.g. STM32 MCU).
- <code>&nbsp;&nbsp;&nbsp;551</code> [sysinfo](https://github.com/zcalusic/sysinfo) - A pure Go library providing Linux OS / kernel / hardware system information.
- <code>&nbsp;&nbsp;&nbsp;367</code> [goroslib](https://github.com/aler9/goroslib) - Robot Operating System (ROS) library for Go.
- <code>&nbsp;&nbsp;&nbsp;215</code> [go-osc](https://github.com/hypebeast/go-osc) - Open Sound Control (OSC) bindings for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;69</code> [joystick](https://github.com/0xcafed00d/joystick) - a polled API to read the state of an attached joystick.

**[⬆ back to top](#contents)**

## Images

*Libraries for manipulating images.*

- <code>&nbsp;&nbsp;7168</code> [gocv](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3.3+.
- <code>&nbsp;&nbsp;5888</code> [imaginary](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing.
- <code>&nbsp;&nbsp;5547</code> [imaging](https://github.com/disintegration/imaging) - Simple Go image processing package.
- <code>&nbsp;&nbsp;4640</code> [gg](https://github.com/fogleman/gg) - 2D rendering in pure Go.
- <code>&nbsp;&nbsp;4125</code> [bild](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go.
- <code>&nbsp;&nbsp;3864</code> [gowitness](https://github.com/sensepost/gowitness) - Screenshoting webpages using go and headless chrome on command line.
- <code>&nbsp;&nbsp;3698</code> [imagor](https://github.com/cshum/imagor) - Fast, secure image processing server and Go library, using libvips.
- <code>&nbsp;&nbsp;3335</code> [ln](https://github.com/fogleman/ln) - 3D line art rendering in Go.
- <code>&nbsp;&nbsp;2892</code> [bimg](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips.
- <code>&nbsp;&nbsp;2264</code> [picfit](https://github.com/thoas/picfit) - An image resizing server written in Go.
- <code>&nbsp;&nbsp;2201</code> [svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation.
- <code>&nbsp;&nbsp;2086</code> [pt](https://github.com/fogleman/pt) - Path tracing engine written in Go.
- <code>&nbsp;&nbsp;1841</code> [smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes.
- <code>&nbsp;&nbsp;1826</code> [imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API.
- <code>&nbsp;&nbsp;1775</code> [gift](https://github.com/disintegration/gift) - Package of image processing filters.
- <code>&nbsp;&nbsp;1602</code> [canvas](https://github.com/tdewolff/canvas) - Vector graphics to PDF, SVG or rasterized image.
- <code>&nbsp;&nbsp;1471</code> [govips](https://github.com/davidbyttow/govips) - A lightning fast image processing and resizing library for Go.
- <code>&nbsp;&nbsp;1277</code> [geopattern](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string.
- <code>&nbsp;&nbsp;1244</code> [stegify](https://github.com/DimitarPetrov/stegify) - Go tool for LSB steganography, capable of hiding any file within an image.
- <code>&nbsp;&nbsp;&nbsp;929</code> [image2ascii](https://github.com/qeesung/image2ascii) - Convert image to ASCII.
- <code>&nbsp;&nbsp;&nbsp;809</code> [goimagehash](https://github.com/corona10/goimagehash) - Go Perceptual image hashing package.
- <code>&nbsp;&nbsp;&nbsp;737</code> [go-qrcode](https://github.com/yeqown/go-qrcode) - Generate QR codes with personalized styles, allowing adjustments to color, block size, shape, and icons.
- <code>&nbsp;&nbsp;&nbsp;607</code> [govatar](https://github.com/o1egl/govatar) - Library and CMD tool for generating funny avatars.
- <code>&nbsp;&nbsp;&nbsp;581</code> [draft](https://github.com/lucasepe/draft) - Generate High Level Microservice Architecture diagrams for GraphViz using simple YAML syntax.
- <code>&nbsp;&nbsp;&nbsp;514</code> [mort](https://github.com/aldor007/mort) - Storage and image processing server written in Go.
- <code>&nbsp;&nbsp;&nbsp;420</code> [go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go.
- <code>&nbsp;&nbsp;&nbsp;340</code> [steganography](https://github.com/auyer/steganography) - Pure Go Library for LSB steganography.
- <code>&nbsp;&nbsp;&nbsp;268</code> [go-webp](https://github.com/kolesa-team/go-webp) - Library for encode and decode webp pictures, using libwebp.
- <code>&nbsp;&nbsp;&nbsp;267</code> [transformimgs](https://github.com/Pixboost/transformimgs) - Transformimgs resizes and optimises images for Web using next-generation formats.
- <code>&nbsp;&nbsp;&nbsp;261</code> [gltf](https://github.com/qmuntal/gltf) - Efficient and robust glTF 2.0 reader, writer and validator.
- <code>&nbsp;&nbsp;&nbsp;241</code> [mergi](https://github.com/noelyahan/mergi) - Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate).
- <code>&nbsp;&nbsp;&nbsp;235</code> [darkroom](https://github.com/gojek/darkroom) - An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency.
- <code>&nbsp;&nbsp;&nbsp;212</code> [rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD.
- <code>&nbsp;&nbsp;&nbsp;156</code> [img](https://github.com/hawx/img) - Selection of image manipulation tools.
- <code>&nbsp;&nbsp;&nbsp;149</code> [go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library.
- <code>&nbsp;&nbsp;&nbsp;129</code> [cameron](https://github.com/aofei/cameron) - An avatar generator for Go.
- <code>&nbsp;&nbsp;&nbsp;100</code> [color-extractor](https://github.com/marekm4/color-extractor) - Dominant color extractor with no external dependencies.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;80</code> [gridder](https://github.com/shomali11/gridder) - A Grid based 2D Graphics library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;77</code> [webp-server](https://github.com/mehdipourfar/webp-server) - Simple and minimal image server capable of storing, resizing, converting and caching images.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> [go-gd](https://github.com/bolknote/go-gd) - Go binding for GD library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> [goimghdr](https://github.com/corona10/goimghdr) - The imghdr module determines the type of image contained in a file for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> [go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> [scout](https://github.com/jonoton/scout) - Scout is a standalone open source software solution for DIY video security.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> [mpo](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos.

**[⬆ back to top](#contents)**

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

- <code>&nbsp;&nbsp;9231</code> [gobot](https://github.com/hybridgroup/gobot/) - Gobot is a framework for robotics, physical computing, and the Internet of Things.
- <code>&nbsp;&nbsp;2477</code> [flogo](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration.
- <code>&nbsp;&nbsp;1618</code> [ekuiper](https://github.com/lf-edge/ekuiper) - Lightweight data stream processing engine for IoT edge.
- <code>&nbsp;&nbsp;1359</code> [shifu](https://github.com/Edgenesis/shifu) - Kubernetes native IoT development framework.
- <code>&nbsp;&nbsp;1218</code> [rulego](https://github.com/rulego/rulego) - RuleGo is a lightweight, high-performance, embedded, orchestrable component-based rule engine for IoT edge.
- <code>&nbsp;&nbsp;1162</code> [gatt](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals.
- <code>&nbsp;&nbsp;&nbsp;418</code> [connectordb](https://github.com/connectordb/connectordb) - Open-Source Platform for Quantified Self & IoT.
- <code>&nbsp;&nbsp;&nbsp;265</code> [devices](https://github.com/goiot/devices) - Suite of libraries for IoT devices, experimental for x/exp/io.
- <code>&nbsp;&nbsp;&nbsp;257</code> [huego](https://github.com/amimof/huego) - An extensive Philips Hue client library for Go.
- <code>&nbsp;&nbsp;&nbsp;231</code> [sensorbee](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;92</code> [smart-home](https://github.com/e154/smart-home) - Software package for IoT automation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;66</code> [iot](https://github.com/vaelen/iot/) - IoT is a simple framework for implementing a Google IoT Core device.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;65</code> [eywa](https://github.com/xcodersun/eywa) - Project Eywa is essentially a connection manager that keeps track of connected devices.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> [mainflux](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server.
- [periph](https://periph.io/) - Peripherals I/O to interface with low-level board facilities.

**[⬆ back to top](#contents)**

## Job Scheduler

*Libraries for scheduling jobs.*

- <code>&nbsp;&nbsp;6418</code> [gocron](https://github.com/go-co-op/gocron) - Easy and fluent Go job scheduling. This is an actively maintained fork of <code>&nbsp;&nbsp;3492</code> [jasonlvhit/gocron](https://github.com/jasonlvhit/gocron).
- <code>&nbsp;&nbsp;1929</code> [go-quartz](https://github.com/reugn/go-quartz) - Simple, zero-dependency scheduling library for Go.
- <code>&nbsp;&nbsp;1073</code> [JobRunner](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in.
- <code>&nbsp;&nbsp;1038</code> [gron](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.
- <code>&nbsp;&nbsp;&nbsp;470</code> [scheduler](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy.
- <code>&nbsp;&nbsp;&nbsp;459</code> [gronx](https://github.com/adhocore/gronx) - Cron expression parser, task runner and daemon consuming crontab like task list.
- <code>&nbsp;&nbsp;&nbsp;446</code> [goflow](https://github.com/fieldryand/goflow) - A simple but powerful DAG scheduler and dashboard.
- <code>&nbsp;&nbsp;&nbsp;316</code> [tasks](https://github.com/madflojo/tasks) - An easy to use in-process scheduler for recurring tasks in Go.
- <code>&nbsp;&nbsp;&nbsp;238</code> [go-cron](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.
- <code>&nbsp;&nbsp;&nbsp;195</code> [cheek](https://github.com/bart6114/cheek) - A simple crontab like scheduler that aims to offer a KISS approach to job scheduling.
- <code>&nbsp;&nbsp;&nbsp;181</code> [clockwerk](https://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax.
- <code>&nbsp;&nbsp;&nbsp;106</code> [leprechaun](https://github.com/kilgaloon/leprechaun) - Job scheduler that supports webhooks, crons and classic scheduling.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;56</code> [cdule](https://github.com/deepaksinghvi/cdule) - Job scheduler library with database support
- <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> [sched](https://github.com/romshark/sched) - A job scheduler with the ability to fast-forward time.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> [cronticker](https://github.com/krayzpipes/cronticker) - A ticker implementation to support cron schedules.

**[⬆ back to top](#contents)**

## JSON

*Libraries for working with JSON.*

- <code>&nbsp;15103</code> [GJSON](https://github.com/tidwall/gjson) - Get a JSON value with one line of code.
- <code>&nbsp;&nbsp;3513</code> [gabs](https://github.com/Jeffail/gabs) - For parsing, creating and editing unknown or dynamic JSON in Go.
- <code>&nbsp;&nbsp;2688</code> [gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON.
- <code>&nbsp;&nbsp;2389</code> [fastjson](https://github.com/valyala/fastjson) - Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection.
- <code>&nbsp;&nbsp;&nbsp;908</code> [OjG](https://github.com/ohler55/ojg) - Optimized JSON for Go is a high performance parser with a variety of additional JSON tools including JSONPath.
- <code>&nbsp;&nbsp;&nbsp;593</code> [jsondiff](https://github.com/wI2L/jsondiff) - JSON diff library for Go based on RFC6902 (JSON Patch).
- <code>&nbsp;&nbsp;&nbsp;386</code> [marshmallow](https://github.com/PerimeterX/marshmallow) - Performant JSON unmarshalling for flexible use cases.
- <code>&nbsp;&nbsp;&nbsp;286</code> [kazaam](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents.
- <code>&nbsp;&nbsp;&nbsp;277</code> [ajson](https://github.com/spyzhov/ajson) - Abstract JSON for golang with JSONPath support.
- <code>&nbsp;&nbsp;&nbsp;197</code> [jsonvalue](https://github.com/Andrew-M-C/go.jsonvalue) - A fast and convenient library for unstructured JSON data, replacing `encoding/json`.
- <code>&nbsp;&nbsp;&nbsp;189</code> [gojq](https://github.com/elgs/gojq) - JSON query in Golang.
- <code>&nbsp;&nbsp;&nbsp;178</code> [jettison](https://github.com/wI2L/jettison) - Fast and flexible JSON encoder for Go.
- <code>&nbsp;&nbsp;&nbsp;136</code> [json2go](https://github.com/m-zajac/json2go) - Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all.
- <code>&nbsp;&nbsp;&nbsp;130</code> [gjo](https://github.com/skanehira/gjo) - Small utility to create JSON objects.
- <code>&nbsp;&nbsp;&nbsp;109</code> [JayDiff](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go.
- <code>&nbsp;&nbsp;&nbsp;108</code> [jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;95</code> [jscan](https://github.com/romshark/jscan) - High performance zero-allocation JSON iterator.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;82</code> [ujson](https://github.com/olvrng/ujson) - Fast and minimal JSON parser and transformer that works on unstructured JSON.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;65</code> [jsonf](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> [go-respond](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> [ask](https://github.com/simonnilsson/ask) - Easy access to nested values in maps and slices. Works in combination with encoding/json and other packages that "Unmarshal" arbitrary data into Go data-types.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> [mp](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> [jsoncolor](https://github.com/neilotoole/jsoncolor) - Drop-in replacement for `encoding/json` that outputs colorized JSON.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> [vjson](https://github.com/miladibra10/vjson) - Go package for validating JSON objects with declaring a JSON schema with fluent API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> [gojmapr](https://github.com/limiu82214/gojmapr) - Get simple struct from complex json by json path.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [mapslice-json](https://github.com/mickep76/mapslice-json) - Go MapSlice for ordered marshal/ unmarshal of maps in JSON.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [go-jsonerror](https://github.com/ddymko/go-jsonerror) - Go-JsonError is meant to allow us to easily create json response errors that follow the JsonApi spec.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [dynjson](https://github.com/cocoonspace/dynjson) - Client-customizable JSON formats for dynamic APIs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [epoch](https://github.com/vtopc/epoch) - Contains primitives for marshaling/unmarshalling Unix timestamp/epoch to/from build-in time.Time type in JSON.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> [jsonhal](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [jsonic](https://github.com/sinhashubham95/jsonic) - Utilities to handle and query JSON without defining structs in a type safe manner.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [jzon](https://github.com/zerosnake0/jzon) - JSON library with standard compatible API/behavior.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [ej](https://github.com/lucassscaravelli/ej) - Write and read JSON from different sources succinctly.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> [htmljson](https://github.com/nikolaydubina/htmljson) - Rich rendering of JSON as HTML in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> [omg.jsonparser](https://github.com/dedalqq/omg.jsonparser) - Simple JSON parser with validation by condition via golang struct fields tags.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> [jsonhandlers](https://github.com/abusomani/jsonhandlers) - JSON library to expose simple handlers that lets you easily read and write json from various sources.
- [JSON-to-Proto](https://json-to-proto.github.io/) - Convert JSON to Protobuf online.
- [JSON-to-Go](https://mholt.github.io/json-to-go/) - Convert JSON to Go struct.

**[⬆ back to top](#contents)**

## Logging

*Libraries for generating and working with log files.*

- <code>&nbsp;25376</code> [logrus](https://github.com/Sirupsen/logrus) - Structured logger for Go.
- <code>&nbsp;23435</code> [zap](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go.
- <code>&nbsp;11675</code> [zerolog](https://github.com/rs/zerolog) - Zero-allocation JSON logger.
- <code>&nbsp;&nbsp;6286</code> [spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging.
- <code>&nbsp;&nbsp;5195</code> [lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser.
- <code>&nbsp;&nbsp;3604</code> [glog](https://github.com/golang/glog) - Leveled execution logs for Go.
- <code>&nbsp;&nbsp;2773</code> [tail](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program.
- <code>&nbsp;&nbsp;1976</code> [pp](https://github.com/k0kubun/pp) - Colored pretty printer for Go language.
- <code>&nbsp;&nbsp;1637</code> [seelog](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting.
- <code>&nbsp;&nbsp;1371</code> [log](https://github.com/apex/log) - Structured logging package for Go.
- <code>&nbsp;&nbsp;1098</code> [log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go.
- <code>&nbsp;&nbsp;1069</code> [tint](https://github.com/lmittmann/tint) - A slog.Handler that writes tinted logs.
- <code>&nbsp;&nbsp;&nbsp;980</code> [sentry-go](https://github.com/getsentry/sentry-go) - Sentry SDK for Go. Helps monitor and track errors with real-time alerts and performance monitoring.
- <code>&nbsp;&nbsp;&nbsp;785</code> [phuslu/log](https://github.com/phuslu/log) - High performance structured logging.
- <code>&nbsp;&nbsp;&nbsp;621</code> [lazyjournal](https://github.com/Lifailon/lazyjournal) - A TUI for reading and filtering logs from journalctl, file system, Docker and Podman containers, as well Kubernetes pods.
- <code>&nbsp;&nbsp;&nbsp;516</code> [slog-multi](https://github.com/samber/slog-multi) - Chain of slog.Handler (pipeline, fanout...).
- <code>&nbsp;&nbsp;&nbsp;487</code> [slog](https://github.com/gookit/slog) - Lightweight, configurable, extensible logger for Go.
- <code>&nbsp;&nbsp;&nbsp;411</code> [onelog](https://github.com/francoispqt/onelog) - Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenarios. Also, it is one of the logger with the lowest allocation.
- <code>&nbsp;&nbsp;&nbsp;408</code> [httpretty](https://github.com/henvic/httpretty) - Pretty-prints your regular HTTP requests on your terminal for debugging (similar to http.DumpRequest).
- <code>&nbsp;&nbsp;&nbsp;379</code> [sqldb-logger](https://github.com/simukti/sqldb-logger) - A logger for Go SQL database driver without modify existing \*sql.DB stdlib usage.
- <code>&nbsp;&nbsp;&nbsp;367</code> [logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger.
- <code>&nbsp;&nbsp;&nbsp;358</code> [logxi](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy.
- <code>&nbsp;&nbsp;&nbsp;298</code> [rollingwriter](https://github.com/arthurkiller/rollingWriter) - RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation.
- <code>&nbsp;&nbsp;&nbsp;295</code> [log](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go.
- <code>&nbsp;&nbsp;&nbsp;289</code> [go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers.
- <code>&nbsp;&nbsp;&nbsp;205</code> [logur](https://github.com/logur/logur) - An opinionated logger interface and collection of logging best practices with adapters and integrations for well-known libraries (<code>&nbsp;25376</code> [logrus](https://github.com/sirupsen/logrus), <code>&nbsp;27189</code> [go-kit log](https://github.com/go-kit/kit/tree/master/log), <code>&nbsp;23435</code> [zap](https://github.com/uber-go/zap), <code>&nbsp;11675</code> [zerolog](https://github.com/rs/zerolog), etc).
- <code>&nbsp;&nbsp;&nbsp;190</code> [glg](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go.
- <code>&nbsp;&nbsp;&nbsp;181</code> [slog-formatter](https://github.com/samber/slog-formatter) - Common formatters for slog and helpers to build your own.
- <code>&nbsp;&nbsp;&nbsp;156</code> [logger](https://github.com/azer/logger) - Minimalistic logging library for Go.
- <code>&nbsp;&nbsp;&nbsp;139</code> [xlog](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching.
- <code>&nbsp;&nbsp;&nbsp;123</code> [ozzo-log](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;57</code> [go-cronowriter](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> [gone/log](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> [stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;44</code> [noodlog](https://github.com/gyozatech/noodlog) - Parametrized JSON logging library which lets you obfuscate sensitive data and marshal any kind of content. No more printed pointers instead of values, nor escape chars for the JSON strings.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;43</code> [journald](https://github.com/ssgreg/journald) - Go implementation of systemd Journal's native API for logging.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;42</code> [go-log](https://github.com/ian-kent/go-log) - Log4j implementation in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;42</code> [logex](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> [mlog](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> [distillog](https://github.com/amoghe/distillog) - distilled levelled logging (think of it as stdlib + log levels).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> [logrusly](https://github.com/sebest/logrusly) - <code>&nbsp;25376</code> [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> [zkits-logger](https://github.com/edoger/zkits-logger) - A powerful zero-dependency JSON logger.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> [zax](https://github.com/yuseferi/zax) - Integrate Context with Zap logger, which leads to more flexibility in Go logging.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> [log](https://github.com/teris-io/log) - Structured log interface for Go cleanly separates logging facade from its implementation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [xylog](https://github.com/xybor-x/xylog) - Leveled and structured logging, dynamic fields, high performance, zone management, simple configuration, and readable syntax.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [log](https://github.com/heartwilltell/log) - Simple leveled logging wrapper around standard log package.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [kemba](https://github.com/clok/kemba) - A tiny debug logging tool inspired by <code>&nbsp;11307</code> [debug](https://github.com/visionmedia/debug), great for CLI tools and applications.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [logrusiowriter](https://github.com/cabify/logrusiowriter) - `io.Writer` implementation using <code>&nbsp;25376</code> [logrus](https://github.com/sirupsen/logrus) logger.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [glo](https://github.com/lajosbencz/glo) - PHP Monolog inspired logging facility with identical severity levels.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> [go-log](https://github.com/subchen/go-log) - Simple and configurable Logging in Go, with level, formatters and writers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> [logo](https://github.com/mbndr/logo) - Golang logger to different configurable writers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [go-log](https://github.com/pieterclaerhout/go-log) - A logging library with stack traces, object dumping and optional timestamps.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [logdump](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [log](https://github.com/aerogo/log) - An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> [xlog](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> [zl](https://github.com/nkmr-jp/zl) - High Developer Experience, zap based logger. It offers rich functionality but is easy to configure.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> [structy/log](https://github.com/structy/log) - A simple to use log system, minimalist but with features for debugging and differentiation of messages.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> [slf4g](https://github.com/echocat/slf4g) - Simple Logging Facade for Golang: Simple structured logging; but powerful, extendable and customizable, with huge amount of learnings from decades of past logging frameworks.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> [log](https://github.com/no-src/log) - A simple logging framework out of the box.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code> [yell](https://github.com/jfcg/yell) - Yet another minimalistic logging library.
- [slogor](https://gitlab.com/greyxor/slogor) - A colorful slog handler.

**[⬆ back to top](#contents)**

## Machine Learning

*Libraries for Machine Learning.*

- <code>&nbsp;&nbsp;9420</code> [GoLearn](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go.
- <code>&nbsp;&nbsp;5818</code> [gorgonia](https://github.com/gorgonia/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms.
- <code>&nbsp;&nbsp;2921</code> [gosseract](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library.
- <code>&nbsp;&nbsp;2898</code> [m2cgen](https://github.com/BayesWitnesses/m2cgen) - A CLI tool to transpile trained classic ML models into a native Go code with zero dependencies, written in Python with Go language support.
- <code>&nbsp;&nbsp;2479</code> [tfgo](https://github.com/galeone/tfgo) - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python.
- <code>&nbsp;&nbsp;1599</code> [goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go.
- <code>&nbsp;&nbsp;&nbsp;902</code> [eaopt](https://github.com/MaxHalford/eaopt) - An evolutionary optimization library.
- <code>&nbsp;&nbsp;&nbsp;854</code> [GoMLX](https://github.com/gomlx/gomlx) - An accelerated Machine Learning framework for Go.
- <code>&nbsp;&nbsp;&nbsp;815</code> [onnx-go](https://github.com/owulveryck/onnx-go) - Go Interface to Open Neural Network Exchange (ONNX).
- <code>&nbsp;&nbsp;&nbsp;810</code> [bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang.
- <code>&nbsp;&nbsp;&nbsp;744</code> [CloudForest](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go.
- <code>&nbsp;&nbsp;&nbsp;743</code> [ocrserver](https://github.com/otiai10/ocrserver) - A simple OCR API server, seriously easy to be deployed by Docker and Heroku.
- <code>&nbsp;&nbsp;&nbsp;567</code> [gobrain](https://github.com/goml/gobrain) - Neural Networks written in go.
- <code>&nbsp;&nbsp;&nbsp;554</code> [go-deep](https://github.com/patrikeh/go-deep) - A feature-rich neural network library in Go.
- <code>&nbsp;&nbsp;&nbsp;434</code> [hugot](https://github.com/knights-analytics/hugot) - Huggingface transformer pipelines for golang with onnxruntime.
- <code>&nbsp;&nbsp;&nbsp;313</code> [regommend](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine.
- <code>&nbsp;&nbsp;&nbsp;270</code> [Goptuna](https://github.com/c-bata/goptuna) - Bayesian optimization framework for black-box functions written in Go. Everything will be optimized.
- <code>&nbsp;&nbsp;&nbsp;224</code> [goga](https://github.com/tomcraven/goga) - Genetic algorithm library for Go.
- <code>&nbsp;&nbsp;&nbsp;206</code> [goRecommend](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go.
- <code>&nbsp;&nbsp;&nbsp;199</code> [go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang.
- <code>&nbsp;&nbsp;&nbsp;158</code> [shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go.
- <code>&nbsp;&nbsp;&nbsp;124</code> [go-featureprocessing](https://github.com/nikolaydubina/go-featureprocessing) - Fast and convenient feature processing for low latency machine learning in Go.
- <code>&nbsp;&nbsp;&nbsp;115</code> [go-fann](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library.
- <code>&nbsp;&nbsp;&nbsp;102</code> [goscore](https://github.com/asafschers/goscore) - Go Scoring API for PMML.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;98</code> [GoMind](https://github.com/surenderthakran/gomind) - A simplistic Neural Network Library in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;86</code> [fonet](https://github.com/Fontinalis/fonet) - A Deep Neural Network library written in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;83</code> [gonet](https://github.com/dathoangnd/gonet) - Neural Network for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;73</code> [libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;70</code> [neural-go](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> [go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;55</code> [Varis](https://github.com/Xamber/Varis) - Golang Neural Network.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> [randomforest](https://github.com/malaschitz/randomForest) - Easy to use Random Forest library for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> [golinear](https://github.com/danieldk/golinear) - liblinear bindings for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;44</code> [go-cluster](https://github.com/e-XpertSolutions/go-cluster) - Go implementation of the k-modes and k-prototypes clustering algorithms.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;43</code> [godist](https://github.com/e-dard/godist) - Various probability distributions, and associated methods.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> [ddt](https://github.com/sgrodriguez/ddt) - Dynamic decision tree, create trees defining customizable rules.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> [evoli](https://github.com/khezen/evoli) - Genetic Algorithm and Particle Swarm Optimization library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [probab](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [catboost-cgo](https://github.com/mirecl/catboost-cgo) - Fast, scalable, high performance Gradient Boosting on Decision Trees library. Golang using Cgo for blazing fast inference CatBoost Model.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> [gorse](https://github.com/zhenghaoz/gorse) - An offline recommender system backend based on collaborative filtering written in Go.

**[⬆ back to top](#contents)**

## Messaging

*Libraries that implement messaging systems.*

- <code>&nbsp;12129</code> [sarama](https://github.com/Shopify/sarama) - Go library for Apache Kafka.
- <code>&nbsp;11700</code> [Asynq](https://github.com/hibiken/asynq) - A simple, reliable, and efficient distributed task queue for Go built on top of Redis.
- <code>&nbsp;&nbsp;9183</code> [Centrifugo](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go.
- <code>&nbsp;&nbsp;8734</code> [Watermill](https://github.com/ThreeDotsLabs/watermill) - Working efficiently with message streams. Building event driven applications, enabling event sourcing, RPC over messages, sagas. Can use conventional pub/sub implementations like Kafka or RabbitMQ, but also HTTP or MySQL binlog.
- <code>&nbsp;&nbsp;8450</code> [gorush](https://github.com/appleboy/gorush) - Push notification server using <code>&nbsp;&nbsp;3107</code> [APNs2](https://github.com/sideshow/apns2) and google <code>&nbsp;&nbsp;&nbsp;105</code> [GCM](https://github.com/google/go-gcm).
- <code>&nbsp;&nbsp;7800</code> [machinery](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing.
- <code>&nbsp;&nbsp;6061</code> [NATS Go Client](https://github.com/nats-io/nats.go) - Go client for the NATS messaging system.
- <code>&nbsp;&nbsp;5782</code> [go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework.
- <code>&nbsp;&nbsp;5007</code> [Mercure](https://github.com/dunglas/mercure) - Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events).
- <code>&nbsp;&nbsp;4958</code> [Confluent Kafka Golang Client](https://github.com/confluentinc/confluent-kafka-go) - confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform.
- <code>&nbsp;&nbsp;3952</code> [melody](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling.
- <code>&nbsp;&nbsp;3107</code> [APNs2](https://github.com/sideshow/apns2) - HTTP/2 Apple Push Notification provider for Go - Send push notifications to iOS, tvOS, Safari and OSX apps.
- <code>&nbsp;&nbsp;2636</code> [go-nsq](https://github.com/nsqio/go-nsq) - the official Go package for NSQ.
- <code>&nbsp;&nbsp;2077</code> [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster.
- <code>&nbsp;&nbsp;1894</code> [EventBus](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility.
- <code>&nbsp;&nbsp;1825</code> [amqp](https://github.com/rabbitmq/amqp091-go) - Go RabbitMQ Client Library.
- <code>&nbsp;&nbsp;1574</code> [Beaver](https://github.com/Clivern/Beaver) - A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps.
- <code>&nbsp;&nbsp;1556</code> [Uniqush-Push](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices.
- <code>&nbsp;&nbsp;1306</code> [Chanify](https://github.com/chanify/chanify) - A push notification server send message to your iOS devices.
- <code>&nbsp;&nbsp;1216</code> [zmq4](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for <code>&nbsp;&nbsp;&nbsp;133</code> [version 3](https://github.com/pebbe/zmq3) and <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> [version 2](https://github.com/pebbe/zmq2).
- <code>&nbsp;&nbsp;1081</code> [dbus](https://github.com/godbus/dbus) - Native Go bindings for D-Bus.
- <code>&nbsp;&nbsp;&nbsp;941</code> [Gollum](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations.
- <code>&nbsp;&nbsp;&nbsp;716</code> [mangos](https://github.com/nanomsg/mangos) - Pure go implementation of the Nanomsg ("Scalability Protocols") with transport interoperability.
- <code>&nbsp;&nbsp;&nbsp;663</code> [golongpoll](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple.
- <code>&nbsp;&nbsp;&nbsp;524</code> [emitter](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins.
- <code>&nbsp;&nbsp;&nbsp;442</code> [pubsub](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go.
- <code>&nbsp;&nbsp;&nbsp;432</code> [Quamina](https://github.com/timbray/quamina) - Fast pattern-matching for filtering messages and events.
- <code>&nbsp;&nbsp;&nbsp;420</code> [Glue](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io).
- <code>&nbsp;&nbsp;&nbsp;349</code> [Bus](https://github.com/mustafaturan/bus) - Minimalist message bus implementation for internal communication.
- <code>&nbsp;&nbsp;&nbsp;278</code> [messagebus](https://github.com/vardius/message-bus) - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD.
- <code>&nbsp;&nbsp;&nbsp;271</code> [rabtap](https://github.com/jandelgado/rabtap) - RabbitMQ swiss army knife cli app.
- <code>&nbsp;&nbsp;&nbsp;249</code> [Go-MediatR](https://github.com/mehdihadeli/Go-MediatR) - A library for handling mediator patterns and simplified CQRS patterns within an event-driven architecture, inspired by csharp MediatR library.
- <code>&nbsp;&nbsp;&nbsp;160</code> [guble](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence.
- <code>&nbsp;&nbsp;&nbsp;147</code> [hub](https://github.com/leandro-lugaresi/hub) - A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges.
- <code>&nbsp;&nbsp;&nbsp;134</code> [redisqueue](https://github.com/robinjoseph08/redisqueue) - redisqueue provides a producer and consumer of a queue that uses Redis streams.
- <code>&nbsp;&nbsp;&nbsp;122</code> [Ratus](https://github.com/hyperonym/ratus) - Ratus is a RESTful asynchronous task queue server.
- <code>&nbsp;&nbsp;&nbsp;112</code> [rabbitroutine](https://github.com/furdarius/rabbitroutine) - Lightweight library that handles RabbitMQ auto-reconnect and publishing retries. The library takes into account the need to re-declare entities in RabbitMQ after reconnection.
- <code>&nbsp;&nbsp;&nbsp;110</code> [oplog](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs.
- <code>&nbsp;&nbsp;&nbsp;105</code> [backlite](https://github.com/mikestefanello/backlite) - Type-safe, persistent, embedded task queues and background job runner w/ SQLite.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;98</code> [rabbus](https://github.com/rafaeljesus/rabbus) - A tiny wrapper over amqp exchanges and queues.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;90</code> [go-mq](https://github.com/cheshir/go-mq) - RabbitMQ client with declarative configuration.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;80</code> [drone-line](https://github.com/appleboy/drone-line) - Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;80</code> [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;71</code> [go-notify](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;69</code> [RapidMQ](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> [Commander](https://github.com/jeroenrinzema/commander) - A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;66</code> [go-res](https://github.com/jirenius/go-res) - Package for building REST/real-time services where clients are synchronized seamlessly, using NATS and Resgate.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> [event](https://github.com/agoalofalife/event) - Implementation of the pattern observer.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> [hare](https://github.com/leozz37/hare) - A user friendly library for sending messages and listening to TCP sockets.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [GoEventBus](https://github.com/Raezil/GoEventBus) - A blazing‑fast, in‑memory, lock‑free event bus library
- <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> [ami](https://github.com/kak-tus/ami) - Go client to reliable queues based on Redis Cluster Streams.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> [hypermatch](https://github.com/SchwarzIT/hypermatch) - A very fast and efficient Go library for matching events to a large set of rules
- <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> [gosd](https://github.com/alexsniffin/gosd) - A library for scheduling when to dispatch a message to a channel.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> [go-vitotrol](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> [rmqconn](https://github.com/sbabiv/rmqconn) - RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> [jazz](https://github.com/socifi/jazz) - A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [gaurun-client](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> [go-eventbus](https://github.com/stanipetrosyan/go-eventbus) - Simple Event Bus package for Go.

**[⬆ back to top](#contents)**

## Microsoft Office

- <code>&nbsp;&nbsp;4636</code> [unioffice](https://github.com/unidoc/unioffice) - Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents.

### Microsoft Excel

*Libraries for working with Microsoft Excel.*

- <code>&nbsp;19448</code> [excelize](https://github.com/xuri/excelize) - Golang library for reading and writing Microsoft Excel&trade; (XLSX) files.
- <code>&nbsp;&nbsp;5991</code> [xlsx](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.
- <code>&nbsp;&nbsp;&nbsp;195</code> [go-excel](https://github.com/szyhf/go-excel) - A simple and light reader to read a relate-db-like excel as a table.
- <code>&nbsp;&nbsp;&nbsp;176</code> [xlsx](https://github.com/plandem/xlsx) - Fast and safe way to read/update your existing Microsoft Excel files in Go programs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;32</code> [exl](https://github.com/go-the-way/exl) - Excel binding to struct written in Go.(Only supports Go1.18+)
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files.

### Microsoft Word

*Libraries for working with Microsoft Word.*

- <code>&nbsp;&nbsp;&nbsp;196</code> [godocx](https://github.com/gomutex/godocx) - Library for reading and writing Microsoft Word (Docx) files.

**[⬆ back to top](#contents)**

## Miscellaneous

### Dependency Injection

*Libraries for working with dependency injection.*

- <code>&nbsp;14012</code> [google/wire](https://github.com/google/wire) - Automated Initialization in Go.
- <code>&nbsp;&nbsp;6714</code> [fx](https://github.com/uber-go/fx) - A dependency injection based application framework for Go (built on top of dig).
- <code>&nbsp;&nbsp;4238</code> [dig](https://github.com/uber-go/dig) - A reflection based dependency injection toolkit for Go.
- <code>&nbsp;&nbsp;2214</code> [do](https://github.com/samber/do) - A dependency injection framework based on Generics.
- <code>&nbsp;&nbsp;&nbsp;598</code> [GoLobby/Container](https://github.com/golobby/container) - GoLobby Container is a lightweight yet powerful IoC dependency injection container for the Go programming language.
- <code>&nbsp;&nbsp;&nbsp;367</code> [goioc/di](https://github.com/goioc/di) - Spring-inspired Dependency Injection Container.
- <code>&nbsp;&nbsp;&nbsp;238</code> [di](https://github.com/goava/di) - A dependency injection container for go programming language.
- <code>&nbsp;&nbsp;&nbsp;185</code> [kod](https://github.com/go-kod/kod) - A generics based dependency injection framework for Go.
- <code>&nbsp;&nbsp;&nbsp;185</code> [dingo](https://github.com/i-love-flamingo/dingo) - A dependency injection toolkit for Go, based on Guice.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> [alice](https://github.com/magic003/alice) - Additive dependency injection container for Golang.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> [gontainer](https://github.com/NVIDIA/gontainer) - A dependency injection service container for Go projects.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> [wire](https://github.com/Fs02/wire) - Strict Runtime Dependency Injection for Golang.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> [boot-go](http://github.com/boot-go/boot) - Component-based development with dependency injection using reflections for Go developers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [linker](https://github.com/logrange/linker) - A reflection based dependency injection and inversion of control library with components lifecycle support.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> [nject](https://github.com/muir/nject) - A type safe, reflective framework for libraries, tests, http endpoints, and service startup.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> [componego](https://github.com/componego/componego) - A dependency injection framework based on components, allowing dynamic dependency replacement without duplicating code in tests.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> [ore](https://github.com/firasdarwish/ore) - Lightweight, generic & simple dependency injection (DI) container.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> [gocontainer](https://github.com/vardius/gocontainer) - Simple Dependency Injection Container.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [gontainer/gontainer](https://github.com/gontainer/gontainer) - A YAML-based Dependency Injection container for GO. It supports dependencies' scopes, and auto-detection of circular dependencies. Gontainer is concurrent-safe.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [autowire](https://github.com/tiendc/autowire) - Dependency injection using Generics and reflection.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [kinit](https://github.com/go-kata/kinit) - Customizable dependency injection container with the global mode, cascade initialization and panic-safe finalization.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> [HnH/di](https://github.com/HnH/di) - DI container library that is focused on clean API and flexibility.
- [cosban/di](https://gitlab.com/cosban/di) - A code generation based dependency injection wiring tool.

**[⬆ back to top](#contents)**

### Project Layout

***Unofficial** set of patterns for structuring projects.*

- <code>&nbsp;53307</code> [golang-standards/project-layout](https://github.com/golang-standards/project-layout) - Set of common historical and emerging project layout patterns in the Go ecosystem. Note: despite the org-name they do not represent official golang standards, see <code>&nbsp;53307</code> [this issue](https://github.com/golang-standards/project-layout/issues/117) for more information. Nonetheless, some may find the layout useful.
- <code>&nbsp;&nbsp;7960</code> [go-blueprint](https://github.com/Melkeydev/go-blueprint) - Allows users to spin up a quick Go project using a popular framework.
- <code>&nbsp;&nbsp;3834</code> [ardanlabs/service](https://github.com/ardanlabs/service) - A <code>&nbsp;&nbsp;3834</code> [starter kit](https://github.com/ardanlabs/service/wiki) for building production grade scalable web service applications.
- <code>&nbsp;&nbsp;3591</code> [goxygen](https://github.com/shpota/goxygen) - Generate a modern Web project with Go and Angular, React, or Vue in seconds.
- <code>&nbsp;&nbsp;2776</code> [pagoda](https://github.com/mikestefanello/pagoda) - Rapid, easy full-stack web development starter kit built in Go.
- <code>&nbsp;&nbsp;2314</code> [nunu](https://github.com/go-nunu/nunu) - Nunu is a scaffolding tool for building Go applications.
- <code>&nbsp;&nbsp;1922</code> [modern-go-application](https://github.com/sagikazarmark/modern-go-application) - Go application boilerplate and example applying modern practices.
- <code>&nbsp;&nbsp;&nbsp;990</code> [goapp](https://github.com/naughtygopher/goapp) - An opinionated guideline to structure & develop a Go web application/service.
- <code>&nbsp;&nbsp;&nbsp;720</code> [cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) - A Go application boilerplate template for quick starting projects following production best practices.
- <code>&nbsp;&nbsp;&nbsp;569</code> [go-starter](https://github.com/allaboutapps/go-starter) - An opinionated production-ready RESTful JSON backend template, highly integrated with VSCode DevContainers.
- <code>&nbsp;&nbsp;&nbsp;534</code> [golang-templates/seed](https://github.com/golang-templates/seed) - Go application GitHub repository template.
- <code>&nbsp;&nbsp;&nbsp;331</code> [go-todo-backend](https://github.com/Fs02/go-todo-backend) - Go Todo Backend example using modular project layout for product microservice.
- <code>&nbsp;&nbsp;&nbsp;147</code> [scaffold](https://github.com/catchplay/scaffold) - Scaffold generates a starter Go project layout. Lets you focus on business logic implemented.
- <code>&nbsp;&nbsp;&nbsp;138</code> [go-sample](https://github.com/zitryss/go-sample) - A sample layout for Go application projects with the real code.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;86</code> [kickstart.go](https://github.com/raeperd/kickstart.go) - Minimalistic single-file Go HTTP server template without third-party dependencies.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;66</code> [gobase](https://github.com/wajox/gobase) - A simple skeleton for golang application with basic setup for real golang application.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [go-module](https://github.com/octomation/go-module) - Template for a typical module written on Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> [wangyoucao577/go-project-layout](https://github.com/wangyoucao577/go-project-layout) - Set of practices and discussions on how to structure Go project layout.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> [insidieux/inizio](https://github.com/insidieux/inizio) - Golang project layout generator with plugins.

**[⬆ back to top](#contents)**

### Strings

*Libraries for working with strings.*

- <code>&nbsp;&nbsp;1409</code> [xstrings](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages.
- <code>&nbsp;&nbsp;1151</code> [sttr](https://github.com/abhimanyu003/sttr) - cross-platform, cli app to perform various operations on string.
- <code>&nbsp;&nbsp;&nbsp;250</code> [gobeam/Stringy](https://github.com/gobeam/Stringy) - String manipulation library to convert string to camel case, snake case, kebab case / slugify etc.
- <code>&nbsp;&nbsp;&nbsp;207</code> [strutil](https://github.com/ozgio/strutil) - String utilities.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> [caps](https://github.com/chanced/caps) - A case conversion library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> [bexp](https://github.com/happy-sdk/happy/tree/main/pkg/strings/bexp) - Go implementation of Brace Expansion mechanism to generate arbitrary strings.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> [strcase](https://github.com/charlievieth/strcase) - Case-insensitive implementation of the standard library's strings/bytes packages.
- [go-formatter](https://gitlab.com/tymonx/go-formatter) - Implements **replacement fields** surrounded by curly braces `{}` format strings.

**[⬆ back to top](#contents)**

### Uncategorized

*These libraries were placed here because none of the other categories seemed to fit.*

- <code>&nbsp;11353</code> [gopsutil](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).
- <code>&nbsp;&nbsp;7889</code> [gatus](https://github.com/TwinProduction/gatus) - Automated service health dashboard.
- <code>&nbsp;&nbsp;5107</code> [gofakeit](https://github.com/brianvoe/gofakeit) - Random data generator written in go.
- <code>&nbsp;&nbsp;2302</code> [go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang.
- <code>&nbsp;&nbsp;2272</code> [base64Captcha](https://github.com/mojocn/base64Captcha) - Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha.
- <code>&nbsp;&nbsp;1468</code> [gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS.
- <code>&nbsp;&nbsp;1302</code> [shoutrrr](https://github.com/containrrr/shoutrrr) - Notification library providing easy access to various messaging services like slack, mattermost, gotify and smtp among others.
- <code>&nbsp;&nbsp;1241</code> [go-commons-pool](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang.
- <code>&nbsp;&nbsp;1234</code> [llvm](https://github.com/llir/llvm) - Library for interacting with LLVM IR in pure Go.
- <code>&nbsp;&nbsp;1085</code> [stateless](https://github.com/qmuntal/stateless) - A fluent library for creating state machines.
- <code>&nbsp;&nbsp;&nbsp;950</code> [shortid](https://github.com/teris-io/shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs.
- <code>&nbsp;&nbsp;&nbsp;814</code> [health](https://github.com/alexliesenfeld/health) - A simple and flexible health check library for Go.
- <code>&nbsp;&nbsp;&nbsp;519</code> [xz](https://github.com/ulikunitz/xz) - Pure golang package for reading and writing xz-compressed files.
- <code>&nbsp;&nbsp;&nbsp;457</code> [banner](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications.
- <code>&nbsp;&nbsp;&nbsp;450</code> [health](https://github.com/dimiro1/health) - Easy to use, extensible health check library.
- <code>&nbsp;&nbsp;&nbsp;419</code> [gountries](https://github.com/pariz/gountries) - Package that exposes country and subdivision data.
- <code>&nbsp;&nbsp;&nbsp;390</code> [lk](https://github.com/hyperboloide/lk) - A simple licensing library for golang.
- <code>&nbsp;&nbsp;&nbsp;381</code> [conv](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types.
- <code>&nbsp;&nbsp;&nbsp;312</code> [ffmt](https://github.com/go-ffmt/ffmt) - Beautify data display for Humans.
- <code>&nbsp;&nbsp;&nbsp;305</code> [gtree](https://github.com/ddddddO/gtree) - Provide CLI, Package and Web for tree output and directories creation from Markdown or programmatically.
- <code>&nbsp;&nbsp;&nbsp;297</code> [go-unarr](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives.
- <code>&nbsp;&nbsp;&nbsp;282</code> [archives](https://github.com/mholt/archives) - a cross-platform, multi-format Go library for working with archives and compression formats with a unified API and as virtual file systems compatible with io/fs.
- <code>&nbsp;&nbsp;&nbsp;274</code> [healthcheck](https://github.com/etherlabsio/healthcheck) - An opinionated and concurrent health-check HTTP handler for RESTful services.
- <code>&nbsp;&nbsp;&nbsp;263</code> [antch](https://github.com/antchfx/antch) - A fast, powerful and extensible web crawling & scraping framework.
- <code>&nbsp;&nbsp;&nbsp;262</code> [battery](https://github.com/distatus/battery) - Cross-platform, normalized battery information library.
- <code>&nbsp;&nbsp;&nbsp;250</code> [bitio](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go.
- <code>&nbsp;&nbsp;&nbsp;172</code> [stats](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...
- <code>&nbsp;&nbsp;&nbsp;166</code> [turtle](https://github.com/hackebrot/turtle) - Emojis for Go.
- <code>&nbsp;&nbsp;&nbsp;160</code> [captcha](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation.
- <code>&nbsp;&nbsp;&nbsp;115</code> [gommit](https://github.com/antham/gommit) - Analyze git commit messages to ensure they follow defined patterns.
- <code>&nbsp;&nbsp;&nbsp;111</code> [indigo](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58.
- <code>&nbsp;&nbsp;&nbsp;108</code> [gotoprom](https://github.com/cabify/gotoprom) - Type-safe metrics builder wrapper library for the official Prometheus client.
- <code>&nbsp;&nbsp;&nbsp;100</code> [faker](https://github.com/pioz/faker) - Random fake data and struct generator for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;91</code> [persian](https://github.com/mavihq/persian) - Some utilities for Persian language in go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> [morse](https://github.com/alwindoss/morse) - Library to convert to and from morse code.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;75</code> [pdfgen](https://github.com/hyperboloide/pdfgen) - HTTP service to generate PDF from Json requests.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;61</code> [xkg](https://github.com/go-xkg/xkg) - X Keyboard Grabber.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> [url-shortener](https://github.com/pantrif/url-shortener) - A modern, powerful, and robust URL shortener microservice with mysql support.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> [browscap_go](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](https://browscap.org/).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> [datacounter](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> [xdg](https://github.com/rkoesters/xdg) - FreeDesktop.org (xdg) Specs implemented in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> [sandid](https://github.com/aofei/sandid) - Every grain of sand on earth has its own ID.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;43</code> [autoflags](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [numa](https://github.com/lrita/numa) - NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [gosh](https://github.com/osamingo/gosh) - Provide Go Statistics Handler, Struct, Measure Method.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> [metrics](https://github.com/pascaldekloe/metrics) - Library for metrics instrumentation and Prometheus exposition.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> [shellwords](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [avgRating](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [anagent](https://github.com/mudler/anagent) - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> [varint](https://github.com/chmike/varint) - A faster varying length integer encoder/decoder than the one provided in the standard library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> [go-commandbus](https://github.com/lana/go-commandbus) - A slight and pluggable command-bus for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [hostutils](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking FQDNs list.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [openapi](https://github.com/neotoolkit/openapi) - OpenAPI 3.x parser.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> [sitemap-format](https://github.com/mingard/sitemap-format) - A simple sitemap generator, with a little syntactic sugar.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and output handling.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> [basexx](https://github.com/bobg/basexx) - Convert to, from, and between digit strings in various number bases.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> [common](https://github.com/kubeservice-stack/common) - A library for server framework.
- [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.

**[⬆ back to top](#contents)**

## Natural Language Processing

*Libraries for working with human languages.*

See also [Text Processing](#text-processing) and [Text Analysis](#text-analysis).

### Language Detection

- <code>&nbsp;&nbsp;1267</code> [lingua-go](https://github.com/pemistahl/lingua-go) - An accurate natural language detection library, suitable for long and short text alike. Supports detecting multiple languages in mixed-language text.
- <code>&nbsp;&nbsp;&nbsp;665</code> [whatlanggo](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc).
- <code>&nbsp;&nbsp;&nbsp;174</code> [getlang](https://github.com/rylans/getlang) - Fast natural language detection package.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;58</code> [guesslanguage](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> [detectlanguage](https://github.com/detectlanguage/detectlanguage-go) - Language Detection API Go Client. Supports batch requests, short phrase or single word language detection.

### Morphological Analyzers

- <code>&nbsp;&nbsp;1815</code> [spaGO](https://github.com/nlpodyssey/spago) - Self-contained Machine Learning and Natural Language Processing library in Go.
- <code>&nbsp;&nbsp;&nbsp;889</code> [kagome](https://github.com/ikawaha/kagome) - JP morphological analyzer written in pure Go.
- <code>&nbsp;&nbsp;&nbsp;459</code> [nlp](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis).
- <code>&nbsp;&nbsp;&nbsp;389</code> [nlp](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp.
- <code>&nbsp;&nbsp;&nbsp;120</code> [RAKE.go](https://github.com/afjoseph/RAKE.Go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;82</code> [go-stem](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;56</code> [go2vec](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> [govader](https://github.com/jonreiter/govader) - Go implementation of <code>&nbsp;&nbsp;4775</code> [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;46</code> [porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> [snowball](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> [paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> [porter](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [gosentiwordnet](https://github.com/dinopuguh/gosentiwordnet) - Sentiment analyzer using sentiwordnet lexicon in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> [govader-backend](https://github.com/PIMPfiction/govader_backend) - Microservice implementation of <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> [GoVader](https://github.com/jonreiter/govader).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> [spelling-corrector](https://github.com/jorelosorio/spellingcorrector) - A spelling corrector for the Spanish language or create your own.

### Slugifiers

- <code>&nbsp;&nbsp;1272</code> [slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;97</code> [go-slugify](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> [Slugify](https://github.com/avelino/slugify) - Go slugify application that handles string.

### Tokenizers

- <code>&nbsp;&nbsp;3069</code> [prose](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only.
- <code>&nbsp;&nbsp;2692</code> [gse](https://github.com/go-ego/gse) - Go efficient text segmentation; support english, chinese, japanese and other.
- <code>&nbsp;&nbsp;2551</code> [gojieba](https://github.com/yanyiwu/gojieba) - This is a Go implementation of <code>&nbsp;34296</code> [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm.
- <code>&nbsp;&nbsp;&nbsp;453</code> [sentences](https://github.com/neurosnap/sentences) - Sentence tokenizer: converts text into a list of sentences.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;89</code> [segment](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](https://www.unicode.org/reports/tr29/)
- <code>&nbsp;&nbsp;&nbsp;&nbsp;73</code> [textcat](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;62</code> [MMSEGO](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> [stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> [gotokenizer](https://github.com/xujiajun/gotokenizer) - A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation)
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [shamoji](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go.

### Translation

- <code>&nbsp;&nbsp;3304</code> [go-i18n](https://github.com/nicksnyder/go-i18n/) - Package and an accompanying tool to work with localized text.
- <code>&nbsp;&nbsp;1702</code> [go-pinyin](https://github.com/mozillazg/go-pinyin) - CN Hanzi to Hanyu Pinyin converter.
- <code>&nbsp;&nbsp;&nbsp;474</code> [gotext](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;74</code> [ctxi18n](https://github.com/invopop/ctxi18n/) - Context aware i18n with a short and consise API, pluralization, interpolation, and `fs.FS` support. YAML locale definitions are based on [Rails i18n](https://guides.rubyonrails.org/i18n.html).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;64</code> [spreak](https://github.com/vorlif/spreak) - Flexible translation and humanization library for Go, based on the concepts behind gettext.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> [iuliia-go](https://github.com/mehanizm/iuliia-go) - Transliterate Cyrillic → Latin in every possible way.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> [go-mystem](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [t](https://github.com/youthlin/t) - Another i18n pkg for golang, which follows GNU gettext style and supports .po/.mo files: `t.T (gettext)`, `t.N (ngettext)`, etc. And it contains a cmd tool <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [xtemplate](https://github.com/youthlin/t/blob/main/cmd/xtemplate), which can extract messages as a pot file from text/html template.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [go-words](https://github.com/saleh-rahimzadeh/go-words) - A words table and text resource library for Golang projects.

### Transliteration

- <code>&nbsp;&nbsp;&nbsp;141</code> [go-unidecode](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;80</code> [gounidecode](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;46</code> [transliterator](https://github.com/alexsergivan/transliterator) - Provides one-way string transliteration with supporting of language-specific transliteration rules.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> [enca](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](https://cihar.com/software/enca/), which detects character encodings.

**[⬆ back to top](#contents)**

## Networking

*Libraries for working with various layers of the network.*

- <code>&nbsp;22806</code> [fasthttp](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http.
- <code>&nbsp;15117</code> [webrtc](https://github.com/pions/webrtc) - A pure Go implementation of the WebRTC API.
- <code>&nbsp;14195</code> [kcptun](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol.
- <code>&nbsp;11162</code> [cloudflared](https://github.com/cloudflare/cloudflared) - Cloudflare Tunnel client (formerly Argo Tunnel).
- <code>&nbsp;10867</code> [quic-go](https://github.com/lucas-clemente/quic-go) - An implementation of the QUIC protocol in pure Go.
- <code>&nbsp;10686</code> [gnet](https://github.com/panjf2000/gnet) - `gnet` is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go.
- <code>&nbsp;&nbsp;8430</code> [dns](https://github.com/miekg/dns) - Go library for working with DNS.
- <code>&nbsp;&nbsp;6582</code> [gopacket](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings.
- <code>&nbsp;&nbsp;6436</code> [GoProxy](https://github.com/elazarl/goproxy) - A library to create a customized HTTP/HTTPS proxy server using Go.
- <code>&nbsp;&nbsp;4377</code> [netpoll](https://github.com/cloudwego/netpoll) - A high-performance non-blocking I/O networking framework, which focused on RPC scenarios, developed by ByteDance.
- <code>&nbsp;&nbsp;4295</code> [kcp-go](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol.
- <code>&nbsp;&nbsp;4078</code> [HTTPLab](https://github.com/gchaincl/httplab) - HTTPLabs let you inspect HTTP requests and forge responses.
- <code>&nbsp;&nbsp;4045</code> [tun2socks](https://github.com/xjasonlyu/tun2socks) - A pure go implementation of tun2socks powered by [gVisor](https://gvisor.dev/) TCP/IP stack.
- <code>&nbsp;&nbsp;3956</code> [ssh](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh).
- <code>&nbsp;&nbsp;3850</code> [gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language.
- <code>&nbsp;&nbsp;3574</code> [fortio](https://github.com/fortio/fortio) - Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC.
- <code>&nbsp;&nbsp;2550</code> [nbio](https://github.com/lesismal/nbio) - Pure Go 1000k+ connections solution, support tls/http1.x/websocket and basically compatible with net/http, with high-performance and low memory cost, non-blocking, event-driven, easy-to-use.
- <code>&nbsp;&nbsp;2062</code> [water](https://github.com/songgao/water) - Simple TUN/TAP library.
- <code>&nbsp;&nbsp;1759</code> [gev](https://github.com/Allenxuxu/gev) - gev is a lightweight, fast non-blocking TCP network library based on Reactor mode.
- <code>&nbsp;&nbsp;1715</code> [go-getter](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL.
- <code>&nbsp;&nbsp;1595</code> [sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt.
- <code>&nbsp;&nbsp;1582</code> [gws](https://github.com/lxzan/gws) - High-Performance WebSocket Server & Client With AsyncIO Supporting .
- <code>&nbsp;&nbsp;1452</code> [grab](https://github.com/cavaliercoder/grab) - Go package for managing file downloads.
- <code>&nbsp;&nbsp;1407</code> [NFF-Go](https://github.com/intel-go/nff-go) - Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF).
- <code>&nbsp;&nbsp;1360</code> [ftp](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](https://tools.ietf.org/html/rfc959).
- <code>&nbsp;&nbsp;1280</code> [mdns](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang.
- <code>&nbsp;&nbsp;1203</code> [gosnmp](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions.
- <code>&nbsp;&nbsp;1185</code> [nodepass](https://github.com/yosebyte/nodepass) - A secure, efficient TCP/UDP tunneling solution that delivers fast, reliable access across network restrictions using pre-established TLS/TCP connections.
- <code>&nbsp;&nbsp;1012</code> [gmqtt](https://github.com/DrmagicE/gmqtt) - Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1.
- <code>&nbsp;&nbsp;1001</code> [sdns](https://github.com/semihalev/sdns) - A high-performance, recursive DNS resolver server with DNSSEC support, focused on preserving privacy.
- <code>&nbsp;&nbsp;&nbsp;974</code> [vssh](https://github.com/yahoo/vssh) - Go library for building network and server automation over SSH protocol.
- <code>&nbsp;&nbsp;&nbsp;947</code> [cidranger](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup for Go.
- <code>&nbsp;&nbsp;&nbsp;823</code> [easytcp](https://github.com/DarthPestilane/easytcp) - A light-weight TCP framework written in Go (Golang), built with message router. EasyTCP helps you build a TCP server easily fast and less painful.
- <code>&nbsp;&nbsp;&nbsp;794</code> [gaio](https://github.com/xtaci/gaio) - High performance async-io networking for Golang in proactor mode.
- <code>&nbsp;&nbsp;&nbsp;710</code> [go-stun](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389).
- <code>&nbsp;&nbsp;&nbsp;690</code> [lhttp](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily.
- <code>&nbsp;&nbsp;&nbsp;660</code> [peerdiscovery](https://github.com/schollz/peerdiscovery) - Pure Go library for cross-platform local peer discovery using UDP multicast.
- <code>&nbsp;&nbsp;&nbsp;515</code> [gotcp](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications.
- <code>&nbsp;&nbsp;&nbsp;494</code> [stun](https://github.com/go-rtc/stun) - Go implementation of RFC 5389 STUN protocol.
- <code>&nbsp;&nbsp;&nbsp;492</code> [gopcap](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap.
- <code>&nbsp;&nbsp;&nbsp;453</code> [ftpserverlib](https://github.com/fclairamb/ftpserverlib) - Fully featured FTP server library.
- <code>&nbsp;&nbsp;&nbsp;446</code> [winrm](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines.
- <code>&nbsp;&nbsp;&nbsp;427</code> [raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface.
- <code>&nbsp;&nbsp;&nbsp;375</code> [arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826.
- <code>&nbsp;&nbsp;&nbsp;334</code> [dnsmonster](https://github.com/mosajjal/dnsmonster) - Passive DNS Capture/Monitoring Framework.
- <code>&nbsp;&nbsp;&nbsp;283</code> [ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshalling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags.
- <code>&nbsp;&nbsp;&nbsp;277</code> [gNxI](https://github.com/google/gnxi) - A collection of tools for Network Management that use the gNMI and gNOI protocols.
- <code>&nbsp;&nbsp;&nbsp;254</code> [buffstreams](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy.
- <code>&nbsp;&nbsp;&nbsp;222</code> [jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices.
- <code>&nbsp;&nbsp;&nbsp;178</code> [utp](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation.
- <code>&nbsp;&nbsp;&nbsp;171</code> [tcpack](https://github.com/lim-yoona/tcpack) - tcpack is an application protocol based on TCP to Pack and Unpack bytes stream in go program.
- <code>&nbsp;&nbsp;&nbsp;158</code> [xtcp](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication, graceful shutdown, and custom protocol.
- <code>&nbsp;&nbsp;&nbsp;156</code> [canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252).
- <code>&nbsp;&nbsp;&nbsp;153</code> [psql-wire](https://github.com/jeroenrinzema/psql-wire) - PostgreSQL server wire protocol. Build your own server and start serving connections..
- <code>&nbsp;&nbsp;&nbsp;151</code> [sslb](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance.
- <code>&nbsp;&nbsp;&nbsp;149</code> [iplib](https://github.com/c-robinson/iplib) - Library for working with IP addresses (net.IP, net.IPNet), inspired by python [ipaddress](https://docs.python.org/3/library/ipaddress.html) and ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html)
- <code>&nbsp;&nbsp;&nbsp;120</code> [event](https://github.com/cheng-zhongliang/event) - Simple I/O event notification library written in Golang.
- <code>&nbsp;&nbsp;&nbsp;116</code> [gldap](https://github.com/jimlambrt/gldap) - gldap provides an ldap server implementation and you provide handlers for its ldap operations.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;97</code> [natiu-mqtt](https://github.com/soypat/natiu-mqtt) - A dead-simple, non-allocating, low level implementation of MQTT well suited for embedded systems.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;97</code> [go-powerdns](https://github.com/joeig/go-powerdns) - PowerDNS API bindings for Golang.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;82</code> [fullproxy](https://github.com/shoriwe/fullproxy) - A fully featured scriptable and daemon configurable proxy and pivoting toolkit with SOCKS5, HTTP, raw ports and reverse proxy protocols.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;80</code> [ether](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;79</code> [dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;78</code> [bart](https://github.com/gaissmai/bart) - Package bart provides a fast routing table algorithm.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> [fwdctl](https://github.com/alegrey91/fwdctl) - A simple and intuitive CLI to manage IPTables forwards in your Linux server.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;58</code> [portproxy](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> [linkio](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> [httpproxy](https://github.com/wzshiming/httpproxy) - HTTP proxy handler and dialer.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> [publicip](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> [graval](https://github.com/koofr/graval) - Experimental FTP server framework.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> [gnet](https://github.com/fish-tennis/gnet) - `gnet` is a high-performance networking framework,especially for game servers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> [goshark](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [llb](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> [tspool](https://github.com/two/tspool) - A TCP Library use worker pool to improve performance and protect your server.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> [go-multiproxy](https://github.com/presbrey/go-multiproxy) - Library for making HTTP requests through a pool of proxies offering fault tolerance, load balancing, automatic retries, cookie management, and more, via http.Get/Post replacement or http.Client RoundTripper drop-in
- <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> [go-sse](https://github.com/lampctl/go-sse) - Go client and server implementation of HTML server-sent events.
- [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
- [net](https://golang.org/x/net) - This repository holds supplementary Go networking libraries.

**[⬆ back to top](#contents)**

### HTTP Clients

*Libraries for making HTTP requests.*

- <code>&nbsp;11104</code> [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.
- <code>&nbsp;&nbsp;4567</code> [req](https://github.com/imroc/req) - Simple Go HTTP client with Black Magic (Less code and More efficiency).
- <code>&nbsp;&nbsp;2689</code> [heimdall](https://github.com/gojektech/heimdall) - An enhanced http client with retry and hystrix capabilities.
- <code>&nbsp;&nbsp;2170</code> [go-retryablehttp](https://github.com/hashicorp/go-retryablehttp) - Retryable HTTP client in Go.
- <code>&nbsp;&nbsp;2163</code> [grequests](https://github.com/levigross/grequests) - A Go "clone" of the great and famous Requests library.
- <code>&nbsp;&nbsp;1708</code> [sling](https://github.com/dghubble/sling) - Sling is a Go HTTP client library for creating and sending API requests.
- <code>&nbsp;&nbsp;1623</code> [requests](https://github.com/carlmjohnson/requests) - HTTP requests for Gophers. Uses context.Context and doesn't hide the underlying net/http.Client, making it compatible with standard Go APIs. Also includes testing tools.
- <code>&nbsp;&nbsp;1212</code> [tls-client](https://github.com/bogdanfinn/tls-client) - net/http.Client like HTTP Client with options to select specific client TLS Fingerprints to use for requests.
- <code>&nbsp;&nbsp;1111</code> [gentleman](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library.
- <code>&nbsp;&nbsp;&nbsp;652</code> [pester](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency.
- <code>&nbsp;&nbsp;&nbsp;404</code> [go-cleanhttp](https://github.com/hashicorp/go-cleanhttp) - Get easily stdlib HTTP client, which does not share any state with other clients.
- <code>&nbsp;&nbsp;&nbsp;297</code> [azuretls-client](https://github.com/Noooste/azuretls-client) - An easy-to-use HTTP client 100% in Go to spoof TLS/JA3 and HTTP2 fingerprint
- <code>&nbsp;&nbsp;&nbsp;293</code> [request](https://github.com/monaco-io/request) - HTTP client for golang. If you have experience about axios or requests, you will love it. No 3rd dependency.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;87</code> [fast-shot](https://github.com/opus-domini/fast-shot) - Hit your API targets with rapid-fire precision using Go's fastest and simple HTTP Client.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> [go-otelroundtripper](https://github.com/NdoleStudio/go-otelroundtripper) - Go http.RoundTripper that emits open telemetry metrics for HTTP requests.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;83</code> [go-http-client](https://github.com/bozd4g/go-http-client) - Make http calls simply and easily.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;81</code> [go-zoox/fetch](https://github.com/go-zoox/fetch) - A Powerful, Lightweight, Easy Http Client, inspired by Web Fetch API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> [rq](https://github.com/ddo/rq) - A nicer interface for golang stdlib HTTP client.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;52</code> [httpretry](https://github.com/ybbus/httpretry) - Enriches the default go HTTP client with retry functionality.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> [axios4go](https://github.com/rezmoss/axios4go) - A Go HTTP client library inspired by Axios, providing a simple and intuitive API for making HTTP requests.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> [go-ipmux](https://github.com/optimus-hft/go-ipmux) - A library for Multiplexing HTTP requests based on multiple Source IPs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> [go-req](https://github.com/wenerme/go-req) - Declarative golang HTTP client.

**[⬆ back to top](#contents)**

## OpenGL

*Libraries for using OpenGL in Go.*

- <code>&nbsp;&nbsp;1630</code> [glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3.
- <code>&nbsp;&nbsp;1166</code> [gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow).
- <code>&nbsp;&nbsp;&nbsp;582</code> [mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM.
- <code>&nbsp;&nbsp;&nbsp;178</code> [goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;83</code> [goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [go-glmatrix](https://github.com/technohippy/go-glmatrix) - Go port of [glMatrix](https://glmatrix.net/) library.

**[⬆ back to top](#contents)**

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

- <code>&nbsp;38634</code> [GORM](https://github.com/go-gorm/gorm) - The fantastic ORM library for Golang, aims to be developer friendly.
- <code>&nbsp;16422</code> [ent](https://github.com/facebook/ent) - An entity framework for Go. Simple, yet powerful ORM for modeling and querying data.
- <code>&nbsp;&nbsp;6908</code> [SQLBoiler](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema.
- <code>&nbsp;&nbsp;4293</code> [bun](https://github.com/uptrace/bun) - SQL-first Golang ORM. Successor of go-pg.
- <code>&nbsp;&nbsp;3747</code> [gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go.
- <code>&nbsp;&nbsp;3611</code> [upper.io/db](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.
- <code>&nbsp;&nbsp;2411</code> [gormt](https://github.com/xxjwxc/gormt) - Mysql database to golang gorm struct.
- <code>&nbsp;&nbsp;2307</code> [Prisma](https://github.com/prisma/prisma-client-go) - Prisma Client Go, Typesafe database access for Go.
- <code>&nbsp;&nbsp;1577</code> [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) - A flexible and powerful SQL string builder library plus a zero-config ORM.
- <code>&nbsp;&nbsp;1494</code> [pop/soda](https://github.com/gobuffalo/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
- <code>&nbsp;&nbsp;1443</code> [reform](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation.
- <code>&nbsp;&nbsp;1385</code> [bob](https://github.com/stephenafamo/bob) - SQL query builder and ORM/Factory generator for Go. Successor of SQLBoiler.
- <code>&nbsp;&nbsp;&nbsp;783</code> [rel](https://github.com/go-rel/rel) - Modern Database Access Layer for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API.
- <code>&nbsp;&nbsp;&nbsp;313</code> [Zoom](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis.
- <code>&nbsp;&nbsp;&nbsp;180</code> [go-sql](https://github.com/rushteam/gosql) - A easy ORM for mysql.
- <code>&nbsp;&nbsp;&nbsp;163</code> [grimoire](https://github.com/Fs02/grimoire) - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3).
- <code>&nbsp;&nbsp;&nbsp;160</code> [golobby/orm](https://github.com/golobby/orm) - Simple, fast, type-safe, generic orm for developer happiness.
- <code>&nbsp;&nbsp;&nbsp;113</code> [go-store](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;52</code> [go-firestorm](https://github.com/jschoedt/go-firestorm) - A simple ORM for Google/Firebase Cloud Firestore.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> [cacheme](https://github.com/Yiling-J/cacheme-go) - Schema based, typed Redis caching/memoize framework for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [CQL](https://github.com/FrancoLiberali/cql) - Built on top of GORM, adds compile-time verified queries based on auto-generated code.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [go-dbw](https://github.com/hashicorp/go-dbw) - A simple package that encapsulates database operations.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> [lore](https://github.com/abrahambotros/lore) - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> [marlow](https://github.com/marlow/marlow) - Generated ORM from project structs for compile time safety assurances.
- [XORM](https://gitea.com/xorm/xorm) - Simple and powerful ORM for Go. (Support: MySQL, MyMysql, PostgreSQL, Tidb, SQLite3, MsSql and Oracle).

**[⬆ back to top](#contents)**

## Package Management

*Official tooling for dependency and package management*

- [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) - Modules are the unit of source code interchange and versioning. The go command has direct support for working with modules, including recording and resolving dependencies on other modules.

*Unofficial libraries for package and dependency management.*

- <code>&nbsp;&nbsp;8130</code> [glide](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip.
- <code>&nbsp;&nbsp;7415</code> [syft](https://github.com/anchore/syft) - A CLI tool and Go library for generating a Software Bill of Materials (SBOM) from container images and filesystems.
- <code>&nbsp;&nbsp;5528</code> [godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.
- <code>&nbsp;&nbsp;4921</code> [govendor](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file.
- <code>&nbsp;&nbsp;2460</code> [gopm](https://github.com/gpmgo/gopm) - Go Package Manager.
- <code>&nbsp;&nbsp;1183</code> [gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go.
- <code>&nbsp;&nbsp;&nbsp;775</code> [goop](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler.
- <code>&nbsp;&nbsp;&nbsp;493</code> [modgv](https://github.com/lucasepe/modgv) - Converts 'go mod graph' output into Graphviz's DOT language.
- <code>&nbsp;&nbsp;&nbsp;432</code> [gup](https://github.com/nao1215/gup) - Update binaries installed by "go install".
- <code>&nbsp;&nbsp;&nbsp;213</code> [johnny-deps](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git.
- <code>&nbsp;&nbsp;&nbsp;165</code> [mvn-golang](https://github.com/raydac/mvn-golang) - plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure.
- <code>&nbsp;&nbsp;&nbsp;126</code> [VenGO](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> [gop](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH.

**[⬆ back to top](#contents)**

## Performance

- <code>&nbsp;21674</code> [jaeger](https://github.com/jaegertracing/jaeger) - A distributed tracing system.
- <code>&nbsp;&nbsp;6108</code> [pixie](https://github.com/pixie-labs/pixie) - No instrumentation tracing for Golang applications via eBPF.
- <code>&nbsp;&nbsp;3352</code> [statsviz](https://github.com/arl/statsviz) - Live visualization of your Go application runtime statistics.
- <code>&nbsp;&nbsp;2033</code> [profile](https://github.com/pkg/profile) - Simple profiling support package for Go.
- <code>&nbsp;&nbsp;&nbsp;273</code> [go-instrument](https://github.com/nikolaydubina/go-instrument) - Automatically add spans to all methods and functions.
- <code>&nbsp;&nbsp;&nbsp;175</code> [mm-go](https://github.com/joetifa2003/mm-go) - Generic manual memory management for golang.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;89</code> [tracer](https://github.com/kamilsk/tracer) - Simple, lightweight tracing.

**[⬆ back to top](#contents)**

## Query Language

- <code>&nbsp;10422</code> [gqlgen](https://github.com/99designs/gqlgen) - go generate based graphql server library.
- <code>&nbsp;10087</code> [graphql-go](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go.
- <code>&nbsp;&nbsp;7515</code> [dasel](https://github.com/tomwright/dasel) - Query and update data structures using selectors from the command line. Comparable to jq/yq but supports JSON, YAML, TOML and XML with zero runtime dependencies.
- <code>&nbsp;&nbsp;4709</code> [graphql](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use.
- <code>&nbsp;&nbsp;2217</code> [gojsonq](https://github.com/thedevsaddam/gojsonq) - A simple Go package to Query over JSON Data.
- <code>&nbsp;&nbsp;&nbsp;359</code> [rql](https://github.com/a8m/rql) - Resource Query Language for REST API.
- <code>&nbsp;&nbsp;&nbsp;278</code> [jsonql](https://github.com/elgs/jsonql) - JSON query expression library in Golang.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;92</code> [jsonslice](https://github.com/bhmj/jsonslice) - Jsonpath queries with advanced filters.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> [rqp](https://github.com/timsolov/rest-query-parser) - Query Parser for REST API. Filtering, validations, both `AND`, `OR` operations are supported directly in the query.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;65</code> [mql](https://github.com/hashicorp/mql) - Model Query Language (mql) is a query language for your database models.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;62</code> [goven](https://github.com/SeldonIO/goven) - A drop-in query language for any database schema.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;57</code> [graphql](https://github.com/tmc/graphql) - graphql parser + utilities.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;57</code> [api-fu](https://github.com/ccbrown/api-fu) - Comprehensive GraphQL implementation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> [straf](https://github.com/SonicRoshan/straf) - Easily Convert Golang structs to GraphQL objects.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> [jsonpath](https://github.com/AsaiYusuke/jsonpath) - A query library for retrieving part of JSON based on JSONPath syntax.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> [gws](https://github.com/Zaba505/gws) - Apollos' "GraphQL over Websocket" client and server implementation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> [grapher](https://github.com/reaganiwadha/grapher) - A GraphQL field builder utilizing Go generics with extra utilities and features.

**[⬆ back to top](#contents)**

## Reflection

- <code>&nbsp;&nbsp;&nbsp;458</code> [Deepcopier](https://github.com/ulule/deepcopier) - Simple struct copying for Go.
- <code>&nbsp;&nbsp;&nbsp;101</code> [go-deepcopy](https://github.com/tiendc/go-deepcopy) - Fast deep copy library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;63</code> [gotype](https://github.com/wzshiming/gotype) - Golang source code parsing, usage like reflect package.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> [copy](https://github.com/gotidy/copy) - Package for fast copying structs of different types.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> [gpath](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [goenum](https://github.com/lvyahui8/goenum) - A common enumeration struct based on generics and reflection that allows you to quickly define enumerations and use a set of useful default methods.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> [reflectutils](https://github.com/muir/reflectutils) - Helpers for working with reflection: struct tag parsing; recursive walking; fill value from string.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [reflectpro](https://github.com/gontainer/reflectpro) - Callers, copiers, getters and setters for go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> [objwalker](https://github.com/rekby/objwalker) - Walk by go objects with reflection.

**[⬆ back to top](#contents)**

## Resource Embedding

- <code>&nbsp;&nbsp;&nbsp;982</code> [vfsgen](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> [debme](https://github.com/leaanthony/debme) - Create an `embed.FS` from an existing `embed.FS` subdirectory.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> [rebed](https://github.com/soypat/rebed) - Recreate folder structures and files from Go 1.16's `embed.FS` type
- [embed](https://pkg.go.dev/embed) - Package embed provides access to files embedded in the running Go program.

**[⬆ back to top](#contents)**

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

- <code>&nbsp;&nbsp;8109</code> [gonum](https://github.com/gonum/gonum) - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more.
- <code>&nbsp;&nbsp;2992</code> [stats](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library.
- <code>&nbsp;&nbsp;2882</code> [gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go.
- <code>&nbsp;&nbsp;1857</code> [gosl](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more.
- <code>&nbsp;&nbsp;1310</code> [streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data.
- <code>&nbsp;&nbsp;1258</code> [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) - Dataframes for machine-learning and statistics (similar to pandas).
- <code>&nbsp;&nbsp;1015</code> [orb](https://github.com/paulmach/orb) - 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support.
- <code>&nbsp;&nbsp;&nbsp;886</code> [go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go.
- <code>&nbsp;&nbsp;&nbsp;774</code> [chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types.
- <code>&nbsp;&nbsp;&nbsp;743</code> [goraph](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorithm visualization).
- <code>&nbsp;&nbsp;&nbsp;731</code> [graph](https://github.com/yourbasic/graph) - Library of basic graph algorithms.
- <code>&nbsp;&nbsp;&nbsp;709</code> [Poly](https://github.com/bebop/poly) - A Go package for engineering organisms.
- <code>&nbsp;&nbsp;&nbsp;448</code> [ewma](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages.
- <code>&nbsp;&nbsp;&nbsp;408</code> [calendarheatmap](https://github.com/nikolaydubina/calendarheatmap) - Calendar heatmap in plain Go inspired by Github contribution activity.
- <code>&nbsp;&nbsp;&nbsp;248</code> [go-hep](https://github.com/go-hep/hep) - A set of libraries and tools for performing High Energy Physics analyses with ease.
- <code>&nbsp;&nbsp;&nbsp;217</code> [TextRank](https://github.com/DavidBelicza/TextRank) - TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support.
- <code>&nbsp;&nbsp;&nbsp;165</code> [sparse](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries.
- <code>&nbsp;&nbsp;&nbsp;117</code> [go-estimate](https://github.com/milosgajdos/go-estimate) - State estimation and filtering algorithms in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;89</code> [gograph](https://github.com/hmdsefi/gograph) - A golang generic graph library that provides mathematical graph-theory and algorithms.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;86</code> [pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;75</code> [jsonl-graph](https://github.com/nikolaydubina/jsonl-graph) - Tool to manipulate JSONL graphs with graphviz support.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;55</code> [geom](https://github.com/skelterjohn/geom) - 2D geometry for golang.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> [evaler](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> [decimal](https://github.com/db47h/decimal) - Package decimal implements arbitrary-precision decimal floating-point arithmetic.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> [triangolatte](https://github.com/tchayen/triangolatte) - 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [goent](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> [piecewiselinear](https://github.com/sgreben/piecewiselinear) - Tiny linear interpolation library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> [godesim](https://github.com/soypat/godesim) - Extended/multivariable ODE solver framework for event-based simulations with simple API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> [GoStats](https://github.com/OGFris/GoStats) - GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> [ode](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [PiHex](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [assocentity](https://github.com/ndabAP/assocentity) - Package assocentity returns the average distance from words to a given entity.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> [topk](https://github.com/keilerkonzept/topk) - Sliding-window and regular top-K sketches, based on the HeavyKeeper algorithm.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [rootfinding](https://github.com/khezen/rootfinding) - root-finding algorithms library for finding roots of quadratic functions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [bradleyterry](https://github.com/seanhagen/bradleyterry) - Provides a Bradley-Terry Model for pairwise comparisons.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [go-gt](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language.

**[⬆ back to top](#contents)**

## Security

*Libraries that are used to help make your application more secure.*

- <code>&nbsp;19375</code> [age](https://github.com/FiloSottile/age) - A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability.
- <code>&nbsp;&nbsp;8764</code> [lego](https://github.com/go-acme/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt).
- <code>&nbsp;&nbsp;5293</code> [CertMagic](https://github.com/caddyserver/certmagic) - Mature, robust, and powerful ACME client integration for fully-managed TLS certificate issuance and renewal.
- <code>&nbsp;&nbsp;4622</code> [Cameradar](https://github.com/Ullaakut/cameradar) - Tool and library to remotely hack RTSP streams from surveillance cameras.
- <code>&nbsp;&nbsp;2795</code> [Coraza](https://github.com/corazawaf/coraza) - Enterprise-ready, modsecurity and OWASP CRS compatible WAF library.
- <code>&nbsp;&nbsp;2646</code> [memguard](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory.
- <code>&nbsp;&nbsp;2317</code> [secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins.
- <code>&nbsp;&nbsp;2080</code> [acmetool](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal.
- <code>&nbsp;&nbsp;1928</code> [themis](https://github.com/cossacklabs/themis) - high-level cryptographic library for solving typical data security tasks (secure data storage, secure messaging, zero-knowledge proof authentication), available for 14 languages, best fit for multi-platform apps.
- <code>&nbsp;&nbsp;1415</code> [acra](https://github.com/cossacklabs/acra) - Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system.
- <code>&nbsp;&nbsp;1341</code> [beelzebub](https://github.com/mariocandela/beelzebub) - A secure low code honeypot framework, leveraging AI for System Virtualization.
- <code>&nbsp;&nbsp;&nbsp;990</code> [dongle](https://github.com/golang-module/dongle) - A simple, semantic and developer-friendly golang package for encoding&decoding and encryption&decryption.
- <code>&nbsp;&nbsp;&nbsp;579</code> [booster](https://github.com/anatol/booster) - Fast initramfs generator with full-disk encryption support.
- <code>&nbsp;&nbsp;&nbsp;548</code> [nacl](https://github.com/kevinburke/nacl) - Go implementation of the NaCL set of API's.
- <code>&nbsp;&nbsp;&nbsp;541</code> [go-password-validator](https://github.com/lane-c-wagner/go-password-validator) - Password validator based on raw cryptographic entropy values.
- <code>&nbsp;&nbsp;&nbsp;473</code> [ssh-vault](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys.
- <code>&nbsp;&nbsp;&nbsp;383</code> [teler-waf](https://github.com/kitabisa/teler-waf) - teler-waf is a Go HTTP middleware that provide teler IDS functionality to protect against web-based attacks and improve the security of Go-based web applications. It is highly configurable and easy to integrate into existing Go applications.
- <code>&nbsp;&nbsp;&nbsp;375</code> [go-yara](https://github.com/hillu/go-yara) - Go Bindings for <code>&nbsp;&nbsp;&nbsp;139</code> [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)".
- <code>&nbsp;&nbsp;&nbsp;361</code> [optimus-go](https://github.com/pjebs/optimus-go) - ID hashing and Obfuscation using Knuth's Algorithm.
- <code>&nbsp;&nbsp;&nbsp;343</code> [firewalld-rest](https://github.com/prashantgupta24/firewalld-rest) - A rest application to dynamically update firewalld rules on a linux server.
- <code>&nbsp;&nbsp;&nbsp;324</code> [BadActor](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban.
- <code>&nbsp;&nbsp;&nbsp;295</code> [go-peer](https://github.com/number571/go-peer) - A software library for creating secure and anonymous decentralized systems.
- <code>&nbsp;&nbsp;&nbsp;293</code> [passlib](https://github.com/hlandau/passlib) - Futureproof password hashing library.
- <code>&nbsp;&nbsp;&nbsp;201</code> [simple-scrypt](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;91</code> [luks.go](https://github.com/anatol/luks.go) - Pure Golang library to manage LUKS partitions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;91</code> [argon2pw](https://github.com/raja/argon2pw) - Argon2 password hash generation with constant-time password comparison.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> [passwap](https://github.com/zitadel/passwap) - Provides a unified implementation between different password hashing algorithms
- <code>&nbsp;&nbsp;&nbsp;&nbsp;60</code> [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) - A probably paranoid package for securely hashing and encrypting passwords.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;55</code> [go-generate-password](https://github.com/m1/go-generate-password) - Password generator that can be used on the cli or as a library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;44</code> [go-htpasswd](https://github.com/tg123/go-htpasswd) - Apache htpasswd Parser for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> [certificates](https://github.com/mvmaasakkers/certificates) - An opinionated tool for generating tls certificates.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> [secureio](https://github.com/xaionaro-go/secureio) - An keyexchanging+authenticating+encrypting wrapper and multiplexer for `io.ReadWriteCloser` based on XChaCha20-poly1305, ECDH and ED25519.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> [secret](https://github.com/rsjethani/secret) - Prevent your secrets from leaking into logs, std\* etc.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> [sslmgr](https://github.com/adrianosela/sslmgr) - SSL certificates made easy with a high level wrapper around acme/autocert.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> [argon2-hashing](https://github.com/andskur/argon2-hashing) - light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [goArgonPass](https://github.com/dwin/goArgonPass) - Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [qrand](https://github.com/bitfield/qrand) - Client for the ANU Quantum Numbers (AQN) API, providing quantum-mechanically secure random data.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> [multikey](https://github.com/adrianosela/multikey) - An n-out-of-N keys encryption/decryption framework based on Shamir's Secret Sharing algorithm.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [Interpol](https://github.com/avahidi/interpol) - Rule-based data generator for fuzzing and penetration testing.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> [entpassgen](https://github.com/andreimerlescu/entpassgen) - Entropy Password Generator with extensive command line arguments to generate random strings securely including digits, passwords, and passwords built using obscure dictionary words mixed with symbols and digits.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> [encid](https://github.com/bobg/encid) - Encode and decode encrypted integer IDs.
- [autocert](https://pkg.go.dev/golang.org/x/crypto/acme/autocert) - Auto provision Let's Encrypt certificates and start a TLS server.
- [acopw-go](https://sr.ht/~jamesponddotco/acopw-go/) - Small cryptographically secure password generator package for Go.

**[⬆ back to top](#contents)**

## Serialization

*Libraries and tools for binary serialization.*

- <code>&nbsp;13842</code> [jsoniter](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json".
- <code>&nbsp;&nbsp;9988</code> [goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.
- <code>&nbsp;&nbsp;8012</code> [mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures.
- <code>&nbsp;&nbsp;5688</code> [gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets.
- <code>&nbsp;&nbsp;1904</code> [go-codec](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support.
- <code>&nbsp;&nbsp;1002</code> [csvutil](https://github.com/jszwec/csvutil) - High Performance, idiomatic CSV record encoding and decoding to native Go structures.
- <code>&nbsp;&nbsp;&nbsp;908</code> [cbor](https://github.com/fxamacker/cbor) - Small, safe, and easy CBOR encoding and decoding library.
- <code>&nbsp;&nbsp;&nbsp;750</code> [colfer](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format.
- <code>&nbsp;&nbsp;&nbsp;287</code> [go-capnproto](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go.
- <code>&nbsp;&nbsp;&nbsp;167</code> [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions.
- <code>&nbsp;&nbsp;&nbsp;144</code> [structomap](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures.
- <code>&nbsp;&nbsp;&nbsp;106</code> [binstruct](https://github.com/ghostiam/binstruct) - Golang binary decoder for mapping data into the structure.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;64</code> [bambam](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;44</code> [bel](https://github.com/32leaves/bel) - Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> [fwencoder](https://github.com/o1egl/fwencoder) - Fixed width file parser (encoding and decoding library) for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> [elastic](https://github.com/epiclabs-io/elastic) - Convert slices, maps or any other unknown value across different types at run-time, no matter what.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> [gotiny](https://github.com/raszia/gotiny) - Efficient Go serialization library, gotiny is almost as fast as serialization libraries that generate code.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> [go-csvlib](https://github.com/tiendc/go-csvlib) - High level and rich functionalities CSV serialization/deserialization library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> [pletter](https://github.com/vimeda/pletter) - A standard way to wrap a proto message for message brokers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> [fixedwidth](https://github.com/huydang284/fixedwidth) - Fixed-width text formatting (UTF-8 supported).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [unitpacking](https://github.com/recolude/unitpacking) - Library to pack unit vectors into as fewest bytes as possible.

**[⬆ back to top](#contents)**

## Server Applications

- <code>&nbsp;65910</code> [Caddy](https://github.com/caddyserver/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use.
- <code>&nbsp;54285</code> [minio](https://github.com/minio/minio) - Minio is a distributed object storage server.
- <code>&nbsp;49953</code> [etcd](https://github.com/etcd-io/etcd) - Highly-available key value store for shared configuration and service discovery.
- <code>&nbsp;49639</code> [pocketbase](https://github.com/pocketbase/pocketbase) - PocketBase is a realtime backend in 1 file consisting of embedded database (SQLite) with realtime subscriptions, built-in auth management and much more.
- <code>&nbsp;10793</code> [SFTPGo](https://github.com/drakkan/sftpgo) - Fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. It can serve local filesystem and Cloud Storage backends such as S3 and Google Cloud Storage.
- <code>&nbsp;&nbsp;8207</code> [RoadRunner](https://github.com/spiral/roadrunner) - High-performance PHP application server, load-balancer and process manager.
- <code>&nbsp;&nbsp;5838</code> [Easegress](https://github.com/megaease/easegress) - A cloud native high availability/performance traffic orchestration system with observability and extensibility.
- <code>&nbsp;&nbsp;4471</code> [flipt](https://github.com/markphelps/flipt) - A self contained feature flag solution written in Go and Vue.js
- <code>&nbsp;&nbsp;4259</code> [Wish](https://github.com/charmbracelet/wish) - Make SSH apps, just like that!
- <code>&nbsp;&nbsp;3678</code> [Fider](https://github.com/getfider/fider) - Fider is an open platform to collect and organize customer feedback.
- <code>&nbsp;&nbsp;3461</code> [devd](https://github.com/cortesi/devd) - Local webserver for developers.
- <code>&nbsp;&nbsp;2927</code> [algernon](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber.
- <code>&nbsp;&nbsp;2514</code> [Flagr](https://github.com/checkr/flagr) - Flagr is an open-source feature flagging and A/B testing service.
- <code>&nbsp;&nbsp;2041</code> [Trickster](https://github.com/tricksterproxy/trickster) - HTTP reverse proxy cache and time series accelerator.
- <code>&nbsp;&nbsp;1798</code> [discovery](https://github.com/Bilibili/discovery) - A registry for resilient mid-tier load balancing and failover.
- <code>&nbsp;&nbsp;1706</code> [go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) - A simple, complete and lightweight self-hosted feature flag solution 100% Open Source.
- <code>&nbsp;&nbsp;&nbsp;645</code> [Clace](https://github.com/claceio/clace) - Clace makes internal tool deployment and management easy by implementing an app server for containerized webapps.
- <code>&nbsp;&nbsp;&nbsp;557</code> [Euterpe](https://github.com/ironsmile/euterpe) - Self-hosted music streaming server with built-in web UI and REST API.
- <code>&nbsp;&nbsp;&nbsp;149</code> [wd-41](https://github.com/baalimago/wd-41) - A (w)eb (d)evelopment server with automatic live-reload on file changes.
- <code>&nbsp;&nbsp;&nbsp;146</code> [dudeldu](https://github.com/krotik/dudeldu) - A simple SHOUTcast server.
- <code>&nbsp;&nbsp;&nbsp;144</code> [go-proxy-cache](https://github.com/fabiocicerchia/go-proxy-cache) - Simple Reverse Proxy with Caching, written in Go, using Redis.
- <code>&nbsp;&nbsp;&nbsp;125</code> [cortex-tenant](https://github.com/blind-oracle/cortex-tenant) - Prometheus remote write proxy that adds add Cortex tenant ID header based on metric labels.
- <code>&nbsp;&nbsp;&nbsp;100</code> [lets-proxy2](https://github.com/rekby/lets-proxy2) - Reverse proxy for handle https with issue certificates in fly from lets-encrypt.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;60</code> [psql-streamer](https://github.com/blind-oracle/psql-streamer) - Stream database events from PostgreSQL to Kafka.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) - Nginx log parser and exporter to Prometheus.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> [protoxy](https://github.com/camgraff/protoxy) - A proxy server that converts JSON request bodies to Protocol Buffers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [Moxy](https://github.com/sinhashubham95/moxy) - Moxy is a simple mocker and proxy application server, you can create mock endpoints as well as proxy requests in case no mock exists for the endpoint.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> [gondola](https://github.com/bmf-san/gondola) - A YAML based golang reverse proxy.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> [riemann-relay](https://github.com/blind-oracle/riemann-relay) - Relay to load-balance Riemann events and/or convert them to Carbon.
- [nsq](https://nsq.io/) - A realtime distributed messaging platform.
- [Engity's Bifröst](https://bifroest.engity.org/) - Highly customizable SSH server with several ways to authorize a user how to execute its session (local or in containers).
- [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.

**[⬆ back to top](#contents)**

## Stream Processing

*Libraries and tools for stream processing and reactive programming.*

- <code>&nbsp;&nbsp;2066</code> [go-streams](https://github.com/reugn/go-streams) - Go stream processing library.
- <code>&nbsp;&nbsp;&nbsp;161</code> [machine](https://github.com/whitaker-io/machine) - Go library for writing and generating stream workers with built in metrics and traceability.
- <code>&nbsp;&nbsp;&nbsp;153</code> [go-etl](https://github.com/Breeze0806/go-etl) - A lightweight toolkit for data source extraction, transformation, and loading (ETL).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;95</code> [stream](https://github.com/youthlin/stream) - Go Stream, like Java 8 Stream: Filter/Map/FlatMap/Peek/Sorted/ForEach/Reduce...
- <code>&nbsp;&nbsp;&nbsp;&nbsp;86</code> [goio](https://github.com/primetalk/goio) - An implementation of IO, Stream, Fiber for Golang, inspired by awesome Scala libraries cats and fs2.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> [nibbler](https://github.com/naughtygopher/nibbler) - A lightweight package for micro batch processing.

**[⬆ back to top](#contents)**

## Template Engines

*Libraries and tools for templating and lexing.*

- <code>&nbsp;&nbsp;9554</code> [templ](https://github.com/a-h/templ) - A HTML templating language that has great developer tooling.
- <code>&nbsp;&nbsp;3248</code> [quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.
- <code>&nbsp;&nbsp;2966</code> [pongo2](https://github.com/flosch/pongo2) - Django-like template-engine for Go.
- <code>&nbsp;&nbsp;2496</code> [maroto](https://github.com/johnfercher/maroto) - A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple.
- <code>&nbsp;&nbsp;1348</code> [jet](https://github.com/CloudyKit/jet) - Jet template engine.
- <code>&nbsp;&nbsp;&nbsp;878</code> [fasttemplate](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](https://golang.org/pkg/text/template/).
- <code>&nbsp;&nbsp;&nbsp;873</code> [Razor](https://github.com/sipin/gorazor) - Razor view engine for Golang.
- <code>&nbsp;&nbsp;&nbsp;639</code> [raymond](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go.
- <code>&nbsp;&nbsp;&nbsp;584</code> [ego](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled.
- <code>&nbsp;&nbsp;&nbsp;457</code> [goview](https://github.com/foolin/goview) - Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application.
- <code>&nbsp;&nbsp;&nbsp;310</code> [liquid](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates.
- <code>&nbsp;&nbsp;&nbsp;175</code> [Soy](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/).
- <code>&nbsp;&nbsp;&nbsp;174</code> [sprout](https://github.com/go-sprout/sprout) - Useful template functions for Go templates.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> [got](https://github.com/goradd/got) - A Go code generator inspired by Hero and Fasttemplate. Has include files, custom tag definitions, injected Go code, language translation, and more.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> [tbd](https://github.com/lucasepe/tbd) - A really simple way to create text templates with placeholders - exposes extra builtin Git repo metadata.
- [htmgo](https://htmgo.dev) - build simple and scalable systems with go + htmx
- [gomponents](https://www.gomponents.com) - HTML 5 components in pure Go, that look something like this: `func(name string) g.Node { return Div(Class("headline"), g.Textf("Hi %v!", name)) }`.
- [extemplate](https://git.sr.ht/~dvko/extemplate) - Tiny wrapper around html/template to allow for easy file-based template inheritance.

**[⬆ back to top](#contents)**

## Testing

*Libraries for testing codebases and generating test data.*

### Testing Frameworks

- <code>&nbsp;24977</code> [Testify](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package.
- <code>&nbsp;10322</code> [keploy](https://github.com/keploy/keploy) - Generate Testcase and Data Mocks from API calls automatically.
- <code>&nbsp;&nbsp;8368</code> [GoConvey](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload.
- <code>&nbsp;&nbsp;4477</code> [go-cmp](https://github.com/google/go-cmp) - Package for comparing Go values in tests.
- <code>&nbsp;&nbsp;4242</code> [testcontainers-go](https://github.com/testcontainers/testcontainers-go) - A Go package that makes it simple to create and clean up container-based dependencies for automated integration/smoke tests. The clean, easy-to-use API enables developers to programmatically define containers that should be run as part of a test and clean up those resources when the test is done.
- <code>&nbsp;&nbsp;2656</code> [httpexpect](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing.
- <code>&nbsp;&nbsp;2474</code> [godog](https://github.com/cucumber/godog) - Cucumber BDD framework for Go.
- <code>&nbsp;&nbsp;1911</code> [is](https://github.com/matryer/is) - Professional lightweight testing mini-framework for Go.
- <code>&nbsp;&nbsp;1459</code> [gnomock](https://github.com/orlangure/gnomock) - integration testing with real dependencies (database, cache, even Kubernetes or AWS) running in Docker, without mocks.
- <code>&nbsp;&nbsp;1320</code> [go-vcr](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests.
- <code>&nbsp;&nbsp;1170</code> [testfixtures](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications.
- <code>&nbsp;&nbsp;&nbsp;990</code> [embedded-postgres](https://github.com/fergusstrange/embedded-postgres) - Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test.
- <code>&nbsp;&nbsp;&nbsp;890</code> [goblin](https://github.com/franela/goblin) - Mocha like testing framework of Go.
- <code>&nbsp;&nbsp;&nbsp;865</code> [goc](https://github.com/qiniu/goc) - Goc is a comprehensive coverage testing system for The Go Programming Language.
- <code>&nbsp;&nbsp;&nbsp;779</code> [baloo](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy.
- <code>&nbsp;&nbsp;&nbsp;657</code> [go-mutesting](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code.
- <code>&nbsp;&nbsp;&nbsp;564</code> [gotest.tools](https://github.com/gotestyourself/gotest.tools) - A collection of packages to augment the go testing package and support common patterns.
- <code>&nbsp;&nbsp;&nbsp;449</code> [go-testdeep](https://github.com/maxatome/go-testdeep) - Extremely flexible golang deep comparison, extends the go testing package.
- <code>&nbsp;&nbsp;&nbsp;440</code> [gofight](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework.
- <code>&nbsp;&nbsp;&nbsp;421</code> [testza](https://github.com/MarvinJWendt/testza) - Full-featured test framework with nice colorized output.
- <code>&nbsp;&nbsp;&nbsp;318</code> [cupaloy](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework.
- <code>&nbsp;&nbsp;&nbsp;276</code> [frisby](https://github.com/verdverm/frisby) - REST API testing framework.
- <code>&nbsp;&nbsp;&nbsp;269</code> [got](https://github.com/ysmood/got) - An enjoyable golang test framework.
- <code>&nbsp;&nbsp;&nbsp;268</code> [endly](https://github.com/viant/endly) - Declarative end to end functional testing.
- <code>&nbsp;&nbsp;&nbsp;260</code> [go-hit](https://github.com/Eun/go-hit) - Hit is an http integration test framework written in golang.
- <code>&nbsp;&nbsp;&nbsp;249</code> [go-carpet](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal.
- <code>&nbsp;&nbsp;&nbsp;228</code> [commander](https://github.com/SimonBaeumer/commander) - Tool for testing cli applications on windows, linux and osx.
- <code>&nbsp;&nbsp;&nbsp;224</code> [go-snaps](http://github.com/gkampitakis/go-snaps) - Jest-like snapshot testing in Golang.
- <code>&nbsp;&nbsp;&nbsp;204</code> [charlatan](https://github.com/percolate/charlatan) - Tool to generate fake interface implementations for tests.
- <code>&nbsp;&nbsp;&nbsp;164</code> [dbcleaner](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby.
- <code>&nbsp;&nbsp;&nbsp;138</code> [jsonassert](https://github.com/kinbiko/jsonassert) - Package for verifying that your JSON payloads are serialized correctly.
- <code>&nbsp;&nbsp;&nbsp;123</code> [testcase](https://github.com/adamluzsi/testcase) - Idiomatic testing framework for Behavior Driven Development.
- <code>&nbsp;&nbsp;&nbsp;108</code> [be](https://github.com/carlmjohnson/be) - The minimalist generic test assertion library.
- <code>&nbsp;&nbsp;&nbsp;106</code> [gocrest](https://github.com/corbym/gocrest) - Composable hamcrest-like matchers for Go assertions.
- <code>&nbsp;&nbsp;&nbsp;102</code> [wstest](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> [Gont](https://github.com/stv0g/gont) - Go network testing toolkit for testing building complex network topologies using Linux namespaces.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;84</code> [gherkingen](https://github.com/hedhyw/gherkingen) - BDD boilerplate generator and framework.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;75</code> [testcerts](https://github.com/madflojo/testcerts) - Dynamically generate self-signed certificates and certificate authorities within your test functions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;65</code> [assert](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;55</code> [restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;52</code> [gospecify](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> [gomatch](https://github.com/jfilipczyk/gomatch) - library created for testing JSON against patterns.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> [dsunit](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;32</code> [fixenv](https://github.com/rekby/fixenv) - Fixture manage engine, inspired by pytest fixtures.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> [Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [flute](https://github.com/suzuki-shunsuke/flute) - HTTP client testing framework.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [schema](https://github.com/jgroeneveld/schema) - Quick and easy expression matching for JSON schemas used in requests and responses.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [testsql](https://github.com/zhulongcheng/testsql) - Generate test data from SQL files before testing and clear it after finished.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [dft](https://github.com/abecodes/dft) - Lightweight, zero dependency docker containers for testing (or more).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> [gogiven](https://github.com/corbym/gogiven) - YATSPEC-like BDD testing framework for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> [biff](https://github.com/fulldump/biff) - Bifurcation testing framework, BDD compatible.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> [stop-and-go](https://github.com/elgohr/stop-and-go) - Testing helper for concurrency.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> [gosuite](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> [Tt](https://github.com/vcaesar/tt) - Simple and colorful test tools.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> [trial](https://github.com/jgroeneveld/trial) - Quick and easy extendable assertions without introducing much boilerplate.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> [go-testpredicate](https://github.com/maargenton/go-testpredicate) - Test predicate style assertions library with extensive diagnostics output.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> [envite](https://github.com/PerimeterX/envite) - Dev and testing environment management framework.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> [go-mysql-test-container](https://github.com/arikama/go-mysql-test-container) - Golang MySQL testcontainer to help with MySQL integration testing.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> [arch-go](https://github.com/fdaines/arch-go) - Architecture testing tool for Go projects.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code> [omg.testingtools](https://github.com/dedalqq/omg.testingtools) - The simple library for change a values of private fields for testing.
- [gomega](https://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
- [ginkgo](https://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
- [apitest](https://apitest.dev) - Simple and extensible behavioural testing library for REST based services or HTTP handlers that supports mocking external http calls and rendering of sequence diagrams.
- [gocheck](https://labix.org/gocheck) - More advanced testing framework alternative to gotest.

### Mock

- <code>&nbsp;&nbsp;6727</code> [mockery](https://github.com/vektra/mockery) - Tool to generate Go interfaces.
- <code>&nbsp;&nbsp;6416</code> [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions.
- <code>&nbsp;&nbsp;2947</code> [gomock](https://github.com/uber-go/mock) - Mocking framework for the Go programming language.
- <code>&nbsp;&nbsp;2424</code> [hoverfly](https://github.com/SpectoLabs/hoverfly) - HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI.
- <code>&nbsp;&nbsp;2189</code> [gock](https://github.com/h2non/gock) - Versatile HTTP mocking made easy.
- <code>&nbsp;&nbsp;2115</code> [moq](https://github.com/matryer/moq) - Utility that generates a struct from any interface. The struct can be used in test code as a mock of the interface.
- <code>&nbsp;&nbsp;2045</code> [httpmock](https://github.com/jarcoal/httpmock) - Easy mocking of HTTP responses from external resources.
- <code>&nbsp;&nbsp;1063</code> [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects.
- <code>&nbsp;&nbsp;&nbsp;722</code> [go-txdb](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes.
- <code>&nbsp;&nbsp;&nbsp;714</code> [minimock](https://github.com/gojuno/minimock) - Mock generator for Go interfaces.
- <code>&nbsp;&nbsp;&nbsp;506</code> [pgxmock](https://github.com/pashagolub/pgxmock) - A mock library implementing <code>&nbsp;12241</code> [pgx - PostgreSQL Driver and Toolkit](https://github.com/jackc/pgx/).
- <code>&nbsp;&nbsp;&nbsp;416</code> [xgo](https://github.com/xhd2015/xgo) - A general pureposed function mocking library.
- <code>&nbsp;&nbsp;&nbsp;191</code> [govcr](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;83</code> [go-localstack](https://github.com/elgohr/go-localstack) - Tool for using localstack in AWS testing.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;71</code> [timex](https://github.com/cabify/timex) - A test-friendly replacement for the native `time` package.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> [mockhttp](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [mooncake](https://github.com/GuilhermeCaruso/mooncake) - A simple way to generate mocks for multiple purposes.
- [genmock](https://gitlab.com/so_literate/genmock) - Go mocking system with code generator for building calls of the interface methods.

### Fuzzing and delta-debugging/reducing/shrinking

- <code>&nbsp;&nbsp;4834</code> [go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing system.
- <code>&nbsp;&nbsp;1503</code> [gofuzz](https://github.com/google/gofuzz) - Library for populating go objects with random values.
- <code>&nbsp;&nbsp;&nbsp;247</code> [Tavor](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework.

### Selenium and browser control tools

- <code>&nbsp;12083</code> [chromedp](https://github.com/knq/chromedp) - a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol.
- <code>&nbsp;&nbsp;6120</code> [rod](https://github.com/go-rod/rod) - A Devtools driver to make web automation and scraping easy.
- <code>&nbsp;&nbsp;2825</code> [playwright-go](https://github.com/mxschmitt/playwright-go) - browser automation library to control Chromium, Firefox and WebKit with a single API.
- <code>&nbsp;&nbsp;2646</code> [selenoid](https://github.com/aerokube/selenoid) - alternative Selenium hub server that launches browsers within containers.
- <code>&nbsp;&nbsp;&nbsp;758</code> [cdp](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it.
- <code>&nbsp;&nbsp;&nbsp;315</code> [ggr](https://github.com/aerokube/ggr) - a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs.

### Fail injection

- <code>&nbsp;&nbsp;&nbsp;854</code> [failpoint](https://github.com/pingcap/failpoint) - An implementation of [failpoints](https://www.freebsd.org/cgi/man.cgi?query=fail) for Golang.

**[⬆ back to top](#contents)**

## Text Processing

*Libraries for parsing and manipulating texts.*

See also [Natural Language Processing](#natural-language-processing) and [Text Analysis](#text-analysis).

### Formatters

- <code>&nbsp;&nbsp;4599</code> [go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format.
- <code>&nbsp;&nbsp;2315</code> [sq](https://github.com/neilotoole/sq) - Convert data from SQL databases or document formats like CSV or Excel into formats such as JSON, Excel, CSV, HTML, Markdown, XML, and YAML.
- <code>&nbsp;&nbsp;&nbsp;556</code> [bytes](https://github.com/labstack/gommon/tree/master/bytes) - Formats and parses numeric byte values (10K, 2M, 3G, etc.).
- <code>&nbsp;&nbsp;&nbsp;337</code> [gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;86</code> [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) - Fixed-width text formatting (encoder/decoder with reflection).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;84</code> [align](https://github.com/Guitarbum722/align) - A general purpose application that aligns text.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;77</code> [address](https://github.com/bojanz/address) - Handles address representation, validation and formatting.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> [textwrap](https://github.com/isbm/textwrap) - Wraps text at end of lines. Implementation of `textwrap` module from Python.

### Markup Languages

- <code>&nbsp;&nbsp;5573</code> [blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go.
- <code>&nbsp;&nbsp;4779</code> [toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection).
- <code>&nbsp;&nbsp;4220</code> [goldmark](https://github.com/yuin/goldmark) - A Markdown parser written in Go. Easy to extend, standard (CommonMark) compliant, well structured.
- <code>&nbsp;&nbsp;2968</code> [html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) - Convert HTML to Markdown. Even works with entire websites and can be extended through rules.
- <code>&nbsp;&nbsp;1837</code> [go-toml](https://github.com/pelletier/go-toml) - Go library for the TOML format with query support and handy cli tools.
- <code>&nbsp;&nbsp;&nbsp;768</code> [htmlquery](https://github.com/antchfx/htmlquery) - An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression.
- <code>&nbsp;&nbsp;&nbsp;628</code> [mxj](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.
- <code>&nbsp;&nbsp;&nbsp;267</code> [goq](https://github.com/andrewstuart/goq) - Declarative unmarshalling of HTML using struct tags with jQuery syntax (uses GoQuery).
- <code>&nbsp;&nbsp;&nbsp;108</code> [bafi](https://github.com/mmalcek/bafi) - Universal JSON, BSON, YAML, XML translator to ANY format using templates.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> [go-output-format](https://github.com/drewstinnett/go-output-format) - Output go structures into multiple formats (YAML/JSON/etc) in your command line app.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> [bbConvert](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> [htmlyaml](https://github.com/nikolaydubina/htmlyaml) - Rich rendering of YAML as HTML in Go
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> [htree](https://github.com/bobg/htree) - Traverse, navigate, filter, and otherwise process trees of [html.Node](https://pkg.go.dev/golang.org/x/net/html#Node) objects.

### Parsers/Encoders/Decoders

- <code>&nbsp;&nbsp;7931</code> [sh](https://github.com/mvdan/sh) - Shell parser and formatter.
- <code>&nbsp;&nbsp;2729</code> [gofeed](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go.
- <code>&nbsp;&nbsp;2068</code> [go-querystring](https://github.com/google/go-querystring) - Go library for encoding structs into URL query parameters.
- <code>&nbsp;&nbsp;1439</code> [when](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules.
- <code>&nbsp;&nbsp;1286</code> [godump (goforj)](https://github.com/goforj/godump) - Pretty-print Go structs with Laravel/Symfony-style dumps, full type info, colorized CLI output, cycle detection, and private field access.
- <code>&nbsp;&nbsp;&nbsp;900</code> [commonregex](https://github.com/mingrammer/commonregex) - A collection of common regular expressions for Go.
- <code>&nbsp;&nbsp;&nbsp;565</code> [gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language.
- <code>&nbsp;&nbsp;&nbsp;245</code> [go-nmea](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language.
- <code>&nbsp;&nbsp;&nbsp;217</code> [godump](https://github.com/yassinebenaid/godump) - Pretty print any GO variable with ease, an alternative to Go's `fmt.Printf("%#v")`.
- <code>&nbsp;&nbsp;&nbsp;147</code> [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go.
- <code>&nbsp;&nbsp;&nbsp;129</code> [tokenizer](https://github.com/bzick/tokenizer) - Parse any string, slice or infinite buffer to any tokens.
- <code>&nbsp;&nbsp;&nbsp;118</code> [go-vcard](https://github.com/emersion/go-vcard) - Parse and format vCard.
- <code>&nbsp;&nbsp;&nbsp;113</code> [sdp](https://github.com/gortc/sdp) - SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)].
- <code>&nbsp;&nbsp;&nbsp;&nbsp;93</code> [did](https://github.com/ockam-network/did) - DID (Decentralized Identifiers) Parser and Stringer in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> [allot](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;58</code> [vdf](https://github.com/andygrunwald/vdf) - A Lexer and Parser for Valves Data Format (known as vdf) written in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;52</code> [normalize](https://github.com/avito-tech/normalize) - Sanitize, normalize and compare fuzzy text.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;43</code> [gonameparts](https://github.com/polera/gonameparts) - Parses human names into individual name parts.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> [go-fasttld](https://github.com/elliotwutingfeng/go-fasttld) - High performance effective top level domains (eTLD) extraction module.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> [xj2go](https://github.com/stackerzzq/xj2go) - Convert xml or json to go struct.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> [codetree](https://github.com/aerogo/codetree) - Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [doi](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [parseargs-go](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [ltsv](https://github.com/Wing924/ltsv) - High performance [LTSV (Labeled Tab Separated Value)](http://ltsv.org/) reader for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> [encdec](https://github.com/mickep76/encdec) - Package provides a generic interface to encoders and decoders.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [prattle](https://github.com/askeladdk/prattle) - Scan and parse LL(1) grammars simply and efficiently.
- [parth](https://github.com/codemodus/parth) - URL path segmentation parsing.

### Regular Expressions

- <code>&nbsp;&nbsp;&nbsp;206</code> [rex](https://github.com/hedhyw/rex) - Regular expressions builder.
- <code>&nbsp;&nbsp;&nbsp;147</code> [regroup](https://github.com/oriser/regroup) - Match regex expression named groups into go struct using struct tags and automatic parsing.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;92</code> [goregen](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;87</code> [go-wildcard](https://github.com/IGLOU-EU/go-wildcard) - Simple and lightweight wildcard pattern matching.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;76</code> [genex](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings.

### Sanitation

- <code>&nbsp;&nbsp;3466</code> [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;68</code> [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) - A sanitization-based swear filter for Go.

### Scrapers

- <code>&nbsp;24494</code> [colly](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers.
- <code>&nbsp;14622</code> [GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.
- <code>&nbsp;&nbsp;1227</code> [xurls](https://github.com/mvdan/xurls) - Extract urls from text.
- <code>&nbsp;&nbsp;&nbsp;688</code> [dataflowkit](https://github.com/slotix/dataflowkit) - Web scraping Framework to turn websites into structured data.
- <code>&nbsp;&nbsp;&nbsp;109</code> [pagser](https://github.com/foolin/pagser) - Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> [Tagify](https://github.com/zoomio/tagify) - Produces a set of tags from given source.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> [go-recipe](https://github.com/kkyr/go-recipe) - A package for scraping recipes from websites.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> [walker](https://github.com/cyucelen/walker) - Seamlessly fetch paginated data from any source. Simple and high performance API scraping included.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> [go-sitemap-parser](https://github.com/aafeher/go-sitemap-parser) - Go language library for parsing Sitemaps.

### RSS

- <code>&nbsp;&nbsp;&nbsp;136</code> [podcast](https://github.com/eduncan911/podcast) - iTunes Compliant and RSS 2.0 Podcast Generator in Golang

### Utility/Miscellaneous

- <code>&nbsp;&nbsp;1173</code> [w2vgrep](https://github.com/arunsupe/semantic-grep) - A semantic grep tool using word embeddings to find semantically similar matches. For example, searching for "death" will find "dead", "killing", "murder".
- <code>&nbsp;&nbsp;&nbsp;646</code> [go-runewidth](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string.
- <code>&nbsp;&nbsp;&nbsp;193</code> [radix](https://github.com/yourbasic/radix) - Fast string sorting algorithm.
- <code>&nbsp;&nbsp;&nbsp;110</code> [go-zero-width](https://github.com/trubitsyn/go-zero-width) - Zero-width character detection and removal for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> [petrovich](https://github.com/striker2000/petrovich) - Petrovich is the library which inflects Russian names to given grammatical case.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> [TySug](https://github.com/Dynom/TySug) - Alternative suggestions with respect to keyboard layouts.

**[⬆ back to top](#contents)**

## Third-party APIs

*Libraries for accessing third party APIs.*

- <code>&nbsp;10878</code> [github](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3.
- <code>&nbsp;10213</code> [go-openai](https://github.com/sashabaranov/go-openai) - OpenAI ChatGPT, DALL·E, Whisper API library for Go.
- <code>&nbsp;&nbsp;5505</code> [discordgo](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API.
- <code>&nbsp;&nbsp;4819</code> [slack](https://github.com/slack-go/slack) - Slack API in Go.
- <code>&nbsp;&nbsp;4303</code> [google](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go.
- <code>&nbsp;&nbsp;4302</code> [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library.
- <code>&nbsp;&nbsp;3187</code> [aws-sdk-go](https://github.com/aws/aws-sdk-go-v2) - The official AWS SDK for the Go programming language.
- <code>&nbsp;&nbsp;2755</code> [minio-go](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage.
- <code>&nbsp;&nbsp;2366</code> [stripe](https://github.com/stripe/stripe-go) - Go client for the Stripe API.
- <code>&nbsp;&nbsp;1551</code> [go-jira](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira)
- <code>&nbsp;&nbsp;1384</code> [facebook](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API.
- <code>&nbsp;&nbsp;1157</code> [githubql](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4.
- <code>&nbsp;&nbsp;1142</code> [anaconda](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API.
- <code>&nbsp;&nbsp;&nbsp;992</code> [webhooks](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket.
- <code>&nbsp;&nbsp;&nbsp;742</code> [paypal](https://github.com/logpacker/PayPal-Go-SDK) - Wrapper for PayPal payment API.
- <code>&nbsp;&nbsp;&nbsp;535</code> [geo-golang](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](https://developer.mapquest.com/documentation/api/geocoding/), [Nominatim](https://nominatim.org/release-docs/latest/api/Overview/), [OpenCage](https://opencagedata.com/api), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs.
- <code>&nbsp;&nbsp;&nbsp;452</code> [lark](https://github.com/chyroc/lark) - [Feishu](https://open.feishu.cn/)/[Lark](https://open.larksuite.com/) Open API Go SDK, Support ALL Open API and Event Callback.
- <code>&nbsp;&nbsp;&nbsp;296</code> [openaigo](https://github.com/otiai10/openaigo) - OpenAI GPT3/GPT3.5 ChatGPT API client library for Go.
- <code>&nbsp;&nbsp;&nbsp;273</code> [ethrpc](https://github.com/onrik/ethrpc) - Go bindings for Ethereum JSON RPC API.
- <code>&nbsp;&nbsp;&nbsp;225</code> [Trello](https://github.com/adlio/trello) - Go wrapper for the Trello API.
- <code>&nbsp;&nbsp;&nbsp;225</code> [go-lark](https://github.com/go-lark/lark) - An easy-to-use unofficial SDK for [Feishu](https://open.feishu.cn/) and [Lark](https://open.larksuite.com/) Open Platform.
- <code>&nbsp;&nbsp;&nbsp;200</code> [go-marathon](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS.
- <code>&nbsp;&nbsp;&nbsp;169</code> [wit-go](https://github.com/wit-ai/wit-go) - Go client for wit.ai HTTP API.
- <code>&nbsp;&nbsp;&nbsp;167</code> [go-atlassian](https://github.com/ctreminiom/go-atlassian) - Go library for accessing the [Atlassian Cloud](https://www.atlassian.com/enterprise/cloud) services (Jira, Jira Service Management, Jira Agile, Confluence, Admin Cloud)
- <code>&nbsp;&nbsp;&nbsp;166</code> [simples3](https://github.com/rhnvrm/simples3) - Simple no frills AWS S3 Library using REST with V4 Signing written in Go.
- <code>&nbsp;&nbsp;&nbsp;159</code> [gosip](https://github.com/koltyakov/gosip) - Client library for SharePoint.
- <code>&nbsp;&nbsp;&nbsp;146</code> [pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API.
- <code>&nbsp;&nbsp;&nbsp;145</code> [go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github.
- <code>&nbsp;&nbsp;&nbsp;142</code> [Medium](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API.
- <code>&nbsp;&nbsp;&nbsp;138</code> [golang-tmdb](https://github.com/cyruzin/golang-tmdb) - Golang wrapper for The Movie Database API v3.
- <code>&nbsp;&nbsp;&nbsp;129</code> [gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.
- <code>&nbsp;&nbsp;&nbsp;111</code> [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP.
- <code>&nbsp;&nbsp;&nbsp;105</code> [disgo](https://github.com/switchupcb/disgo) - Go API Wrapper for the Discord API.
- <code>&nbsp;&nbsp;&nbsp;104</code> [hipchat](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API.
- <code>&nbsp;&nbsp;&nbsp;100</code> [go-gerrit](https://github.com/andygrunwald/go-gerrit) - Go client library for [Gerrit Code Review](https://www.gerritcodereview.com/).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;90</code> [cachet](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;87</code> [go-redoc](https://github.com/mvrilo/go-redoc) - Embedded OpenAPI/Swagger documentation ui for Go using [ReDoc](https://redocly.com/).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;86</code> [go-postman-collection](https://github.com/rbretecher/go-postman-collection) - Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) (compatible with Insomnia).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;86</code> [GoFreeDB](https://github.com/FreeLeh/GoFreeDB) - Golang library providing common and simple database abstractions on top of Google Sheets.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> [gogtrends](https://github.com/groovili/gogtrends) - Google Trends Unofficial API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;84</code> [igdb](https://github.com/Henry-Sarabia/igdb) - Go client for the [Internet Game Database API](https://api.igdb.com/).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;82</code> [airtable](https://github.com/mehanizm/airtable) - Go client library for the [Airtable API](https://airtable.com/api).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;76</code> [go-unsplash](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;74</code> [ynab](https://github.com/brunomvsouza/ynab.go) - Go wrapper for the YNAB API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;65</code> [circleci](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;61</code> [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;60</code> [mixpanel](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;57</code> [uptimerobot](https://github.com/bitfield/uptimerobot) - Go wrapper and command-line client for the Uptime Robot v2 API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;55</code> [clarifai](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> [megos](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](https://mesos.apache.org/) cluster.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> [go-xkcd](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> [gads](https://github.com/emiddleton/gads) - Google Adwords Unofficial API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> [fcm](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> [spotify](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> [swag](https://github.com/zc2638/swag) - No comments, simple go wrapper to create swagger 2.0 compatible APIs. Support most routing frameworks, such as built-in, gin, chi, mux, echo, httprouter, fasthttp and more.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;44</code> [go-salesforce](https://github.com/k-capehart/go-salesforce) - Go client library for interacting with the [Salesforce REST API](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_list.htm).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;44</code> [patreon-go](https://github.com/mxpv/patreon-go) - Go library for Patreon API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;42</code> [go-myanimelist](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](https://myanimelist.net/apiconfig/references/api/v2).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> [golyrics](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [lastpass-go](https://github.com/ansd/lastpass-go) - Go client library for the [LastPass](https://www.lastpass.com/) API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> [steam](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> [gcm](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> [jokeapi-go](https://github.com/icelain/jokeapi) - Go client for [JokeAPI](https://sv443.net/jokeapi/v2/).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) - Go client library for interacting with Coinpaprika's API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> [shopify](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> [device-check-go](https://github.com/rinchsan/device-check-go) - Go client library for interacting with [iOS DeviceCheck API](https://developer.apple.com/documentation/devicecheck) v1.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> [go-imgur](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com)
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> [aws-encryption-sdk-go](https://github.com/chainifynet/aws-encryption-sdk-go) - Unofficial Go SDK implementation of the [AWS Encryption SDK](https://docs.aws.amazon.com/encryption-sdk/latest/developer-guide/index.html).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> [brewerydb](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> [textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> [go-openproject](https://github.com/manuelbcd/go-openproject) - Go client library for interacting with [OpenProject](https://docs.openproject.org/api/) API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> [codeship-go](https://github.com/codeship/codeship-go) - Go client library for interacting with Codeship's API v2.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [go-aws-news](https://github.com/circa10a/go-aws-news) - Go application and library to fetch what's new from AWS.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [goami2](https://github.com/staskobzar/goami2) - AMI v2 library for Asterisk PBX.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [go-hacknews](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [gopaapi5](https://github.com/utekaravinash/gopaapi5) - Go Client Library for [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [bqwriter](https://github.com/OTA-Insight/bqwriter) - High Level Go Library to write data into [Google BigQuery](https://cloud.google.com/bigquery) at a high throughout.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> [google-analytics](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [go-here](https://github.com/abdullahselek/go-here) - Go client library around the HERE location based APIs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [rawg-sdk-go](https://github.com/dimuska139/rawg-sdk-go) - Go library for the [RAWG Video Games Database](https://rawg.io/) API
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [ip2location-io-go](https://github.com/ip2location/ip2location-io-go) - Go wrapper for the IP2Location.io API [IP2Location.io](https://www.ip2location.io/).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> [go-sophos](https://github.com/esurdam/go-sophos) - Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> [gomalshare](https://github.com/MonaxGT/gomalshare) - Go library MalShare API [malshare.com](https://www.malshare.com/)
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [goagi](https://github.com/staskobzar/goagi) - Go library to build Asterisk PBX agi/fastagi applications.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [go-swagger-ui](https://github.com/esurdam/go-swagger-ui) - Go library containing precompiled [Swagger UI](https://swagger.io/tools/swagger-ui/) for serving swagger json.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [smite](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [libgoffi](https://github.com/clevabit/libgoffi) - Library adapter toolbox for native [libffi](https://sourceware.org/libffi/) integration
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [go-hibp](https://github.com/wneessen/go-hibp) - Simple Go binding to the "Have I Been Pwned" APIs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> [go-chronos](https://github.com/axelspringer/go-chronos) - Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> [tumblr](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [newsapi-go](https://github.com/jellydator/newsapi-go) - Go client for [NewsAPI](https://newsapi.org/).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [zooz](https://github.com/gojuno/go-zooz) - Go client for the Zooz API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> [appstore-sdk-go](https://github.com/Kachit/appstore-sdk-go) - Unofficial Golang SDK for AppStore Connect API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> [go-restcountries](https://github.com/chriscross0/go-restcountries) - Go library for the [REST Countries API](https://countrylayer.com/).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> [dusupay-sdk-go](https://github.com/Kachit/dusupay-sdk-go) - Unofficial Dusupay payment gateway API Client for Go
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> [gopensky](https://github.com/navidys/gopensky) - Go client implementation for [OpenSKY Network](https://opensky-network.org/) live's API (airspace ADS-B and Mode S data).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> [TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) - Go wrapper for the TripAdvisor API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> [vl-go](https://github.com/verifid/vl-go) - Go client library around the VerifID identity verification layer API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> [fasapay-sdk-go](https://github.com/Kachit/fasapay-sdk-go) - Unofficial Fasapay payment gateway XML API Client for Golang.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK.
- [go-telegraph](https://gitlab.com/toby3d/telegraph) - Telegraph publishing platform API client.
- [go-yapla](https://gitlab.com/adrienK/go-yapla) - Go client library for the Yapla v2.0 API.

**[⬆ back to top](#contents)**

## Utilities

*General utilities and tools to make your life easier.*

- <code>&nbsp;72477</code> [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go.
- <code>&nbsp;51549</code> [dive](https://github.com/wagoodman/dive) - A tool for exploring each layer in a Docker image.
- <code>&nbsp;22906</code> [hub](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal.
- <code>&nbsp;19848</code> [lo](https://github.com/samber/lo) - A Lodash like Go library based on Go 1.18+ Generics (map, filter, contains, find...)
- <code>&nbsp;17092</code> [sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package.
- <code>&nbsp;16736</code> [ctop](https://github.com/bcicen/ctop) - [Top-like](https://ctop.sh) interface (e.g. htop) for container metrics.
- <code>&nbsp;14981</code> [goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible.
- <code>&nbsp;10677</code> [wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection.
- <code>&nbsp;&nbsp;9467</code> [usql](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases.
- <code>&nbsp;&nbsp;7777</code> [peco](https://github.com/peco/peco) - Simplistic interactive filtering tool.
- <code>&nbsp;&nbsp;5151</code> [lancet](https://github.com/duke-git/lancet) - A comprehensive, efficient, and reusable util function library of go.
- <code>&nbsp;&nbsp;4917</code> [go-funk](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).
- <code>&nbsp;&nbsp;4200</code> [godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox.
- <code>&nbsp;&nbsp;3922</code> [minify](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats.
- <code>&nbsp;&nbsp;3683</code> [panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump.
- <code>&nbsp;&nbsp;3137</code> [goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report.
- <code>&nbsp;&nbsp;3114</code> [mc](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.
- <code>&nbsp;&nbsp;3030</code> [mergo](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.
- <code>&nbsp;&nbsp;2743</code> [retry-go](https://github.com/avast/retry-go) - Simple library for retry mechanism.
- <code>&nbsp;&nbsp;2720</code> [create-go-app](https://github.com/create-go-app/cli) - A powerful CLI for create a new production-ready project with backend (Golang), frontend (JavaScript, TypeScript) & deploy automation (Ansible, Docker) by running one command.
- <code>&nbsp;&nbsp;2258</code> [EaseProbe](https://github.com/megaease/easeprobe) - A simple, standalone, and lightWeight tool that can do health/status checking daemon, support HTTP/TCP/SSH/Shell/Client/... probes, and Slack/Discord/Telegram/SMS... notification.
- <code>&nbsp;&nbsp;2218</code> [filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature.
- <code>&nbsp;&nbsp;2087</code> [Storm](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB.
- <code>&nbsp;&nbsp;1873</code> [jump](https://github.com/gsamokovarov/jump) - Jump helps you navigate faster by learning your habits.
- <code>&nbsp;&nbsp;1835</code> [mimetype](https://github.com/gabriel-vasile/mimetype) - Package for MIME type detection based on magic numbers.
- <code>&nbsp;&nbsp;1819</code> [Failsafe-go](https://github.com/failsafe-go/failsafe-go) - Fault tolerance and resilience patterns for Go.
- <code>&nbsp;&nbsp;1739</code> [boilr](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates.
- <code>&nbsp;&nbsp;1715</code> [mole](https://github.com/davrodpin/mole) - cli app to easily create ssh tunnels.
- <code>&nbsp;&nbsp;1558</code> [gitbatch](https://github.com/isacikgoz/gitbatch) - manage your git repositories in one place.
- <code>&nbsp;&nbsp;1450</code> [scany](https://github.com/georgysavva/scany) - Library for scanning data from a database into Go structs and more.
- <code>&nbsp;&nbsp;1322</code> [bed](https://github.com/itchyny/bed) - A Vim-like binary editor written in Go.
- <code>&nbsp;&nbsp;1176</code> [sesh](https://github.com/joshmedeski/sesh) - Sesh is a CLI that helps you create and manage tmux sessions quickly and easily using zoxide.
- <code>&nbsp;&nbsp;1167</code> [hostctl](https://github.com/guumaster/hostctl) - A CLI tool to manage /etc/hosts with easy commands.
- <code>&nbsp;&nbsp;1149</code> [circuitbreaker](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go.
- <code>&nbsp;&nbsp;&nbsp;997</code> [git-time-metric](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git.
- <code>&nbsp;&nbsp;&nbsp;949</code> [upterm](https://github.com/owenthereal/upterm) - A tool for developers to share terminal/tmux sessions securely over the web. It’s perfect for remote pair programming, accessing computers behind NATs/firewalls, remote debugging, and more.
- <code>&nbsp;&nbsp;&nbsp;824</code> [immortal](https://github.com/immortal/immortal) - \*nix cross-platform (OS agnostic) supervisor.
- <code>&nbsp;&nbsp;&nbsp;786</code> [circuit](https://github.com/cep21/circuit) - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern.
- <code>&nbsp;&nbsp;&nbsp;783</code> [changie](https://github.com/miniscruff/changie) - Automated changelog tool for preparing releases with lots of customization options.
- <code>&nbsp;&nbsp;&nbsp;709</code> [clockwork](https://github.com/jonboulle/clockwork) - A simple fake clock for golang.
- <code>&nbsp;&nbsp;&nbsp;709</code> [clipboard](https://github.com/golang-design/clipboard) - 📋 cross-platform clipboard package in Go.
- <code>&nbsp;&nbsp;&nbsp;654</code> [delve](https://github.com/derekparker/delve) - Go debugger.
- <code>&nbsp;&nbsp;&nbsp;636</code> [ergo](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy.
- <code>&nbsp;&nbsp;&nbsp;612</code> [remote-touchpad](https://github.com/Unrud/remote-touchpad) - Control mouse and keyboard from a smartphone.
- <code>&nbsp;&nbsp;&nbsp;597</code> [scan](https://github.com/blockloop/scan) - Scan golang `sql.Rows` directly to structs, slices, or primitive types.
- <code>&nbsp;&nbsp;&nbsp;579</code> [limiters](https://github.com/mennanov/limiters) - Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks.
- <code>&nbsp;&nbsp;&nbsp;568</code> [mani](https://github.com/alajmo/mani) - CLI tool to help you manage multiple repositories.
- <code>&nbsp;&nbsp;&nbsp;556</code> [htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility.
- <code>&nbsp;&nbsp;&nbsp;531</code> [koazee](https://github.com/wesovilabs/koazee) - Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays.
- <code>&nbsp;&nbsp;&nbsp;500</code> [gubrak](https://github.com/novalagung/gubrak) - Golang utility library with syntactic sugar. It's like lodash, but for golang.
- <code>&nbsp;&nbsp;&nbsp;495</code> [godaemon](https://github.com/VividCortex/godaemon) - Utility to write daemons.
- <code>&nbsp;&nbsp;&nbsp;487</code> [go-dry](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go.
- <code>&nbsp;&nbsp;&nbsp;462</code> [countries](https://github.com/biter777/countries) - Full implementation of ISO-3166-1, ISO-4217, ITU-T E.164, Unicode CLDR and IANA ccTLD standards.
- <code>&nbsp;&nbsp;&nbsp;453</code> [gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.
- <code>&nbsp;&nbsp;&nbsp;425</code> [request](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™.
- <code>&nbsp;&nbsp;&nbsp;403</code> [go-rate](https://github.com/beefsack/go-rate) - Timed rate limiter for Go.
- <code>&nbsp;&nbsp;&nbsp;383</code> [config-file-validator](https://github.com/Boeing/config-file-validator) - Cross Platform tool to validate configuration files.
- <code>&nbsp;&nbsp;&nbsp;375</code> [grofer](https://github.com/pesos/grofer) - A system and resource monitoring tool written in Golang!
- <code>&nbsp;&nbsp;&nbsp;347</code> [serve](https://github.com/syntaqx/serve) - A static http server anywhere you need.
- <code>&nbsp;&nbsp;&nbsp;345</code> [retry](https://github.com/kamilsk/retry) - The most advanced functional mechanism to perform actions repetitively until successful.
- <code>&nbsp;&nbsp;&nbsp;341</code> [rospo](https://github.com/ferama/rospo) - Simple and reliable ssh tunnels with embedded ssh server in Golang.
- <code>&nbsp;&nbsp;&nbsp;306</code> [gotenv](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go.
- <code>&nbsp;&nbsp;&nbsp;299</code> [util](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...).
- <code>&nbsp;&nbsp;&nbsp;274</code> [wifiqr](https://github.com/reugn/wifiqr) - Wi-Fi QR Code Generator.
- <code>&nbsp;&nbsp;&nbsp;250</code> [pattern-match](https://github.com/alexpantyukhin/go-pattern-match) - Pattern matching library.
- <code>&nbsp;&nbsp;&nbsp;249</code> [go-trigger](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.
- <code>&nbsp;&nbsp;&nbsp;225</code> [toolbox](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer.
- <code>&nbsp;&nbsp;&nbsp;225</code> [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go.
- <code>&nbsp;&nbsp;&nbsp;198</code> [Death](https://github.com/vrecan/death) - Managing go application shutdown with signals.
- <code>&nbsp;&nbsp;&nbsp;181</code> [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only).
- <code>&nbsp;&nbsp;&nbsp;172</code> [goval](https://github.com/maja42/goval) - Evaluate arbitrary expressions in Go.
- <code>&nbsp;&nbsp;&nbsp;169</code> [moldova](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template.
- <code>&nbsp;&nbsp;&nbsp;167</code> [apm](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API.
- <code>&nbsp;&nbsp;&nbsp;166</code> [rerun](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes.
- <code>&nbsp;&nbsp;&nbsp;166</code> [go-bsdiff](https://github.com/gabstv/go-bsdiff) - Pure Go bsdiff and bspatch libraries and CLI tools.
- <code>&nbsp;&nbsp;&nbsp;160</code> [json-log-viewer](https://github.com/hedhyw/json-log-viewer) - Interactive viewer for JSON logs.
- <code>&nbsp;&nbsp;&nbsp;160</code> [cmd](https://github.com/SimonBaeumer/cmd) - Library for executing shell commands on osx, windows and linux.
- <code>&nbsp;&nbsp;&nbsp;159</code> [robustly](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics.
- <code>&nbsp;&nbsp;&nbsp;158</code> [chyle](https://github.com/antham/chyle) - Changelog generator using a git repository with multiple configuration possibilities.
- <code>&nbsp;&nbsp;&nbsp;154</code> [cryptgo](https://github.com/Gituser143/cryptgo) - Crytpgo is a TUI based application written purely in Go to monitor and observe cryptocurrency prices in real time!
- <code>&nbsp;&nbsp;&nbsp;151</code> [filter](https://github.com/gookit/filter) - provide filtering, sanitizing, and conversion of Go data.
- <code>&nbsp;&nbsp;&nbsp;146</code> [nostromo](https://github.com/pokanop/nostromo) - CLI for building powerful aliases.
- <code>&nbsp;&nbsp;&nbsp;137</code> [sorty](https://github.com/jfcg/sorty) - Fast Concurrent / Parallel Sorting.
- <code>&nbsp;&nbsp;&nbsp;136</code> [onecache](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc).
- <code>&nbsp;&nbsp;&nbsp;132</code> [mongo-go-pagination](https://github.com/gobeam/mongo-go-pagination) - Mongodb Pagination for official mongodb/mongo-go-driver package which supports both normal queries and Aggregation pipelines.
- <code>&nbsp;&nbsp;&nbsp;128</code> [lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go.
- <code>&nbsp;&nbsp;&nbsp;124</code> [gitcs](https://github.com/knbr13/gitcs/) - Git Commits Visualizer, CLI tool to visualize your Git commits on your local machine.
- <code>&nbsp;&nbsp;&nbsp;120</code> [go-lock](https://github.com/viney-shih/go-lock) - go-lock is a lock library implementing read-write mutex and read-write trylock without starvation.
- <code>&nbsp;&nbsp;&nbsp;116</code> [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features.
- <code>&nbsp;&nbsp;&nbsp;111</code> [cookie](https://github.com/syntaqx/cookie) - Cookie struct parsing and helper package.
- <code>&nbsp;&nbsp;&nbsp;102</code> [mssqlx](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind.
- <code>&nbsp;&nbsp;&nbsp;102</code> [xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang.
- <code>&nbsp;&nbsp;&nbsp;100</code> [mimemagic](https://github.com/zRedShift/mimemagic) - Pure Go ultra performant MIME sniffing library/utility.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;96</code> [go-health](https://github.com/Talento90/go-health) - Health package simplifies the way you add health check to your services.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;95</code> [go-lambda-cleanup](https://github.com/karl-cardenas-coding/go-lambda-cleanup) - A CLI for removing unused or previous versions of AWS Lambdas.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;93</code> [go-pattern-match](https://github.com/PhakornKiong/go-pattern-match) - A Pattern matching library inspired by ts-pattern.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;92</code> [countries](https://github.com/pioz/countries) - All you need when you are working with countries in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;91</code> [equalizer](https://github.com/reugn/equalizer) - Quota manager and rate limiter collection for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;88</code> [pgo](https://github.com/arthurkushman/pgo) - Convenient functions for PHP community.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> [repeat](https://github.com/ssgreg/repeat) - Go implementation of different backoff strategies useful for retrying operations and heartbeating.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;82</code> [handy](https://github.com/miguelpragier/handy) - Many utilities and helpers like string handlers/formatters and validators.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;79</code> [pm](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;72</code> [netbug](https://github.com/e-dard/netbug) - Easy remote profiling of your services.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;70</code> [UNIS](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;70</code> [multitick](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;69</code> [goreadability](https://github.com/philipjkim/goreadability) - Webpage summary extractor using Facebook Open Graph and arc90's readability.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;68</code> [dbt](https://github.com/nikogura/dbt) - A framework for running self-updating signed binaries from a central, trusted repository.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> [backscanner](https://github.com/icza/backscanner) - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> [scan](https://github.com/wroge/scan) - Scan sql rows into any type powered by generics.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;66</code> [go-astitodo](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;66</code> [retry](https://github.com/thedevsaddam/retry) - Simple and easy retry mechanism package for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;63</code> [golog](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;62</code> [minquery](https://github.com/icza/minquery) - MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;60</code> [shutdown](https://github.com/ztrue/shutdown) - App shutdown hooks for `os.Signal` handling.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> [copy-pasta](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> [golarm](https://github.com/msempere/golarm) - Fire alarms with system events.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> [cvt](https://github.com/shockerli/cvt) - Easy and safe convert any value to another type.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> [gofn](https://github.com/tiendc/gofn) - High performance utility functions written using Generics for Go 1.18+.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> [sshman](https://github.com/shoobyban/sshman) - SSH Manager for authorized_keys files on multiple remote servers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> [slice](https://github.com/psampaz/slice) - Type-safe functions for common Go slice operations.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> [goback](https://github.com/carlescere/goback) - Go simple exponential backoff package.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> [retry-go](https://github.com/rafaeljesus/retry-go) - Retrying made simple and easy for golang.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> [go-httpheader](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> [ghokin](https://github.com/antham/ghokin) - Parallelized formatter with no external dependencies for gherkin (cucumber, behat...).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> [gostrutils](https://github.com/ik5/gostrutils) - Collections of string manipulation and conversion functions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> [slicer](https://github.com/leaanthony/slicer) - Makes working with slices easier.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> [set](https://github.com/nofeaturesonlybugs/set) - Performant and flexible struct mapping and loose type conversion.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;46</code> [yogo](https://github.com/antham/yogo) - Check yopmail mails from command line.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> [pointer](https://github.com/xorcare/pointer) - Package pointer contains helper routines for simplifying the creation of optional fields of basic type.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;42</code> [evaluator](https://github.com/nullne/evaluator) - Evaluate an expression dynamically based on s-expression. It's simple and easy to extend.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> [go-qr](https://github.com/piglig/go-qr) - A native, high-quality and minimalistic QR code generator.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> [throttle](https://github.com/yudppp/throttle) - Throttle is an object that will perform exactly one action per duration.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> [just](https://github.com/kazhuravlev/just) - Just a collection of useful functions for working with generic data structures.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [rclient](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [tome](https://github.com/cyruzin/tome) - Tome was designed to paginate simple RESTful APIs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [watchhttp](https://github.com/nikolaydubina/watchhttp) - Run command periodically and expose latest STDOUT or its rich delta as HTTP endpoint.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> [mimesniffer](https://github.com/aofei/mimesniffer) - A MIME type sniffer for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> [git-tools](https://github.com/kazhuravlev/git-tools) - Tool to help manage git tags.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> [generate](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> [debounce](https://github.com/floatdrop/debounce) - A zero-allocation debouncer written in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> [goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> [graterm](https://github.com/skovtunenko/graterm) - Provides primitives to perform ordered (sequential/concurrent) GRAceful TERMination (aka shutdown) in Go application.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> [ptr](https://github.com/gotidy/ptr) - Package that provide functions for simplified creation of pointers from constants of basic types.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> [ctxutil](https://github.com/posener/ctxutil) - A collection of utility functions for contexts.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> [structs](https://github.com/PumpkinSeed/structs) - Implement simple functions to manipulate structs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> [go-convert](https://github.com/Eun/go-convert) - Package go-convert enables you to convert a value into another type.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> [jsend](https://github.com/clevergo/jsend) - JSend's implementation written in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> [healthcheck](https://github.com/kazhuravlev/healthcheck) - A simple yet powerful readiness test for Kubernetes.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> [go-type](https://github.com/mikekonan/go-types) - Library providing Go types for store/validation and transfer of ISO-4217, ISO-3166, and other types.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> [filler](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [dlog](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) - Go package for working with Problem Details.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [rest-go](https://github.com/edermanoel94/rest-go) - A package that provide many helpful methods for working with rest api.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [go-countries](https://github.com/mikekonan/go-countries) - Lightweight lookup over ISO-3166 codes.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [okrun](https://github.com/xta/okrun) - go run error steamroller.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> [go-tripper](https://github.com/rajnandan1/go-tripper) - Tripper is a circuit breaker package for Go that allows you to circuit and control the status of circuits.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> [silk](https://github.com/chrispassas/silk) - Read silk netflow files.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> [go-clip](https://github.com/prashantgupta24/go-clip) - A minimalistic clipboard manager for Mac.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [retry](https://github.com/shafreeck/retry) - A pretty simple library to ensure your work to be done.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [blank](https://github.com/Henry-Sarabia/blank) - Verify or remove blanks and whitespace from strings.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [command](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> [jet](https://github.com/NicoNex/jet) - Just Edit Text: a fast and powerful tool for finding and replacing file content and names using regular expressions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [loncha](https://github.com/kazu/loncha) - A high-performance slice Utilities.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [nfdump](https://github.com/chrispassas/nfdump) - Read nfdump netflow files.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [statiks](https://github.com/janiltonmaciel/statiks) - Fast, zero-configuration, static HTTP filer server.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [bleep](https://github.com/sinhashubham95/bleep) - Perform any number of actions on any set of OS signals in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [retry](https://github.com/percolate/retry) - A simple but highly configurable retry package for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [goctx](https://github.com/zerosnake0/goctx) - Get your context value with high performance.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [optional](https://github.com/kazhuravlev/optional) - Optional struct fields and vars.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> [sliceconv](https://github.com/Henry-Sarabia/sliceconv) - Slice conversion between primitive types.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [go-events](https://github.com/deatil/go-events) - A go event and event'subscribe package, like wordpress hook functions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [lets-go](https://github.com/aplescia-chwy/lets-go) - Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [go-pkg](https://github.com/chenquan/go-pkg) - A go toolkit.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> [tik](https://github.com/andy2046/tik) - Simple and easy timing wheel package for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> [olaf](https://github.com/btnguyen2k/olaf) - Twitter Snowflake implemented in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> [xpool](https://github.com/peczenyj/xpool) - Yet another golang type safe object pool using generics.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> [go-actuator](https://github.com/sinhashubham95/go-actuator) - Production ready features for Go based web frameworks.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> [lang](https://github.com/maxbolgarin/lang) - Generic one-liners to work with variables, slices and maps without boilerplate code.

**[⬆ back to top](#contents)**

## UUID

*Libraries for working with UUIDs.*

- <code>&nbsp;&nbsp;5756</code> [uuid](https://github.com/google/uuid) - Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services.
- <code>&nbsp;&nbsp;4790</code> [ulid](https://github.com/oklog/ulid) - Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier).
- <code>&nbsp;&nbsp;4166</code> [xid](https://github.com/rs/xid) - Xid is a globally unique id generator library, ready to be safely used directly in your server code.
- <code>&nbsp;&nbsp;1706</code> [uuid](https://github.com/gofrs/uuid) - Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid.
- <code>&nbsp;&nbsp;&nbsp;541</code> [wuid](https://github.com/edwingeng/wuid) - An extremely fast globally unique number generator.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;92</code> [sno](https://github.com/muyo/sno) - Compact, sortable and fast unique IDs with embedded metadata.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;71</code> [guid](https://github.com/sdrapkin/guid) - Fast cryptographically safe Guid generator for Go (~10x faster than `uuid`).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;62</code> [nanoid](https://github.com/aidarkhanov/nanoid) - A tiny and efficient Go unique string ID generator.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> [goid](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> [gouid](https://github.com/twharmon/gouid) - Generate cryptographically secure random string IDs with just one allocation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> [uuid](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> [uuidcheck](https://github.com/ashwingopalsamy/uuidcheck) - A tiny, dependency-free Go library that validates UUIDs against standard RFC 4122 formatting, converts UUIDv7() into UTC timestamps.
- [uniq](https://gitlab.com/skilstak/code/go/uniq) - No hassle safe, fast unique identifiers with commands.
- [fastuuid](https://github.com/rekby/fastuuid) - Fast generate UUIDv4 as string or bytes.

**[⬆ back to top](#contents)**

## Validation

*Libraries for validation.*

- <code>&nbsp;18772</code> [validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.
- <code>&nbsp;&nbsp;6171</code> [govalidator](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs.
- <code>&nbsp;&nbsp;3965</code> [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags.
- <code>&nbsp;&nbsp;1338</code> [govalidator](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation.
- <code>&nbsp;&nbsp;1104</code> [validate](https://github.com/gookit/validate) - Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features.
- <code>&nbsp;&nbsp;&nbsp;933</code> [Zog](https://github.com/Oudwins/zog) - A <code>&nbsp;39323</code> [Zod](https://github.com/colinhacks/zod) inspired schema builder for runtime value parsing and validation. **[⬆ back to top](#contents)**
- <code>&nbsp;&nbsp;&nbsp;161</code> [gody](https://github.com/guiferpa/gody) - :balloon: A lightweight struct validator for Go.
- <code>&nbsp;&nbsp;&nbsp;118</code> [jio](https://github.com/faceair/jio) - jio is a json schema validator similar to <code>&nbsp;21135</code> [joi](https://github.com/hapijs/joi).
- <code>&nbsp;&nbsp;&nbsp;111</code> [checkdigit](https://github.com/osamingo/checkdigit) - Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;99</code> [govalid](https://github.com/twharmon/govalid) - Fast, tag-based validation for structs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;93</code> [validate](https://github.com/gobuffalo/validate) - This package provides a framework for writing validations for Go applications.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> [valix](https://github.com/marrow16/valix) Go package for validating requests
- <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> [go-validator](https://github.com/tiendc/go-validator) - Validation library using Generics.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> [hvalid](https://github.com/lyonnee/hvalid) hvalid is a lightweight validation library written in Go language. It provides a custom validator interface and a series of common validation functions to help developers quickly implement data validation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [Validator](https://github.com/go-the-way/validator) - A lightweight model validator written in Go.Contains VFs:Min, Max, MinLength, MaxLength, Length, Enum, Regex.

## Version Control

*Libraries for version control.*

- <code>&nbsp;&nbsp;6748</code> [go-git](https://github.com/go-git/go-git) - highly extensible Git implementation in pure Go.
- <code>&nbsp;&nbsp;2722</code> [hercules](https://github.com/src-d/hercules) - gaining advanced insights from Git repository history.
- <code>&nbsp;&nbsp;1977</code> [git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2.
- <code>&nbsp;&nbsp;&nbsp;111</code> [githooks](https://github.com/gabyx/githooks) - Per-repo and shared Git hooks with version control and auto update.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;80</code> [go-vcs](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> [froggit-go](https://github.com/jfrog/froggit-go) - Froggit-Go is a Go library, allowing to perform actions on VCS providers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [hgo](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories.
- [cli](https://gitlab.com/gitlab-org/cli) - An open-source GitLab command line tool bringing GitLab's cool features to your command line.

**[⬆ back to top](#contents)**

## Video

*Libraries for manipulating video.*

- <code>&nbsp;&nbsp;2126</code> [goav](https://github.com/giorgisio/goav) - Comprehensive Go bindings for FFmpeg.
- <code>&nbsp;&nbsp;1265</code> [m3u8](https://github.com/grafov/m3u8) - Parser and generator library of M3U8 playlists for Apple HLS.
- <code>&nbsp;&nbsp;&nbsp;917</code> [gmf](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries.
- <code>&nbsp;&nbsp;&nbsp;813</code> [gortsplib](https://github.com/aler9/gortsplib) - Pure Go RTSP server and client library.
- <code>&nbsp;&nbsp;&nbsp;648</code> [go-astisub](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).
- <code>&nbsp;&nbsp;&nbsp;578</code> [go-astits](https://github.com/asticode/go-astits) - Parse and demux MPEG Transport Streams (.ts) natively in GO.
- <code>&nbsp;&nbsp;&nbsp;539</code> [mp4ff](https://github.com/Eyevinn/mp4ff) - Library and tools for working with MP4 files containing video, audio, subtitles, or metadata.
- <code>&nbsp;&nbsp;&nbsp;529</code> [go-astiav](https://github.com/asticode/go-astiav) - Better C bindings for ffmpeg in GO.
- <code>&nbsp;&nbsp;&nbsp;476</code> [libvlc-go](https://github.com/adrg/libvlc-go) - Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> [v4l](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [go-m3u8](https://github.com/etherlabsio/go-m3u8) - Parser and generator library for Apple m3u8 playlists. Actively maintained version of quangngotan95/go-m3u8 with improvements and latest HLS playlist parsing compatibility.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> [go-mpd](https://github.com/unki2aut/go-mpd) - Parser and generator library for MPEG-DASH manifest files.

**[⬆ back to top](#contents)**

## Web Frameworks

*Full stack web frameworks.*

- <code>&nbsp;83409</code> [Gin](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.
- <code>&nbsp;37284</code> [Fiber](https://github.com/gofiber/fiber) - An Express.js inspired web framework build on Fasthttp.
- <code>&nbsp;32181</code> [Beego](https://github.com/beego/beego) - beego is an open-source, high-performance web framework for the Go programming language.
- <code>&nbsp;31337</code> [Echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework.
- <code>&nbsp;13216</code> [Revel](https://github.com/revel/revel) - High-productivity web framework for the Go language.
- <code>&nbsp;12659</code> [GoFr](https://github.com/gofr-dev/gofr) - Gofr is an opinionated microservice development framework.
- <code>&nbsp;12603</code> [GoFrame](https://github.com/gogf/gf) - GoFrame is a modular, powerful, high-performance and enterprise-class application development framework of Golang.
- <code>&nbsp;&nbsp;6536</code> [Hertz](https://github.com/cloudwego/hertz) - A high-performance and strong-extensibility Go HTTP framework that helps developers build microservices.
- <code>&nbsp;&nbsp;5913</code> [Goa](https://github.com/goadesign/goa) - Goa provides a holistic approach for developing remote APIs and microservices in Go.
- <code>&nbsp;&nbsp;3938</code> [goravel](https://github.com/goravel/goravel) - A Laravel-inspired web framework with ORM, authentication, queue, task scheduling, and more built-in features.
- <code>&nbsp;&nbsp;3278</code> [Huma](https://github.com/danielgtaylor/huma/) - Framework for modern REST/GraphQL APIs with built-in OpenAPI 3, generated documentation, and a CLI.
- <code>&nbsp;&nbsp;1719</code> [Goyave](https://github.com/go-goyave/goyave) - Feature-complete REST API framework aimed at clean code and fast development, with powerful built-in functionalities.
- <code>&nbsp;&nbsp;1459</code> [Fuego](https://github.com/go-fuego/fuego) - The framework for busy Go developers! Web framework generating OpenAPI 3 spec from source code.
- <code>&nbsp;&nbsp;1288</code> [Atreugo](https://github.com/savsgio/atreugo) - High performance and extensible micro web framework with zero memory allocations in hot paths.
- <code>&nbsp;&nbsp;&nbsp;847</code> [templui](https://github.com/axzilla/templui) - Modern UI Components for Go & Templ.
- <code>&nbsp;&nbsp;&nbsp;740</code> [Yokai](https://github.com/ankorstore/yokai) - Simple, modular, and observable Go framework for backend applications.
- <code>&nbsp;&nbsp;&nbsp;584</code> [iWF](https://github.com/indeedeng/iwf) - iWF is an all-in-one platform for developing long-running business processes. It offers a convenient abstraction for utilizing databases, ElasticSearch, message queues, durable timers, and more, with a clean, simple, and user-friendly interface.
- <code>&nbsp;&nbsp;&nbsp;568</code> [Flamingo Commerce](https://github.com/i-love-flamingo/flamingo-commerce) - Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications.
- <code>&nbsp;&nbsp;&nbsp;545</code> [rk-boot](https://github.com/rookie-ninja/rk-boot) - A bootstrapper library for building enterprise go microservice with Gin and gRPC quickly and easily.
- <code>&nbsp;&nbsp;&nbsp;540</code> [Flamingo](https://github.com/i-love-flamingo/flamingo) - Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc.
- <code>&nbsp;&nbsp;&nbsp;476</code> [Fastschema](https://github.com/fastschema/fastschema) - A flexible Go web framework and Headless CMS.
- <code>&nbsp;&nbsp;&nbsp;352</code> [uAdmin](https://github.com/uadmin/uadmin) - Fully featured web framework for Golang, inspired by Django.
- <code>&nbsp;&nbsp;&nbsp;308</code> [WebGo](https://github.com/naughtygopher/webgo) - A micro-framework to build web apps with handler chaining, middleware, and context injection. With standard library-compliant HTTP handlers (i.e., `http.HandlerFunc`)..
- <code>&nbsp;&nbsp;&nbsp;297</code> [Ginrpc](https://github.com/xxjwxc/ginrpc) - Gin parameter automatic binding tool,gin rpc tools.
- <code>&nbsp;&nbsp;&nbsp;181</code> [hiboot](https://github.com/hidevopsio/hiboot) - hiboot is a high performance web application framework with auto configuration and dependency injection support.
- <code>&nbsp;&nbsp;&nbsp;131</code> [Gone](https://github.com/gone-io/gone) - A lightweight dependency injection and web framework inspired by Spring.
- <code>&nbsp;&nbsp;&nbsp;126</code> [patron](https://github.com/beatlabs/patron) - Patron is a microservice framework following best cloud practices with a focus on productivity.
- <code>&nbsp;&nbsp;&nbsp;118</code> [Microservice](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;97</code> [rux](https://github.com/gookit/rux) - Simple and fast web framework for build golang HTTP applications.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> [Don](https://github.com/abemedia/go-don) - A highly performant and simple to use API framework.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;34</code> [Ronykit](https://github.com/clubpay/ronykit) - Web framework with pluggable architecture and very performant.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;30</code> [Lit](https://github.com/jvcoutinho/lit) - Highly performant declarative web framework for Golang, aiming for simplicity and quality of life.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [golamb](https://github.com/twharmon/golamb) - Golamb makes it easier to write API endpoints for use with AWS Lambda and API Gateway.
- [Pnutmux](https://gitlab.com/fruitygo/pnutmux) - Pnutmux is a powerful Go web framework that uses regex for matching and handling HTTP requests. It offers features such as CORS handling, structured logging, URL parameters extraction, middlewares, and concurrency limiting.
- [Confetti Framework](https://confetti-framework.github.io/docs/) - Confetti is a Go web application framework with an expressive, elegant syntax. Confetti combines the elegance of Laravel and the simplicity of Go.

**[⬆ back to top](#contents)**

### Middlewares

#### Actual middlewares

- <code>&nbsp;&nbsp;2811</code> [Tollbooth](https://github.com/didip/tollbooth) - Rate limit HTTP request handler.
- <code>&nbsp;&nbsp;2805</code> [CORS](https://github.com/rs/cors) - Easily add CORS capabilities to your API.
- <code>&nbsp;&nbsp;2252</code> [Limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go.
- <code>&nbsp;&nbsp;&nbsp;860</code> [go-server-timing](https://github.com/mitchellh/go-server-timing) - Add/parse Server-Timing header.
- <code>&nbsp;&nbsp;&nbsp;509</code> [go-fault](https://github.com/github/go-fault) - Fault injection middleware for Go.
- <code>&nbsp;&nbsp;&nbsp;155</code> [ln-paywall](https://github.com/philippgille/ln-paywall) - Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin).
- <code>&nbsp;&nbsp;&nbsp;100</code> [XFF](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;78</code> [rk-grpc](https://github.com/rookie-ninja/rk-grpc) - Middleware for gRPC with logging, metrics, auth, tracing etc.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> [rk-gin](https://github.com/rookie-ninja/rk-gin) - Middleware for Gin framework with logging, metrics, auth, tracing etc.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> [formjson](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> [client-timing](https://github.com/posener/client-timing) - An HTTP client for Server-Timing header.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [echo-middleware](https://github.com/faabiosr/echo-middleware) - Middleware for Echo framework with logging and metrics.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [mid](https://github.com/bobg/mid) - Miscellaneous HTTP middleware features: idiomatic error return from handlers; receive/respond with JSON data; request tracing; and more.

#### Libraries for creating HTTP middlewares

- <code>&nbsp;&nbsp;7532</code> [negroni](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang.
- <code>&nbsp;&nbsp;3287</code> [alice](https://github.com/justinas/alice) - Painless middleware chaining for Go.
- <code>&nbsp;&nbsp;1971</code> [render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses.
- <code>&nbsp;&nbsp;&nbsp;593</code> [stats](https://github.com/thoas/stats) - Go middleware that stores various information about your web application.
- <code>&nbsp;&nbsp;&nbsp;293</code> [interpose](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang.
- <code>&nbsp;&nbsp;&nbsp;262</code> [renderer](https://github.com/thedevsaddam/renderer) - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go.
- <code>&nbsp;&nbsp;&nbsp;206</code> [muxchain](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http.
- <code>&nbsp;&nbsp;&nbsp;106</code> [gores](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs.
- <code>&nbsp;&nbsp;&nbsp;100</code> [rye](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;88</code> [mediary](https://github.com/HereMobilityDevelopers/mediary) - add interceptors to `http.Client` to allow dumping/shaping/tracing/... of requests/responses.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;61</code> [chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware").
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> [catena](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain").

**[⬆ back to top](#contents)**

### Routers

- <code>&nbsp;21507</code> [mux](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang.
- <code>&nbsp;20239</code> [chi](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context.
- <code>&nbsp;16947</code> [httprouter](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework.
- <code>&nbsp;&nbsp;1514</code> [gocraft/web](https://github.com/gocraft/web) - Mux and middleware package in Go.
- <code>&nbsp;&nbsp;1287</code> [Bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer.
- <code>&nbsp;&nbsp;&nbsp;971</code> [Goji](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`.
- <code>&nbsp;&nbsp;&nbsp;871</code> [fasthttprouter](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`.
- <code>&nbsp;&nbsp;&nbsp;619</code> [httptreemux](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter.
- <code>&nbsp;&nbsp;&nbsp;529</code> [xujiajun/gorouter](https://github.com/xujiajun/gorouter) - A simple and fast HTTP router for Go.
- <code>&nbsp;&nbsp;&nbsp;456</code> [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs.
- <code>&nbsp;&nbsp;&nbsp;384</code> [lars](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks.
- <code>&nbsp;&nbsp;&nbsp;348</code> [Siesta](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers.
- <code>&nbsp;&nbsp;&nbsp;267</code> [vestigo](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications.
- <code>&nbsp;&nbsp;&nbsp;185</code> [gowww/router](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface.
- <code>&nbsp;&nbsp;&nbsp;153</code> [GoRouter](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`.
- <code>&nbsp;&nbsp;&nbsp;150</code> [pure](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation.
- <code>&nbsp;&nbsp;&nbsp;135</code> [alien](https://github.com/gernest/alien) - Lightweight and fast http router from outer space.
- <code>&nbsp;&nbsp;&nbsp;108</code> [violetear](https://github.com/nbari/violetear) - Go HTTP router.
- <code>&nbsp;&nbsp;&nbsp;101</code> [Bxog](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;99</code> [xmux](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;81</code> [goblin](https://github.com/bmf-san/goblin) - A golang http router based on trie tree.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;71</code> [ngamux](https://github.com/ngamux/ngamux) - Simple HTTP router for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> [bellt](https://github.com/GuilhermeCaruso/bellt) - A simple Go HTTP router.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> [FastRouter](https://github.com/razonyang/fastrouter) - a fast, flexible HTTP router written in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> [GoLobby/Router](https://github.com/golobby/router) - GoLobby Router is a lightweight yet powerful HTTP router for the Go programming language.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> [nchi](https://github.com/muir/nchi) - chi-like router built on httprouter with dependency injection based middleware wrappers
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> [goroute](https://github.com/goroute/route) - Simple yet powerful HTTP request multiplexer.

**[⬆ back to top](#contents)**

## WebAssembly

- <code>&nbsp;16512</code> [tinygo](https://github.com/tinygo-org/tinygo) - Go compiler for small places. Microcontrollers, WebAssembly, and command-line tools. Based on LLVM.
- <code>&nbsp;&nbsp;&nbsp;497</code> [dom](https://github.com/dennwc/dom) - DOM library.
- <code>&nbsp;&nbsp;&nbsp;264</code> [go-canvas](https://github.com/markfarnan/go-canvas) - Library to use HTML5 Canvas, with all drawing within go code.
- <code>&nbsp;&nbsp;&nbsp;200</code> [wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) - Run Go WASM tests in your browser.
- <code>&nbsp;&nbsp;&nbsp;179</code> [webapi](https://github.com/gowebapi/webapi) - Bindings for DOM and HTML generated from WebIDL.
- <code>&nbsp;&nbsp;&nbsp;126</code> [Extism Go SDK](https://github.com/extism/go-sdk) - Universal, cross-language WebAssembly framework for building plug-in systems and polyglot apps.
- <code>&nbsp;&nbsp;&nbsp;104</code> [vert](https://github.com/norunners/vert) - Interop between Go and JS values.

**[⬆ back to top](#contents)**

## Webhooks Server

- <code>&nbsp;11103</code> [webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.
- <code>&nbsp;&nbsp;&nbsp;236</code> [WebhookX](https://github.com/webhookx-io/webhookx) - A webhooks gateway for message receiving, processing, and reliable delivering.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> [webhooked](https://github.com/42Atomys/webhooked) - A webhook receiver on steroids: handle, secure, format and store a Webhook payload has never been easier.

**[⬆ back to top](#contents)**

## Windows

- <code>&nbsp;&nbsp;1256</code> [go-ole](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang.
- <code>&nbsp;&nbsp;&nbsp;161</code> [d3d9](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> [gosddl](https://github.com/MonaxGT/gosddl) - Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL.

**[⬆ back to top](#contents)**

## Workflow Frameworks

*Libraries for creating Workflows.*

- <code>&nbsp;&nbsp;2471</code> [Dagu](https://github.com/dagu-go/dagu) - No-code workflow executor. it executes DAGs defined in a simple YAML format.
- <code>&nbsp;&nbsp;&nbsp;564</code> [go-taskflow](https://github.com/noneback/go-taskflow) - A taskflow-like General-purpose Task-parallel Programming Framework with integrated visualizer and profiler.
- <code>&nbsp;&nbsp;&nbsp;362</code> [Cadence-client](https://github.com/uber-go/cadence-client) - A framework for authoring workflows and activities running on top of the Cadence orchestration engine made by Uber.
- <code>&nbsp;&nbsp;&nbsp;181</code> [workflow](https://github.com/luno/workflow) - A tech stack agnostic Event Driven Workflow framework.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> [go-dag](https://github.com/rhosocial/go-dag) - A framework developed in Go that manages the execution of workflows described by directed acyclic graphs.

**[⬆ back to top](#contents)**

## XML

*Libraries and tools for manipulating XML.*

- <code>&nbsp;&nbsp;&nbsp;771</code> [zek](https://github.com/miku/zek) - Generate a Go struct from XML.
- <code>&nbsp;&nbsp;&nbsp;724</code> [xpath](https://github.com/antchfx/xpath) - XPath package for Go.
- <code>&nbsp;&nbsp;&nbsp;475</code> [xmlquery](https://github.com/antchfx/xmlquery) - xmlquery is Golang XPath package for XML query.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;64</code> [xml2map](https://github.com/sbabiv/xml2map) - XML to MAP converter written Golang.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> [XML-Comp](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags.

## Zero Trust

*Libraries and tools to implement Zero Trust architectures.*

- <code>&nbsp;&nbsp;5104</code> [Cosign](https://github.com/sigstore/cosign) - Container Signing, Verification and Storage in an OCI registry.
- <code>&nbsp;&nbsp;3483</code> [OpenZiti](https://github.com/openziti/ziti) - A full, open source zero trust overlay network. Including numerous SDKs for numerous languages such as <code>&nbsp;&nbsp;&nbsp;109</code> [golang](https://github.com/openziti/sdk-golang) allowing you to embed zero trust principles directly into your applications. The [OpenZiti Test Kitchen](https://github.com/openziti-test-kitchen) has numerous examples to draw inspiration from including a <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> [zero trust ssh client - zssh](https://github.com/openziti-test-kitchen/zssh)
- <code>&nbsp;&nbsp;2009</code> [Spire](https://github.com/spiffe/spire) - SPIRE (the SPIFFE Runtime Environment) is a toolchain of APIs for establishing trust between software systems across a wide variety of hosting platforms.
- <code>&nbsp;&nbsp;&nbsp;140</code> [in-toto](https://github.com/in-toto/in-toto-golang) - Go implementation of the in-toto (provides a framework to protect the integrity of the software supply chain) python reference implementation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;90</code> [Spiffe-Vault](https://github.com/philips-labs/spiffe-vault) - Utilizes Spiffe JWT authentication with Hashicorp Vault for secretless authentication.

## Code Analysis

*Source code analysis tools, also known as Static Application Security Testing (SAST) Tools.*

- <code>&nbsp;17410</code> [golangci-lint](https://github.com/golangci/golangci-lint) – A fast Go linters runner. It runs linters in parallel, uses caching, supports `yaml` config, has integrations with all major IDE and has dozens of linters included.
- <code>&nbsp;&nbsp;6528</code> [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
- <code>&nbsp;&nbsp;5266</code> [revive](https://github.com/mgechev/revive) – ~6x faster, stricter, configurable, extensible, and beautiful drop-in replacement for `golint`.
- <code>&nbsp;&nbsp;2434</code> [errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs.
- <code>&nbsp;&nbsp;2032</code> [GoPlantUML](https://github.com/jfeliu007/goplantuml) - Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them.
- <code>&nbsp;&nbsp;1974</code> [go-critic](https://github.com/go-critic/go-critic) - source code linter that brings checks that are currently not implemented in other linters.
- <code>&nbsp;&nbsp;1090</code> [golines](https://github.com/segmentio/golines) - Formatter that automatically shortens long lines in Go code.
- <code>&nbsp;&nbsp;&nbsp;955</code> [php-parser](https://github.com/z7zmey/php-parser) - A Parser for PHP written in Go.
- <code>&nbsp;&nbsp;&nbsp;954</code> [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects.
- <code>&nbsp;&nbsp;&nbsp;811</code> [vacuum](https://github.com/daveshanley/vacuum) - An ultra-super-fast, lightweight OpenAPI linter and quality checking tool.
- <code>&nbsp;&nbsp;&nbsp;784</code> [goast-viewer](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer.
- <code>&nbsp;&nbsp;&nbsp;662</code> [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) - An easy way to find outdated dependencies of your Go projects.
- <code>&nbsp;&nbsp;&nbsp;534</code> [goreturns](https://github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
- <code>&nbsp;&nbsp;&nbsp;435</code> [Chronos](https://github.com/amit-davidson/Chronos) - Detects race conditions statically
- <code>&nbsp;&nbsp;&nbsp;434</code> [todocheck](https://github.com/preslavmihaylov/todocheck) - Static code analyser which links TODO comments in code with issues in your issue tracker.
- <code>&nbsp;&nbsp;&nbsp;384</code> [unconvert](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source.
- <code>&nbsp;&nbsp;&nbsp;352</code> [dupl](https://github.com/mibk/dupl) - Tool for code clone detection.
- <code>&nbsp;&nbsp;&nbsp;344</code> [wrapcheck](https://github.com/tomarrell/wrapcheck) - A linter to check that errors from external packages are wrapped.
- <code>&nbsp;&nbsp;&nbsp;324</code> [tickgit](https://github.com/augmentable-dev/tickgit) - CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author.
- <code>&nbsp;&nbsp;&nbsp;244</code> [gostatus](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages.
- <code>&nbsp;&nbsp;&nbsp;180</code> [apicompat](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes.
- <code>&nbsp;&nbsp;&nbsp;147</code> [testifylint](https://github.com/Antonboom/testifylint) – A linter that checks usage of <code>&nbsp;24976</code> [github.com/stretchr/testify](https://github.com/stretchr/testify).
- <code>&nbsp;&nbsp;&nbsp;131</code> [go-checkstyle](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;88</code> [asty](https://github.com/asty-org/asty) - Converts golang AST to JSON and JSON to AST.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;65</code> [lint](https://github.com/surullabs/lint) - Run linters as part of go test.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;62</code> [validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;58</code> [ChainJacking](https://github.com/Checkmarx/chainjacking) - Find which of your Go lang direct GitHub dependencies is susceptible to ChainJacking attack.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> [fatcontext](https://github.com/Crocmagnon/fatcontext) - Fatcontext detects nested contexts in loops or function literals.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> [usestdlibvars](https://github.com/sashamelentyev/usestdlibvars) - A linter that detect the possibility to use variables/constants from the Go standard library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [golang-ifood-sdk](https://github.com/arxdsilva/golang-ifood-sdk) - iFood API SDK.
- [goimports](https://pkg.go.dev/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
- [blanket](https://gitlab.com/verygoodsoftwarenotvirus/blanket) - blanket is a tool that helps you catch functions which don't have direct unit tests in your Go packages.

**[⬆ back to top](#contents)**

## Editor Plugins

*Plugin for text editors and IDEs.*

- <code>&nbsp;16157</code> [vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim.
- <code>&nbsp;&nbsp;5006</code> [gocode](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language.
- <code>&nbsp;&nbsp;4095</code> [vscode-go](https://github.com/golang/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language.
- <code>&nbsp;&nbsp;3420</code> [GoSublime](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features.
- <code>&nbsp;&nbsp;1424</code> [go-mode](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs.
- <code>&nbsp;&nbsp;&nbsp;679</code> [goimports-reviser](https://github.com/incu6us/goimports-reviser) - Formatting tool for imports.
- <code>&nbsp;&nbsp;&nbsp;576</code> [coc-go language server extension for Vim/Neovim](https://github.com/josa42/coc-go) - This plugin adds <code>&nbsp;&nbsp;7764</code> [gopls](https://github.com/golang/tools/blob/master/gopls/README.md) features to Vim/Neovim.
- <code>&nbsp;&nbsp;&nbsp;202</code> [Watch](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;90</code> [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> [gounit-vim](https://github.com/hexdigest/gounit-vim) - Vim plugin for generating Go tests based on the function's or method's signature.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> [Go Doc](https://github.com/msyrus/vscode-go-doc) - A Visual Studio Code extension for showing definition in output and generating go doc.
- [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) - This extension adds benchmark profiling support for the Go language to VS Code.
- [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.

**[⬆ back to top](#contents)**

## Go Generate Tools

- <code>&nbsp;&nbsp;5093</code> [gotests](https://github.com/cweill/gotests) - Generate Go tests from your source code.
- <code>&nbsp;&nbsp;&nbsp;377</code> [xgen](https://github.com/xuri/xgen) - XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator.
- <code>&nbsp;&nbsp;&nbsp;143</code> [hasgo](https://github.com/DylanMeeus/hasgo) - Generate Haskell inspired functions for your slices.
- <code>&nbsp;&nbsp;&nbsp;114</code> [gocontracts](https://github.com/Parquery/gocontracts) - brings design-by-contract to Go by synchronizing the code with the documentation.
- <code>&nbsp;&nbsp;&nbsp;113</code> [gonerics](https://github.com/bouk/gonerics) - Idiomatic Generics in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;96</code> [options-gen](https://github.com/kazhuravlev/options-gen) - Functional options described by Dave Cheney's post "Functional options for friendly APIs".
- <code>&nbsp;&nbsp;&nbsp;&nbsp;88</code> [envdoc](https://github.com/g4s8/envdoc) - generate documentation for environment variables from Go source files.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> [sqlgen](https://github.com/anqiansong/sqlgen) - Generate gorm, xorm, sqlx, bun, sql code from SQL file or DSN.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> [gounit](https://github.com/hexdigest/gounit) - Generate Go tests using your own templates.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;49</code> [generic](https://github.com/usk81/generic) - flexible data type for Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> [godal](https://github.com/mafulong/godal) - Generate orm models corresponding to golang by specifying sql ddl file, which can be used by gorm.
- [TOML-to-Go](https://xuri.me/toml-to-go) - Translates TOML into a Go type in the browser instantly.
- [re2dfa](https://gitlab.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code.

**[⬆ back to top](#contents)**

## Go Tools

- <code>&nbsp;&nbsp;9809</code> [go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API.
- <code>&nbsp;&nbsp;6339</code> [go-callvis](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format.
- <code>&nbsp;&nbsp;5323</code> [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.
- <code>&nbsp;&nbsp;1643</code> [go-size-analyzer](https://github.com/Zxilly/go-size-analyzer) - Analyze and visualize the size of dependencies in compiled Golang binaries, providing insight into their impact on the final build.
- <code>&nbsp;&nbsp;&nbsp;862</code> [richgo](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations.
- <code>&nbsp;&nbsp;&nbsp;275</code> [MoniGO](https://github.com/iyashjayesh/monigo) - A performance monitoring library for Go applications. It provides real-time insights into application performance! 🚀
- <code>&nbsp;&nbsp;&nbsp;251</code> [rts](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses.
- <code>&nbsp;&nbsp;&nbsp;220</code> [roumon](https://github.com/becheran/roumon) - Monitor current state of all active goroutines via a command line interface.
- <code>&nbsp;&nbsp;&nbsp;206</code> [godbg](https://github.com/tylerwince/godbg) - Implementation of Rusts `dbg!` macro for quick and easy debugging during development.
- <code>&nbsp;&nbsp;&nbsp;205</code> [typex](https://github.com/dtgorski/typex) - Examine Go types and their transitive dependencies, alternatively export results as TypeScript value objects (or types) declaration.
- <code>&nbsp;&nbsp;&nbsp;146</code> [gotestdox](https://github.com/bitfield/gotestdox) - Show Go test results as readable sentences.
- <code>&nbsp;&nbsp;&nbsp;128</code> [gothanks](https://github.com/psampaz/gothanks) - GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;68</code> [igo](https://github.com/rocketlaunchr/igo) - An igo to go transpiler (new language features for Go language!)
- <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> [gotutor](https://github.com/ahmedakef/gotutor) - Online Go Debugger & Visualizer.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;46</code> [docs](https://github.com/go-oas/docs) - Automatically generate RESTful API documentation for GO projects - aligned with Open API Specification standard.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> [gomodrun](https://github.com/dustinblackman/gomodrun/) - Go tool that executes and caches binaries included in go.mod files.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> [decouple](https://github.com/bobg/decouple) - Find “overspecified” function parameters that could be generalized with interface types.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> [modver](https://github.com/bobg/modver) - Compare two versions of a Go module to check the version-number change required (major, minor, or patchlevel), according to [semver](https://semver.org/) rules.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> [textra](https://github.com/ravsii/textra) - Extract Go struct field names, types and tags for filtering and exporting.
- [gotemplate.io](https://gotemplate.io/) - Online tool to preview `text/template` templates live.
- [go-template-playground](https://bartventer.github.io/go-template-playground/) - An interactive environment to create and test Go templates.

**[⬆ back to top](#contents)**

## Software Packages

*Software written in Go.*

**[⬆ back to top](#contents)**

### DevOps Tools

- <code>116646</code> [kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google.
- <code>&nbsp;70413</code> [Moby](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems.
- <code>&nbsp;55838</code> [traefik](https://github.com/containous/traefik) - Reverse proxy and load balancer with support for multiple backends.
- <code>&nbsp;49838</code> [Gitea](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven.
- <code>&nbsp;30749</code> [minikube](https://github.com/kubernetes/minikube) - Run Kubernetes locally.
- <code>&nbsp;30347</code> [k3s](https://github.com/k3s-io/k3s) - Lightweight Kubernetes.
- <code>&nbsp;28411</code> [k6](https://github.com/grafana/k6) - A modern load testing tool, using Go and JavaScript.
- <code>&nbsp;24414</code> [Vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000!
- <code>&nbsp;19122</code> [Hey](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application.
- <code>&nbsp;15421</code> [Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
- <code>&nbsp;14382</code> [kind](https://github.com/kubernetes-sigs/kind) - Kubernetes IN Docker - local clusters for testing Kubernetes.
- <code>&nbsp;11452</code> [kubeshark](https://github.com/kubeshark/kubeshark) - API traffic analyzer for Kubernetes, inspired by Wireshark, purposely built for Kubernetes.
- <code>&nbsp;11133</code> [GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions.
- <code>&nbsp;&nbsp;9204</code> [Flannel](https://github.com/flannel-io/flannel) - Flannel is a network fabric for containers, designed for Kubernetes.
- <code>&nbsp;&nbsp;8485</code> [Ddosify](https://github.com/ddosify/ddosify) - High-performance load testing tool, written in Golang.
- <code>&nbsp;&nbsp;8087</code> [ko](https://github.com/google/ko) - Command line tool for building and deploying Go applications on Kubernetes
- <code>&nbsp;&nbsp;6793</code> [script](https://github.com/bitfield/script) - Making it easy to write shell-like scripts in Go for DevOps and system administration tasks.
- <code>&nbsp;&nbsp;6781</code> [KubeVela](https://github.com/kubevela/kubevela) - Cloud native application delivery.
- <code>&nbsp;&nbsp;6451</code> [bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool.
- <code>&nbsp;&nbsp;5939</code> [k3d](https://github.com/k3d-io/k3d) - Little helper to run CNCF's k3s in Docker.
- <code>&nbsp;&nbsp;5668</code> [podinfo](https://github.com/stefanprodan/podinfo) - Podinfo is a tiny web application made with Go that showcases best practices of running microservices in Kubernetes. Podinfo is used by CNCF projects like Flux and Flagger for end-to-end testing and workshops.
- <code>&nbsp;&nbsp;5326</code> [Fleet device management](https://github.com/fleetdm/fleet) - Lightweight, programmable telemetry for servers and workstations.
- <code>&nbsp;&nbsp;5231</code> [gaia](https://github.com/gaia-pipeline/gaia) - Build powerful pipelines in any programming language.
- <code>&nbsp;&nbsp;4368</code> [Pomerium](https://github.com/pomerium/pomerium) - Pomerium is an identity-aware access proxy.
- <code>&nbsp;&nbsp;4221</code> [tau](https://github.com/taubyte/tau) - Easily build Cloud Computing Platforms with features like Serverless WebAssembly Functions, Frontend Hosting, CI/CD, Object Storage, K/V Database, and Pub-Sub Messaging.
- <code>&nbsp;&nbsp;3491</code> [s5cmd](https://github.com/peak/s5cmd) - Blazing fast S3 and local filesystem execution tool.
- <code>&nbsp;&nbsp;3414</code> [bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework.
- <code>&nbsp;&nbsp;2769</code> [kubeblocks](https://github.com/apecloud/kubeblocks) - KubeBlocks is an open-source control plane that runs and manages databases, message queues and other data infrastructure on K8s.
- <code>&nbsp;&nbsp;2678</code> [aptly](https://github.com/aptly-dev/aptly) - aptly is a Debian repository management tool.
- <code>&nbsp;&nbsp;2155</code> [kala](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler.
- <code>&nbsp;&nbsp;1853</code> [fac](https://github.com/mkchoi212/fac) - Command-line user interface to fix git merge conflicts.
- <code>&nbsp;&nbsp;1785</code> [ghorg](https://github.com/gabrie30/ghorg) - Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, Gitea, and Bitbucket.
- <code>&nbsp;&nbsp;1629</code> [StatusOK](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected.
- <code>&nbsp;&nbsp;1624</code> [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update.
- <code>&nbsp;&nbsp;1441</code> [tlm](https://github.com/yusufcanb/tlm) - Local cli copilot, powered by CodeLLaMa
- <code>&nbsp;&nbsp;1300</code> [uTask](https://github.com/ovh/utask) - Automation engine that models and executes business processes declared in yaml.
- <code>&nbsp;&nbsp;1203</code> [PipeCD](https://github.com/pipe-cd/pipecd) - A GitOps-style continuous delivery platform that provides consistent deployment and operations experience for any applications.
- <code>&nbsp;&nbsp;1193</code> [KubeVPN](https://github.com/kubenetworks/kubevpn) - KubeVPN offers a Cloud-Native Dev Environment that seamlessly connects to your Kubernetes cluster network.
- <code>&nbsp;&nbsp;1153</code> [KusionStack](https://github.com/KusionStack/kusion) - A unified programmable configuration techstack to deliver modern app in 'platform as code' and 'infra as code' approach.
- <code>&nbsp;&nbsp;1142</code> [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.
- <code>&nbsp;&nbsp;&nbsp;986</code> [kwatch](https://github.com/abahmed/kwatch) - Monitor & detect crashes in your Kubernetes(K8s) cluster instantly.
- <code>&nbsp;&nbsp;&nbsp;980</code> [skm](https://github.com/TimothyYe/skm) - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily!
- <code>&nbsp;&nbsp;&nbsp;926</code> [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker).
- <code>&nbsp;&nbsp;&nbsp;804</code> [cassowary](https://github.com/rogerwelin/cassowary) - Modern cross-platform HTTP load-testing tool written in Go.
- <code>&nbsp;&nbsp;&nbsp;698</code> [alaz](https://github.com/ddosify/alaz) - Effortless, Low-Overhead, eBPF-based Kubernetes Monitoring.
- <code>&nbsp;&nbsp;&nbsp;691</code> [kool](https://github.com/kool-dev/kool) - Command line tool for managing Docker environments as an easy way.
- <code>&nbsp;&nbsp;&nbsp;601</code> [aurora](https://github.com/xuri/aurora) - Cross-platform web-based Beanstalkd queue server console.
- <code>&nbsp;&nbsp;&nbsp;539</code> [govvv](https://github.com/ahmetalpbalkan/govvv) - “go build” wrapper to easily add version information into Go binaries.
- <code>&nbsp;&nbsp;&nbsp;437</code> [Pewpew](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester.
- <code>&nbsp;&nbsp;&nbsp;405</code> [jcli](https://github.com/jenkins-zh/jenkins-cli) - Jenkins CLI allows you manage your Jenkins as an easy way.
- <code>&nbsp;&nbsp;&nbsp;397</code> [gobrew](https://github.com/kevincobain2000/gobrew) - Go version manager. Super simple tool to install and manage Go versions. Install go without root. Gobrew doesn't require shell rehash.
- <code>&nbsp;&nbsp;&nbsp;377</code> [s3-proxy](https://github.com/oxyno-zeta/s3-proxy) - S3 Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth).
- <code>&nbsp;&nbsp;&nbsp;338</code> [gonative](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.
- <code>&nbsp;&nbsp;&nbsp;337</code> [lstags](https://github.com/ivanilves/lstags) - Tool and API to sync Docker images across different registries.
- <code>&nbsp;&nbsp;&nbsp;336</code> [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`.
- <code>&nbsp;&nbsp;&nbsp;334</code> [trubka](https://github.com/xitonix/trubka) - A CLI tool to manage and troubleshoot Apache Kafka clusters with the ability of generically publishing/consuming protocol buffer and plain text events to/from Kafka.
- <code>&nbsp;&nbsp;&nbsp;316</code> [Mora](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data.
- <code>&nbsp;&nbsp;&nbsp;306</code> [Balerter](https://github.com/balerter/balerter) - A self-hosted script-based alerting manager.
- <code>&nbsp;&nbsp;&nbsp;300</code> [manssh](https://github.com/xwjdsh/manssh) - manssh is a command line tool for managing your ssh alias config easily.
- <code>&nbsp;&nbsp;&nbsp;278</code> [terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) - Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed.
- <code>&nbsp;&nbsp;&nbsp;272</code> [dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart).
- <code>&nbsp;&nbsp;&nbsp;246</code> [dish](https://github.com/thevxn/dish) - A lightweight, remotely configurable monitoring service.
- <code>&nbsp;&nbsp;&nbsp;228</code> [godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application.
- <code>&nbsp;&nbsp;&nbsp;222</code> [abbreviate](https://github.com/dnnrly/abbreviate) - abbreviate is a tool turning long strings in to shorter ones with configurable separators, for example to embed branch names in to deployment stack IDs.
- <code>&nbsp;&nbsp;&nbsp;220</code> [Blast](https://github.com/dave/blast) - A simple tool for API load testing and batch jobs.
- <code>&nbsp;&nbsp;&nbsp;220</code> [kcli](https://github.com/cswank/kcli) - Command line tool for inspecting kafka topics/partitions/messages.
- <code>&nbsp;&nbsp;&nbsp;191</code> [gobrew](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go.
- <code>&nbsp;&nbsp;&nbsp;180</code> [ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB.
- <code>&nbsp;&nbsp;&nbsp;177</code> [Dockerfile-Generator](https://github.com/ozankasikci/dockerfile-generator) - A go library and an executable that produces valid Dockerfiles using various input channels.
- <code>&nbsp;&nbsp;&nbsp;169</code> [grapes](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease.
- <code>&nbsp;&nbsp;&nbsp;168</code> [winrm-cli](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines.
- <code>&nbsp;&nbsp;&nbsp;158</code> [tf-profile](https://github.com/datarootsio/tf-profile) - Profiler for Terraform runs. Generate global stats, resource-level stats or visualizations.
- <code>&nbsp;&nbsp;&nbsp;156</code> [drone-scp](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI.
- <code>&nbsp;&nbsp;&nbsp;114</code> [Mantil](https://github.com/mantil-io/mantil) - Go specific framework for building serverless applications on AWS that enables you to focus on pure Go code while Mantil takes care of the infrastructure.
- <code>&nbsp;&nbsp;&nbsp;107</code> [go-rocket-update](https://github.com/mouuff/go-rocket-update) - A simple way to make self updating Go applications - Supports Github and Gitlab.
- <code>&nbsp;&nbsp;&nbsp;107</code> [decompose](https://github.com/s0rg/decompose) - tool to generate and process Docker containers connections graphs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;99</code> [go-furnace](https://github.com/go-furnace/go-furnace) - Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;66</code> [Dropship](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;52</code> [docker-go-mingw](https://github.com/x1unix/docker-go-mingw) - Docker image for building Go binaries for Windows with MinGW toolchain.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> [httpref](https://github.com/dnnrly/httpref) - httpref is a handy CLI reference for HTTP methods, status codes, headers, and TCP and UDP ports.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> [drone-jenkins](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> [awsenv](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> [Rodent](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;32</code> [lwc](https://github.com/timdp/lwc) - A live-updating version of the UNIX wc command.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> [DepCharge](https://github.com/centerorbit/depcharge) - Helps orchestrating the execution of commands across the many dependencies in larger projects.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> [wait-for](https://github.com/dnnrly/wait-for) - Wait for something to happen (from the command line) before continuing. Easy orchestration of Docker services and other things.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code> [sg](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response.
- [Docker](https://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
- [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) - Migrate all your GitHub repositories, issues, milestones and labels to your Gitea instance.
- [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
- [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.

**[⬆ back to top](#contents)**

### Other Software

- <code>&nbsp;30702</code> [croc](https://github.com/schollz/croc) - Easily and securely send files or folders from one computer to another.
- <code>&nbsp;29477</code> [restic](https://github.com/restic/restic) - De-duplicating backup program.
- <code>&nbsp;25364</code> [Seaweed File System](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek.
- <code>&nbsp;19030</code> [Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.
- <code>&nbsp;11980</code> [JuiceFS](https://github.com/juicedata/juicefs) - Distributed POSIX file system built on top of Redis and AWS S3.
- <code>&nbsp;11383</code> [toxiproxy](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests.
- <code>&nbsp;10419</code> [Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections.
- <code>&nbsp;&nbsp;8407</code> [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul.
- <code>&nbsp;&nbsp;7703</code> [LiteIDE](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE.
- <code>&nbsp;&nbsp;7534</code> [scc](https://github.com/boyter/scc) - Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates.
- <code>&nbsp;&nbsp;6723</code> [drive](https://github.com/odeke-em/drive) - Google Drive client for the commandline.
- <code>&nbsp;&nbsp;5585</code> [nes](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go.
- <code>&nbsp;&nbsp;5499</code> [blocky](https://github.com/0xERR0R/blocky) - Fast and lightweight DNS proxy as ad-blocker for local network with many features.
- <code>&nbsp;&nbsp;5484</code> [Duplicacy](https://github.com/gilbertchen/duplicacy) - A cross-platform network and cloud backup tool based on the idea of lock-free deduplication.
- <code>&nbsp;&nbsp;2718</code> [myLG](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go.
- <code>&nbsp;&nbsp;2632</code> [GoBoy](https://github.com/Humpheh/goboy) - Nintendo Game Boy Color emulator written in Go.
- <code>&nbsp;&nbsp;2507</code> [Stack Up](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers.
- <code>&nbsp;&nbsp;2460</code> [lgo](https://github.com/yunabe/lgo) - Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility.
- <code>&nbsp;&nbsp;2277</code> [Documize](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools.
- <code>&nbsp;&nbsp;2178</code> [Gokapi](https://github.com/Forceu/gokapi) - Lightweight server to share files, which expire after a set amount of downloads or days. Similar to Firefox Send, but without public upload.
- <code>&nbsp;&nbsp;2094</code> [sonic](https://github.com/go-sonic/sonic) - Sonic is a Go Blogging Platform. Simple and Powerful.
- <code>&nbsp;&nbsp;1988</code> [Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
- <code>&nbsp;&nbsp;1672</code> [portal](https://github.com/SpatiumPortae/portal) - Portal is a quick and easy command-line file transfer utility from any computer to another.
- <code>&nbsp;&nbsp;1610</code> [borg](https://github.com/crufter/borg) - Terminal based search engine for bash snippets.
- <code>&nbsp;&nbsp;1600</code> [Plik](https://github.com/root-gg/plik) - Plik is a temporary file upload system (Wetransfer like) in Go.
- <code>&nbsp;&nbsp;1423</code> [shell2http](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control).
- <code>&nbsp;&nbsp;1130</code> [vFlow](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector.
- <code>&nbsp;&nbsp;1066</code> [peg](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator.
- <code>&nbsp;&nbsp;&nbsp;897</code> [Go Package Store](https://github.com/shurcooL/Go-Package-Store) - App that displays updates for the Go packages in your GOPATH.
- <code>&nbsp;&nbsp;&nbsp;894</code> [GoNB](https://github.com/janpfeifer/gonb) - Interactive Go programming with Jupyter Notebooks (also works in VSCode, Binder and Google's Colab).
- <code>&nbsp;&nbsp;&nbsp;815</code> [yai](https://github.com/ekkinox/yai) - AI powered terminal assistant.
- <code>&nbsp;&nbsp;&nbsp;756</code> [Leaps](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms.
- <code>&nbsp;&nbsp;&nbsp;752</code> [gfile](https://github.com/Antonito/gfile) - Securely transfer files between two computers, without any third party, over WebRTC.
- <code>&nbsp;&nbsp;&nbsp;702</code> [sake](https://github.com/alajmo/sake) - sake is a command runner for local and remote hosts.
- <code>&nbsp;&nbsp;&nbsp;675</code> [Guora](https://github.com/meloalright/guora) - A self-hosted Quora like web application written in Go.
- <code>&nbsp;&nbsp;&nbsp;644</code> [gocc](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go.
- <code>&nbsp;&nbsp;&nbsp;632</code> [Gebug](https://github.com/moshebe/gebug) - A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly.
- <code>&nbsp;&nbsp;&nbsp;601</code> [Chapar](https://github.com/chapar-rest/chapar) - Chapar is a a cross-platform Postman alternative built with go, aims to help developers to test their api endpoints. it support http and grpc protocols.
- <code>&nbsp;&nbsp;&nbsp;564</code> [mockingjay](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests.
- <code>&nbsp;&nbsp;&nbsp;490</code> [woke](https://github.com/get-woke/woke) - Detect non-inclusive language in your source code.
- <code>&nbsp;&nbsp;&nbsp;473</code> [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client.
- <code>&nbsp;&nbsp;&nbsp;398</code> [hotswap](https://github.com/edwingeng/hotswap) - A complete solution to reload your go code without restarting your server, interrupting or blocking any ongoing procedure.
- <code>&nbsp;&nbsp;&nbsp;361</code> [ide](https://github.com/thestrukture/ide) - Browser accessible IDE. Designed for Go with Go.
- <code>&nbsp;&nbsp;&nbsp;332</code> [Neo-cowsay](https://github.com/Code-Hex/Neo-cowsay) - 🐮 cowsay is reborn. for a New Era.
- <code>&nbsp;&nbsp;&nbsp;303</code> [crawley](https://github.com/s0rg/crawley) - Web scraper/crawler for cli.
- <code>&nbsp;&nbsp;&nbsp;302</code> [wellington](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass).
- <code>&nbsp;&nbsp;&nbsp;301</code> [Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go.
- <code>&nbsp;&nbsp;&nbsp;279</code> [stew](https://github.com/marwanhawari/stew) - An independent package manager for compiled binaries.
- <code>&nbsp;&nbsp;&nbsp;260</code> [tcpdog](https://github.com/mehrdadrad/tcpdog) - eBPF based TCP observability.
- <code>&nbsp;&nbsp;&nbsp;217</code> [joincap](https://github.com/assafmo/joincap) - Command-line utility for merging multiple pcap files together.
- <code>&nbsp;&nbsp;&nbsp;187</code> [Orbit](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates.
- <code>&nbsp;&nbsp;&nbsp;184</code> [fjira](https://github.com/mk-5/fjira) - A fuzzy-search based terminal UI application for Attlasian Jira
- <code>&nbsp;&nbsp;&nbsp;155</code> [vaku](https://github.com/lingrino/vaku) - CLI & API for folder-based functions in Vault like copy, move, and search.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;80</code> [dp](https://github.com/scryinfo/dp) - Through SDK for data exchange with blockchain, developers can get easy access to DAPP development.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;78</code> [boxed](https://github.com/tejo/boxed) - Dropbox based blog engine.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> [naclpipe](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> [Snitch](https://github.com/lucasgomide/snitch) - Simple way to notify your team and many tools when someone has deployed any application via Tsuru.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at function list.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> [tinycare-tui](https://github.com/DMcP89/tinycare-tui) - Small terminal app that shows git commits from the last 24 hours and week, current weather, some self care advice, a joke, and you current todo list tasks.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> [hoofli](https://github.com/dnnrly/hoofli) - Generate PlantUML diagrams from Chrome or Firefox network inspections.
- [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
- [hugo](https://gohugo.io/) - Fast and Modern Static Website Engine.
- [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
- [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
- [GoLand](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
- [goblin](https://goblin.run) - Cloud builder for CLI's written in go lang
- [Wave Terminal](https://waveterm.dev) - Wave is an open-source, AI-native terminal built for seamless developer workflows with inline rendering, a modern UI, and persistent sessions.
- [limetext](https://limetext.github.io) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
- [Better Go Playground](https://goplay.tools) - Go playground with syntax highlight, code completion and other features.
- [Layli](https://layli.app) - Draw pretty layout diagrams as code.
- [zs](https://git.mills.io/prologic/zs) - an extremely minimal static site generator.

**[⬆ back to top](#contents)**

# Resources

*Where to discover new Go libraries.*

**[⬆ back to top](#contents)**

## Benchmarks

- <code>&nbsp;&nbsp;2124</code> [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark.
- <code>&nbsp;&nbsp;1657</code> [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison.
- <code>&nbsp;&nbsp;1599</code> [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods.
- <code>&nbsp;&nbsp;1057</code> [skynet](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark.
- <code>&nbsp;&nbsp;&nbsp;243</code> [speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language.
- <code>&nbsp;&nbsp;&nbsp;148</code> [go-benchmarks](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches.
- <code>&nbsp;&nbsp;&nbsp;137</code> [golang-benchmarks](https://github.com/SimonWaldherr/golang-benchmarks) - a collection of golang benchmarks.
- <code>&nbsp;&nbsp;&nbsp;126</code> [gospeed](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;99</code> [autobench](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;66</code> [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;61</code> [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;32</code> [go-ml-benchmarks](https://github.com/nikolaydubina/go-ml-benchmarks) - benchmarks for machine learning inference in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> [kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> [go-json-benchmark](https://github.com/zerosnake0/go-json-benchmark) - Go JSON benchmark.

**[⬆ back to top](#contents)**

## Conferences

- [GoCon](https://gocon.connpass.com/) - Tokyo, Japan.
- [GoDays](https://www.godays.io/) - Berlin, Germany.
- [GoLab](https://golab.io/) - Florence, Italy.
- [GopherChina](https://gopherchina.org) - Shanghai, China.
- [GopherCon](https://www.gophercon.com/) - Varied Locations Each Year, USA.
- [GopherCon Australia](https://gophercon.com.au/) - Sydney, Australia.
- [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, Brazil.
- [GopherCon Europe](https://gophercon.eu/) - Berlin, Germany.
- [GopherCon India](https://gopherconindia.org/) - Pune, India.
- [GopherCon Israel](https://www.gophercon.org.il/) - Tel Aviv, Israel.
- [GopherCon Russia](https://www.gophercon-russia.ru) - Moscow, Russia.
- [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore.
- [GopherCon UK](https://www.gophercon.co.uk/) - London, UK.
- [GopherCon Vietnam](https://gophercon.vn/) - Ho Chi Minh City, Vietnam.
- [GoWest Conference](https://www.gowestconf.com/) - Lehi, USA.

**[⬆ back to top](#contents)**

## E-Books

### E-books for purchase

- [100 Go Mistakes: How to Avoid Them](https://www.manning.com/books/100-go-mistakes-how-to-avoid-them)
- [Black Hat Go](https://nostarch.com/blackhatgo) - Go programming for hackers and pentesters.
- [Build an Orchestrator in Go](https://www.manning.com/books/build-an-orchestrator-in-go)
- [Continuous Delivery in Go](https://www.manning.com/books/continuous-delivery-in-go) - This practical guide to continuous delivery shows you how to rapidly establish an automated pipeline that will improve your testing, code quality, and final product.
- [Creative DIY Microcontroller Project With TinyGo and WebAssembly](https://www.packtpub.com/product/creative-diy-microcontroller-projects-with-tinygo-and-webassembly/9781800560208) - An introduction into the TinyGo compiler with projects involving Arduino and WebAssembly.
- [Effective Go: Elegant, efficient, and testable code](https://www.manning.com/books/effective-go) - Unlock Go’s unique perspective on program design, and start writing simple, maintainable, and testable Go code.
- [For the Love of Go](https://bitfieldconsulting.com/books/love) - An introductory book for Go beginners.
- [Go in Practice, Second Edition](https://www.manning.com/books/go-in-practice-second-edition) - Your practical guide on the ins-and-outs of Go development, covering the standard library and the most important tools from Go’s powerful ecosystem.
- [Know Go: Generics](https://bitfieldconsulting.com/books/generics) - A guide to understanding and using generics in Go.
- [Lets-Go](https://lets-go.alexedwards.net) - A step-by-step guide to creating fast, secure and maintanable web applications with Go.
- [Lets-Go-Further](https://lets-go-further.alexedwards.net) - Advanced patterns for building APIs and web applications in Go.
- [The Power of Go: Tests](https://bitfieldconsulting.com/books/tests) - A guide to testing in Go.
- [The Power of Go: Tools](https://bitfieldconsulting.com/books/tools) - A guide to writing command-line tools in Go.
- [Writing A Compiler In Go](https://compilerbook.com)
- [Writing An Interpreter In Go](https://interpreterbook.com) - Book that introduces dozens of techniques for writing idiomatic, expressive, and efficient Go code that avoids common pitfalls.

### Free e-books

- <code>&nbsp;18327</code> [GoBooks](https://github.com/dariubs/GoBooks) - A curated list of Go books.
- <code>&nbsp;&nbsp;9546</code> [The Golang Standard Library by Example (Chinese)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example)
- <code>&nbsp;&nbsp;5472</code> [Go AST Book (Chinese)](https://github.com/chai2010/go-ast-book) - A book focusing on Go `go/*` packages.
- <code>&nbsp;&nbsp;3214</code> [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)
- <code>&nbsp;&nbsp;&nbsp;446</code> [Build a blockchain from scratch in Go with gRPC](https://github.com/volodymyrprokopyuk/go-blockchain) - The foundational and practical guide for effectively learning and progressively building a blockchain from scratch in Go with gRPC.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> [Go Succinctly](https://github.com/thedevsir/gosuccinctly) - in Persian.
- [Building Web Apps With Go](https://codegangsta.gitbooks.io/building-web-apps-with-go/content/)
- [Go Faster](https://leanpub.com/gofaster) - This book seeks to shorten your learning curve and help you become a proficient Go programmer, faster.
- [Go 101](https://go101.org) - A book focusing on Go syntax/semantics and all kinds of details.
- [Go with the domain](https://threedots.tech/go-with-the-domain/) - A book showing how to apply DDD, Clean Architecture, and CQRS by practical refactoring.
- [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
- [How To Code in Go eBook](https://www.digitalocean.com/community/books/how-to-code-in-go-ebook) - A 600 page introduction to Go aimed at first time developers.
- [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
- [Network Programming With Go](https://jan.newmarch.name/golang/)
- [Practical Go Lessons](https://www.practical-go-lessons.com/)
- [Spaceship Go A Journey to the Standard Library](https://blasrodri.github.io/spaceship-go-gh-pages/)
- [The Go Programming Language](https://www.gopl.io/)
- [Build Web Application with Golang](https://astaxie.gitbooks.io/build-web-application-with-golang/content/en/)
- [An Introduction to Programming in Go](http://www.golang-book.com/)

**[⬆ back to top](#contents)**

## Gophers

- <code>&nbsp;&nbsp;3789</code> [Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack) - Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster.
- <code>&nbsp;&nbsp;3699</code> [gophers](https://github.com/egonelbre/gophers) - Free gophers.
- <code>&nbsp;&nbsp;3025</code> [gophers](https://github.com/ashleymcnamara/gophers) - Gopher artworks by Ashley McNamara.
- <code>&nbsp;&nbsp;&nbsp;737</code> [gopherize.me](https://github.com/matryer/gopherize.me) - Gopherize yourself.
- <code>&nbsp;&nbsp;&nbsp;625</code> [gophericons](https://github.com/shalakhin/gophericons)
- <code>&nbsp;&nbsp;&nbsp;601</code> [gopher-stickers](https://github.com/tenntenn/gopher-stickers)
- <code>&nbsp;&nbsp;&nbsp;156</code> [gophers](https://github.com/sillecelik/go-gopher) - Gopher amigurumi toy pattern.
- <code>&nbsp;&nbsp;&nbsp;131</code> [gopher-logos](https://github.com/GolangUA/gopher-logos) - adorable gopher logos.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;73</code> [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) - Go gopher Vector Data [.ai, .svg].
- <code>&nbsp;&nbsp;&nbsp;&nbsp;58</code> [gophers](https://github.com/rogeralsing/gophers) - random gopher graphics.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> [gophers](https://github.com/scraly/gophers) - Gophers by Aurélie Vache.

**[⬆ back to top](#contents)**

## Meetups

- [Basel Go Meetup](https://www.meetup.com/Basel-Go-Meetup/)
- [Belfast Gophers](https://www.meetup.com/Belfast-Gophers/)
- [Belgrade Golang Meetup](https://www.meetup.com/golang-serbia/)
- [Berlin Golang](https://www.meetup.com/golang-users-berlin/)
- [Brisbane Gophers](https://www.meetup.com/Brisbane-Golang-Meetup/)
- [Bärner Go Meetup - Berne, Switzerland](https://www.meetup.com/berner-go-meetup/)
- [Go Ireland - Dublin](https://www.meetup.com/goireland/)
- [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
- [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
- [Go Remote Meetup](https://www.meetup.com/Go-Remote-Meetup/)
- [Go Toronto](https://www.meetup.com/go-toronto/)
- [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
- [GoBandung](https://www.meetup.com/GoBandung/)
- [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
- [GoCracow - Krakow, Poland](https://www.meetup.com/GoCracow/)
- [GoJakarta](https://www.meetup.com/GoJakarta/)
- [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
- [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
- [Golang Athens](https://www.meetup.com/Athens-Gophers/)
- [Golang Baltimore, MD](https://www.meetup.com/BaltimoreGolang/)
- [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
- [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
- [Golang Boston](https://www.meetup.com/bostongo/)
- [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
- [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
- [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
- [Golang Curitiba - Brazil](https://www.meetup.com/GolangCWB/)
- [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
- [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
- [Golang Estonia](https://www.meetup.com/Golang-Estonia/)
- [Golang Gurgaon, India](https://www.meetup.com/Gurgaon-Go-Meetup/)
- [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
- [Golang Israel](https://www.meetup.com/Go-Israel/)
- [Golang Kathmandu](https://www.meetup.com/Golang-Kathmandu/)
- [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
- [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
- [Golang Marseille](https://www.meetup.com/fr-FR/Golang-Marseille/)
- [Golang Melbourne](https://www.meetup.com/golang-mel/)
- [Golang Milano](https://www.meetup.com/golang-milano/)
- [Golang North East](https://www.meetup.com/en-AU/Golang-North-East/)
- [Golang Paris](https://www.meetup.com/Golang-Paris/)
- [Golang Poland](https://www.meetup.com/Golang-Poland/)
- [Golang Pune](https://www.meetup.com/Golang-Pune/)
- [Golang Roma](https://www.meetup.com/golangroma/)
- [Golang Rotterdam](https://www.meetup.com/golang-rotterdam/)
- [Golang Singapore](https://www.meetup.com/golangsg/)
- [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
- [Golang Sydney, AU](https://www.meetup.com/golang-syd/)
- [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
- [Golang Taipei](https://www.meetup.com/golang-taipei-meetup/)
- [Golang Thessaloniki](https://www.meetup.com/thessaloniki-golang-meetup/)
- [Golang Torino](https://www.meetup.com/golang-torino/)
- [Golang Turkey](https://kommunity.com/goturkiye)
- [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
- [Golang Vienna, Austria](https://www.meetup.com/viennago/)
- [Golang Москва](https://www.meetup.com/Golang-Moscow/)
- [GoSF - San Francisco, CA](https://www.meetup.com/golangsf)
- [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
- [Lagos Gophers](https://www.meetup.com/GolangNigeria/)
- [Nairobi Gophers](https://www.meetup.com/nairobi-gophers/)
- [Seattle Go Programmers](https://www.meetup.com/golang/)
- [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
- [Utah Go User Group](https://www.meetup.com/utahgophers/)
- [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)
- [Zürich Gophers - Zurich, Switzerland](https://www.meetup.com/zurich-gophers/)

*Add the group of your city/country here (send **PR**)*

**[⬆ back to top](#contents)**

## Style Guides

- <code>&nbsp;31139</code> [CockroachDB](https://github.com/cockroachdb/cockroach/blob/master/docs/style.md)
- <code>&nbsp;16706</code> [Uber](https://github.com/uber-go/guide/blob/master/style.md)
- <code>&nbsp;16209</code> [Hyperledger](https://github.com/hyperledger/fabric/blob/release-1.4/docs/source/style-guides/go-style.rst)
- <code>&nbsp;&nbsp;3094</code> [Magnetico](https://github.com/boramalper/magnetico/wiki/magnetico-Design-Specification)
- <code>&nbsp;&nbsp;1509</code> [bahlo/go-styleguide](https://github.com/bahlo/go-styleguide)
- <code>&nbsp;&nbsp;&nbsp;309</code> [Trybe](https://github.com/betrybe/playbook-go/blob/main/README_EN.md)
- [GitLab](https://docs.gitlab.com/ee/development/go_guide/)
- [Google](https://google.github.io/styleguide/go/)
- [Thanos](https://thanos.io/tip/contributing/coding-style-guide.md/)

**[⬆ back to top](#contents)**

## Social Media

### Twitter

- [@GoDiscussions](https://twitter.com/GoDiscussions)
- [@golang](https://twitter.com/golang)
- [@golang_news](https://twitter.com/golang_news)
- [@golangch](https://twitter.com/golangch)
- [@golangweekly](https://twitter.com/golangweekly)

**[⬆ back to top](#contents)**

### Reddit

- [r/golang](https://www.reddit.com/r/golang/)

**[⬆ back to top](#contents)**

## Websites

- <code>129166</code> [Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki.
- <code>&nbsp;39129</code> [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them are looking for Go hackers.
- <code>&nbsp;32748</code> [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists.
- <code>&nbsp;&nbsp;&nbsp;522</code> [Awesome Golang Workshops](https://github.com/amit-davidson/awesome-golang-workshops) - A curated list of awesome golang workshops.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> [gocryforhelp](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> [awesome-go-extra](https://github.com/xwjdsh/awesome-go-extra) - Parse awesome-go README file and generate a new README file with repo info.
- [Go Blog](https://blog.golang.org) - The official Go blog.
- [Golang Nugget](https://golangnugget.com) - A weekly roundup of the best Go content, delivered to your inbox every Monday.
- [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
- [Go Code Club](https://www.youtube.com/watch?v=nvoIPQYdx9g&list=PLEcwzBXTPUE_YQR7R0BRtHBYJ0LN3Y0i3) - A group of Gophers read and discuss a different Go project every week.
- [Go Community on Hashnode](https://hashnode.com/n/go) - Community of Gophers on Hashnode.
- [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
- [Coding Mystery](https://codingmystery.com) - Solve exciting escape-room-inspired programming challenges using Go.
- [Go Proverbs](https://go-proverbs.github.io/) - Go Proverbs by Rob Pike.
- [Go Report Card](https://goreportcard.com) - A report card for your Go package.
- [go.dev](https://go.dev/) - A hub for Go developers.
- [Code with Mukesh](https://codewithmukesh.com/categories/golang) - Software Engineer and Blogs @ codewithmukesh.com.
- [Golang Developer Jobs](https://golangjob.xyz) - Developer Jobs exclusively for Golang related Roles.
- [Golang News](https://golangnews.com) - Links and news about Go programming.
- [CodinGame](https://www.codingame.com/) - Learn Go by solving interactive tasks using small games as practical examples.
- [Golang Weekly](https://discu.eu/weekly/golang/) - Each monday projects, tutorials and articles about Go.
- [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
- [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
- [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
- [Gophercises](https://gophercises.com/) - Free coding exercises for budding gophers.
- [json2go](https://m-zajac.github.io/json2go) - Advanced JSON to Go struct conversion - online tool.
- [justforfunc](https://www.youtube.com/c/justforfunc) - Youtube channel dedicated to Go programming language tips and tricks, hosted by Francesc Campoy [@francesc](https://twitter.com/francesc).
- [Learn Go Programming](https://blog.learngoprogramming.com) - Learn Go concepts with illustrations.
- [Made with Golang](https://madewithgolang.com/?ref=awesome-go)
- [pkg.go.dev](https://pkg.go.dev/) - Documentation for open source Go packages.
- [studygolang](https://studygolang.com) - The community of studygolang in China.
- [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.
- [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

**[⬆ back to top](#contents)**

### Tutorials

- <code>&nbsp;43716</code> [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang.
- <code>&nbsp;26713</code> [go-patterns](https://github.com/tmrts/go-patterns) - Curated list of Go design patterns, recipes and idioms.
- <code>&nbsp;23037</code> [Learn Go with TDD](https://github.com/quii/learn-go-with-tests) - Learn Go with test-driven development.
- <code>&nbsp;19421</code> [Learn Go with 1000+ Exercises](https://github.com/inancgumus/learngo) - Learn Go with thousands of examples, exercises, and quizzes.
- <code>&nbsp;&nbsp;8678</code> [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card.
- <code>&nbsp;&nbsp;6984</code> [go-clean-template](https://github.com/evrone/go-clean-template) - Clean Architecture template for Golang services.
- <code>&nbsp;&nbsp;4743</code> [Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) - Examples of Golang compared to Node.js for learning.
- <code>&nbsp;&nbsp;1637</code> [golang-examples](https://github.com/SimonWaldherr/golang-examples) - Many examples to learn Golang.
- <code>&nbsp;&nbsp;&nbsp;155</code> [Go in 7 days](https://github.com/harrytran103/7_days_of_go) - Learn everything about Go in 7 days (from a Nodejs developer).
- <code>&nbsp;&nbsp;&nbsp;128</code> [Design Patterns in Go](https://github.com/shubhamzanwar/design-patterns) - Collection of programming design patterns implemented in Go.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;79</code> [Hex Monscape](https://github.com/Haraj-backend/hex-monscape) - Getting started guidelines in writing maintainable code using Hexagonal Architecture.
- [Gosamples](https://gosamples.dev/) - Collection of code snippets that let you solve everyday code problems.
- [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - How to cancel MySQL queries.
- [GopherSnippets](https://gophersnippets.com/) - Code snippets with tests and testable examples for the Go programming language.
- [CodeCrafters Golang Track](https://app.codecrafters.io/tracks/go) - Achieve mastery in advanced Go by building your own Redis, Docker, Git, and SQLite. Featuring goroutines, systems programming, file I/O, and more.
- [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
- [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) - How to cache slow database queries.
- [Go Language Tutorial](https://www.javatpoint.com/go-tutorial) - Learn Go language Tutorial.
- [Go Tutorial](https://www.tutorialspoint.com/go/index.htm) - Learn Go programming.
- [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
- [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
- [Building and Testing a REST API in Go with Gorilla Mux and PostgreSQL](https://semaphoreci.com/community/tutorials/building-and-testing-a-rest-api-in-go-with-gorilla-mux-and-postgresql) - We’ll write an API with the help of the powerful Gorilla Mux.
- [Build a Database in 1000 lines of code](https://link.medium.com/O9YQlx89Htb) - Build a NoSQL Database From Zero in 1000 Lines of Code.
- [Golang Tutorial Guide](https://www.freecodecamp.org/news/golang-tutorial-list-free-courses-learn-go-programming-language/) - A List of Free Courses to Learn the Go Programming Language.
- [A Tour of Go](https://tour.golang.org/) - Interactive tour of Go.
- [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
- [GopherCoding](https://gophercoding.com/) - Collection of code snippets and tutorials to help tackle every day issues.
- [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
- [GraphQL with Go](https://hasura.io/learn/graphql/backend-stack/languages/go/) - Learn how to create a Go GraphQL server and client with code generation. Also includes creating REST endpoints.
- [Games With Go](https://www.youtube.com/watch?v=9D4yH7e_ea8&list=PLDZujg-VgQlZUy1iCqBbe5faZLMkA3g2x) - A video series teaching programming and game development.
- [Hackr.io](https://hackr.io/tutorials/learn-golang) - Learn Go from the best online golang tutorials submitted & voted by the golang programming community.
- [50 Shades of Go](https://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - Traps, Gotchas, and Common Mistakes for New Golang Devs.
- [How to Benchmark: dbq vs sqlx vs GORM](https://medium.com/@rocketlaunchr.cloud/how-to-benchmark-dbq-vs-sqlx-vs-gorm-e814caacecb5) - Learn how to benchmark in Go. As a case-study, we will benchmark dbq, sqlx and GORM.
- [How To Deploy a Go Web Application with Docker](https://semaphoreci.com/community/tutorials/how-to-deploy-a-go-web-application-with-docker) - Learn how to use Docker for Go development and how to build production Docker images.
- [How to Implement Role-Based Access Control (RBAC) Authorization in Golang](https://www.permit.io/blog/role-based-access-control-rbac-authorization-in-golang) - A guide to implementing Role-Based Access Control (RBAC) in Golang, including code examples, covering various methods to secure app endpoints with role-based authorization.
- [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog - a Behavior-driven development framework for building and testing Go applications.
- [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) - Building a Golang site for e-commerce (demo included).
- [A Comprehensive Guide to Structured Logging in Go](https://betterstack.com/community/guides/logging/logging-in-go/) - Delve deep into the world of structured logging in Go with a specific focus on recently accepted slog proposal which aims to bring high performance structured logging with levels to the standard library.
- [Learning Go by examples](https://dev.to/aurelievache/learning-go-by-examples-introduction-448n) - Series of articles in order to learn Golang language by concrete applications as example.
- [Microservices with Go](https://www.youtube.com/playlist?list=PLmD8u-IFdreyh6EUfevBcbiuCKzFk0EW_) - Dive deep into building microservices using Go, including gRPC.
- [package main](https://www.youtube.com/packagemain) - YouTube channel about Programming in Go.
- [Programming with Google Go](https://www.coursera.org/specializations/google-golang) - Coursera Specialization to learn about Go from scratch.
- [Scaling Go Applications](https://betterstack.com/community/guides/scaling-go/) - Everything about building, deploying and scaling Go applications in production.
- [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
- [Understanding Go in a visual way](https://dev.to/aurelievache/series/26234) - Learn Go visually
- [W3basic Go Tutorials](https://www.w3basic.com/golang/) - W3Basic provides an in-depth tutorial and well-organized content to learn Golang programming.
- [Your basic Go](https://yourbasic.org/golang) - Huge collection of tutorials and how to's.

**[⬆ back to top](#contents)**

### Guided Learning

- <code>&nbsp;&nbsp;&nbsp;711</code> [The Go Interview Practice](https://github.com/RezaSi/go-interview-practice) - A GitHub repository offering coding challenges for Go technical interview preparation.
- [The Go Developer Roadmap](https://roadmap.sh/golang) - A visual roadmap that new Go developers can follow through to help them learn Go.
- [The Go Learning Path](https://tutorialedge.net/paths/golang/) - A guided learning path containing a mix of free and premium resources.
- [The Go Skill Tree](https://labex.io/skilltrees/go) - A structured learning path that combines both free and premium resources.

**[⬆ back to top](#contents)**
