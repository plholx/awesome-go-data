# Awesome Go Info

go语言开源项目列表，项目分类及GitHub上的开源项目数据完全来自于[awesome-go](https://github.com/avelino/awesome-go) 的[README.md](https://github.com/avelino/awesome-go/blob/master/README.md)文件，通过调用GitHub的API获取仓库信息，展示项目的star数、watch数等，方便查看go语言开源项目的一些相关信息。

_该文件仅包含[awesome-go](https://github.com/avelino/awesome-go) [README.md](https://github.com/avelino/awesome-go/blob/master/README.md)文件中列出的在GitHub上开源的优秀项目，不罗列其它golang相关的网站_
_该文件中的GitHub仓库信息数据会在每天凌晨1点左右更新,当前数据更新于2021-07-13 00:58:07_

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
        - [Relational Databases](#relational-databases)
        - [NoSQL Databases](#nosql-databases)
    - [Date and Time](#date-and-time)
    - [Distributed Systems](#distributed-systems)
    - [Dynamic DNS](#dynamic-dns)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Error Handling](#error-handling)
    - [Files](#files)
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
        - [Testing Frameworks](#testing-frameworks)
        - [Mock](#mock)
        - [Fail injection](#fail-injection)
    - [Text Processing](#text-processing)
        - [Specific Formats](#specific-formats)
        - [Utility](#utility)
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
    - [Windows](#windows)
    - [XML](#xml)
    - [WebAssembly](#webassembly)
    - [Files](#Files)
    - [File Handling](#file-handling)
    - [Build Automation](#build-automation)
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
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)
    - [Style Guides](#style-guides)




# Awesome Go
        

## Audio and Music
        
*Libraries for manipulating audio.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [oto](https://github.com/hajimehoshi/oto) | 828 | 9 | 2017/05/04 | 1 week ago | A low-level library to play sound on multiple platforms. |
| [portaudio](https://github.com/gordonklaus/portaudio) | 457 | 13 | 2015/09/16 | 10 months ago | Go bindings for the PortAudio audio I/O library. |
| [music-theory](https://github.com/go-music-theory/music-theory) | 342 | 19 | 2016/03/17 | 11 months ago | Music theory models in Go. |
| [waveform](https://github.com/mdlayher/waveform) | 338 | 12 | 2014/09/13 | 1 year ago | Go package capable of generating waveform images from audio streams. |
| [portmidi](https://github.com/rakyll/portmidi) | 258 | 11 | 2013/11/10 | 8 months ago | Go bindings for PortMidi. |
| [id3v2](https://github.com/bogem/id3v2) | 188 | 6 | 2016/05/15 | 2 months ago | ID3 decoding and encoding library for Go. |
| [flac](https://github.com/mewkiz/flac) | 159 | 11 | 2012/11/01 | 5 months ago | Native Go FLAC encoder/decoder with support for FLAC streams. |
| [malgo](https://github.com/gen2brain/malgo) | 150 | 5 | 2017/11/09 | 2 months ago | Mini audio library. |
| [mix](https://github.com/go-mix/mix) | 140 | 3 | 2016/01/03 | 1 year ago | Sequence-based Go-native audio mixer for music apps. |
| [GoAudio](https://github.com/DylanMeeus/GoAudio) | 137 | 6 | 2020/07/05 | 3 months ago | Native Go Audio Processing Library. |
| [go-sox](https://github.com/krig/go-sox) | 120 | 9 | 2013/10/08 | 3 years ago | libsox bindings for go. |
| [mp3](https://github.com/tcolgate/mp3) | 114 | 2 | 2015/02/26 | 4 years ago | Native Go MP3 decoder. |
| [gaad](https://github.com/Comcast/gaad) | 84 | 12 | 2016/07/11 | 3 days ago | Native Go AAC bitstream parser. |
| [go-taglib](https://github.com/wtolson/go-taglib) | 74 | 6 | 2012/11/20 | 3 years ago | Go bindings for taglib. |
| [minimp3](https://github.com/tosone/minimp3) | 55 | 3 | 2018/01/26 | 3 months ago | Lightweight MP3 decoder library. |
| [EasyMIDI](https://github.com/algoGuy/EasyMIDI) | 35 | 3 | 2018/02/19 | 3 years ago | EasyMidi is a simple and reliable library for working with standard midi file (SMF). |
| [go_mediainfo](https://github.com/zhulik/go_mediainfo) | 32 | 1 | 2015/12/13 | 5 years ago | libmediainfo bindings for go. |
| [vorbis](https://github.com/mccoyst/vorbis) | 28 | 3 | 2013/07/12 | 2 years ago | "Native" Go Vorbis decoder (uses CGO, but has no dependencies). |
| [gosamplerate](https://github.com/dh1tw/gosamplerate) | 11 | 1 | 2016/11/20 | 1 year ago | libsamplerate bindings for go. |

## Authentication and OAuth
        
*Libraries for implementing authentications schemes.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [jwt-go](https://github.com/dgrijalva/jwt-go) | 9759 | 153 | 2012/04/18 | 2 days ago | Golang implementation of JSON Web Tokens (JWT). |
| [casbin](https://github.com/casbin/casbin) | 9460 | 218 | 2017/04/08 | 1 month ago | Authorization library that supports access control models like ACL, RBAC, ABAC. |
| [oauth2](https://github.com/golang/oauth2) | 3717 | 103 | 2014/04/14 | 1 week ago | Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support. |
| [goth](https://github.com/markbates/goth) | 3227 | 63 | 2014/10/14 | 1 week ago | provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box. |
| [authboss](https://github.com/volatiletech/authboss) | 2703 | 55 | 2015/01/03 | 1 week ago | Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time. |
| [loginsrv](https://github.com/tarent/loginsrv) | 1796 | 53 | 2016/11/11 | 4 months ago | JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam. |
| [go-jose](https://github.com/square/go-jose) | 1785 | 61 | 2014/11/14 | 1 month ago | Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. |
| [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) | 1775 | 85 | 2015/11/01 | 6 months ago | Standalone, specification-compliant,  OAuth2 server written in Golang. |
| [osin](https://github.com/openshift/osin) | 1676 | 72 | 2013/09/10 | 1 week ago | Golang OAuth2 server library. |
| [gologin](https://github.com/dghubble/gologin) | 1409 | 29 | 2015/06/23 | 1 month ago | chainable handlers for login with OAuth1 and OAuth2 authentication providers. |
| [gorbac](https://github.com/mikespook/gorbac) | 1187 | 61 | 2013/12/26 | 2 months ago | provides a lightweight role-based access control (RBAC) implementation in Golang. |
| [scs](https://github.com/alexedwards/scs) | 892 | 25 | 2016/08/08 | 1 month ago | Session Manager for HTTP servers. |
| [paseto](https://github.com/o1egl/paseto) | 523 | 22 | 2018/01/23 | 1 year ago | Golang implementation of Platform-Agnostic Security Tokens (PASETO). |
| [permissions2](https://github.com/xyproto/permissions2) | 432 | 14 | 2014/11/19 | 5 days ago | Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt. |
| [go-guardian](https://github.com/shaj13/go-guardian) | 280 | 5 | 2020/05/14 | 1 day ago | Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token and Certificate based authentication. |
| [jwt](https://github.com/cristalhq/jwt) | 277 | 12 | 2019/07/20 | 1 day ago | Safe, simple and fast JSON Web Tokens for Go. |
| [jwt](https://github.com/pascaldekloe/jwt) | 257 | 13 | 2018/03/21 | 4 months ago | Lightweight JSON Web Token (JWT) library. |
| [jeff](https://github.com/abraithwaite/jeff) | 228 | 4 | 2018/08/02 | 2 weeks ago | Simple, flexible, secure and idiomatic web session management with pluggable backends. |
| [httpauth](https://github.com/goji/httpauth) | 206 | 7 | 2014/05/26 | 11 months ago | HTTP Authentication middleware. |
| [jwt-auth](https://github.com/adam-hanna/jwt-auth) | 204 | 12 | 2016/07/05 | 1 month ago | JWT middleware for Golang http servers with many configuration options. |
| [branca](https://github.com/hako/branca) | 154 | 8 | 2018/01/09 | 11 months ago | Golang implementation of Branca Tokens. |
| [sessionup](https://github.com/swithek/sessionup) | 112 | 6 | 2019/07/23 | 1 month ago | Simple, yet effective HTTP session management and identification package. |
| [session](https://github.com/icza/session) | 105 | 7 | 2016/02/08 | 2 years ago | Go session management for web servers (including support for Google App Engine - GAE). |
| [sjwt](https://github.com/brianvoe/sjwt) | 92 | 1 | 2019/06/20 | 1 year ago | Simple jwt generator and parser. |
| [jwt](https://github.com/robbert229/jwt) | 90 | 9 | 2016/06/05 | 7 months ago | Clean and easy to use implementation of JSON Web Tokens (JWT). |
| [rbac](https://github.com/zpatrick/rbac) | 80 | 3 | 2018/08/02 | 2 years ago | Minimalistic RBAC package for Go applications. |
| [sessions](https://github.com/adam-hanna/sessions) | 60 | 3 | 2017/04/29 | 1 year ago | Dead simple, highly performant, highly customizable sessions service for go http servers. |
| [securecookie](https://github.com/chmike/securecookie) | 51 | 5 | 2017/09/03 | 1 week ago | Efficient secure cookie encoding/decoding. |
| [go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) | 22 | 1 | 2020/08/21 | 7 months ago | Golang library for providing a canonical representation of email address. |
| [otpgo](https://github.com/jltorresm/otpgo) | 20 | 3 | 2020/08/19 | 4 months ago | Time-Based One-Time Password (TOTP) and HMAC-Based One-Time Password (HOTP) library for Go. |
| [scope](https://github.com/SonicRoshan/scope) | 12 | 1 | 2019/09/23 | 1 month ago | Easily Manage OAuth2 Scopes In Go. |
| [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) | 9 | 2 | 2017/10/20 | 2 years ago | Go session management using the SessionGate Redis module. |
| [signedvalue](https://github.com/sashka/signedvalue) | 8 | 0 | 2018/01/06 | 1 year ago | Signed and timestamped strings compatible with [Tornado's](https://github.com/tornadoweb/tornado) `create_signed_value`, `decode_signed_value`, and therefore `set_secure_cookie` and `get_secure_cookie`. |
| [cookiestxt](https://github.com/mengzhuo/cookiestxt) | 6 | 1 | 2017/10/09 | 4 months ago | provides parser of cookies.txt file format. |
| [casbin](https://github.com/hsluoyz/casbin) | 1 | 0 | 2021/04/16 | 1 month ago | Authorization library that supports access control models like ACL, RBAC, ABAC. |

## Bot Building
        
*Libraries for building and working with bots.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [olivia](https://github.com/olivia-ai/olivia) | 2978 | 81 | 2018/06/05 | 4 months ago | A chatbot built with an artificial neural network. |
| [telegram-bot-api](https://github.com/go-telegram-bot-api/telegram-bot-api) | 2942 | 82 | 2015/06/25 | 2 days ago | Simple and clean Telegram bot client. |
| [telebot](https://github.com/tucnak/telebot) | 1982 | 48 | 2015/06/25 | 4 days ago | Telegram bot framework written in Go. |
| [kelp](https://github.com/stellar/kelp) | 704 | 46 | 2018/08/08 | 1 week ago | official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies. |
| [bot](https://github.com/go-chat-bot/bot) | 685 | 47 | 2015/09/22 | 9 months ago | IRC, Slack & Telegram bot written in Go. |
| [golang-crypto-trading-bot](https://github.com/saniales/golang-crypto-trading-bot) | 571 | 33 | 2017/05/14 | 1 month ago | A golang implementation of a console-based trading bot for cryptocurrency exchanges. |
| [slacker](https://github.com/shomali11/slacker) | 525 | 14 | 2017/05/20 | 3 days ago | Easy to use framework to create Slack bots. |
| [tbot](https://github.com/yanzay/tbot) | 314 | 10 | 2015/09/11 | 3 months ago | Telegram bot server with API similar to net/http. |
| [go-sarah](https://github.com/oklahomer/go-sarah) | 196 | 7 | 2016/11/06 | 1 month ago | Framework to build bot for desired chat services including LINE, Slack, Gitter and more. |
| [go-twitch-irc](https://github.com/gempir/go-twitch-irc) | 175 | 11 | 2017/03/23 | 4 months ago | Libary to write bots for twitch. |
| [tenyks](https://github.com/kyleterry/tenyks) | 170 | 15 | 2012/08/26 | 1 year ago | Service oriented IRC bot using Redis and JSON for messaging. |
| [hanu](https://github.com/sbstjn/hanu) | 135 | 6 | 2016/09/16 | 3 weeks ago | Framework for writing Slack bots. |
| [go-tgbot](https://github.com/olebedev/go-tgbot) | 107 | 9 | 2016/12/11 | 3 years ago | Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware. |
| [margelet](https://github.com/zhulik/margelet) | 63 | 4 | 2015/11/21 | 4 years ago | Framework for building Telegram bots. |
| [ephemeral-roles](https://github.com/ewohltman/ephemeral-roles) | 50 | 5 | 2017/12/19 | 1 month ago | A Discord bot for managing ephemeral roles based upon voice channel member presence. |
| [slackscot](https://github.com/alexandre-normand/slackscot) | 45 | 1 | 2015/10/22 | 4 months ago | Another framework for building Slack bots. |
| [govkbot](https://github.com/nikepan/govkbot) | 36 | 3 | 2016/07/11 | 1 year ago | Simple Go [VK](https://vk.com) bot library. |
| [micha](https://github.com/onrik/micha) | 17 | 3 | 2016/04/14 | 1 month ago | Go Library for Telegram bot api. |

## Command Line
        
*Libraries for building Console Applications and Console User Interfaces.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [cobra](https://github.com/spf13/cobra) | 22322 | 345 | 2013/09/03 | 19 hours ago | Commander for modern Go CLI interactions. |
| [cli](https://github.com/urfave/cli) | 16119 | 301 | 2013/07/13 | 5 days ago | Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli). |
| [termui](https://github.com/gizak/termui) | 11074 | 294 | 2015/02/03 | 2 months ago | Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib). |
| [gocui](https://github.com/jroimartin/gocui) | 7247 | 128 | 2014/01/04 | 2 months ago | Minimalist Go library aimed at creating Console User Interfaces. |
| [termbox-go](https://github.com/nsf/termbox-go) | 4091 | 98 | 2012/01/12 | 2 months ago | Termbox is a library for creating cross-platform text-based interfaces. |
| [go-prompt](https://github.com/c-bata/go-prompt) | 4017 | 54 | 2017/08/14 | 3 weeks ago | Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit). |
| [kingpin](https://github.com/alecthomas/kingpin) | 3073 | 54 | 2014/05/14 | 2 weeks ago | Command line and flag parser supporting sub commands. |
| [dnote](https://github.com/dnote/dnote) | 2104 | 29 | 2017/03/30 | 3 weeks ago | A simple command line notebook with multi-device sync. |
| [go-flags](https://github.com/jessevdk/go-flags) | 1973 | 29 | 2012/08/31 | 3 weeks ago | go command line option parser. |
| [progressbar](https://github.com/schollz/progressbar) | 1949 | 23 | 2017/10/26 | 3 weeks ago | Basic thread-safe progress bar that works in every OS. |
| [uiprogress](https://github.com/gosuri/uiprogress) | 1808 | 36 | 2015/11/17 | 3 months ago | Flexible library to render progress bars in terminal applications. |
| [termdash](https://github.com/mum4k/termdash) | 1735 | 27 | 2018/03/24 | 1 month ago | Go terminal dashboard based on **termbox-go** and inspired by [termui](https://github.com/gizak/termui). |
| [asciigraph](https://github.com/guptarohit/asciigraph) | 1696 | 30 | 2018/06/17 | 3 months ago | Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies. |
| [readline](https://github.com/chzyer/readline) | 1555 | 40 | 2015/09/20 | 1 year ago | Pure golang implementation that provides most features in GNU-Readline under MIT license. |
| [pflag](https://github.com/spf13/pflag) | 1485 | 31 | 2013/08/30 | 1 month ago | Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags. |
| [pterm](https://github.com/pterm/pterm) | 1403 | 16 | 2020/09/17 | 5 days ago | A library to beautify console output on every platform with many combinable components. |
| [cli](https://github.com/mitchellh/cli) | 1351 | 24 | 2013/11/03 | 6 months ago | Go library for implementing command-line interfaces. |
| [mpb](https://github.com/vbauerster/mpb) | 1335 | 20 | 2016/12/14 | 2 weeks ago | Multi progress bar for terminal applications. |
| [uilive](https://github.com/gosuri/uilive) | 1317 | 19 | 2015/11/16 | 8 months ago | Library for updating terminal output in realtime. |
| [docopt.go](https://github.com/docopt/docopt.go) | 1266 | 35 | 2013/08/25 | 8 months ago | Command-line arguments parser that will make you smile. |
| [go-arg](https://github.com/alexflint/go-arg) | 1191 | 14 | 2015/11/01 | 1 month ago | Struct-based argument parsing in Go. |
| [aurora](https://github.com/logrusorgru/aurora) | 1111 | 9 | 2016/11/06 | 5 months ago | ANSI terminal colors that supports fmt.Printf/Sprintf. |
| [gcli](https://github.com/tcnksm/gcli) | 907 | 26 | 2014/06/19 | 3 years ago | The easy way to start building Golang command line applications. |
| [color](https://github.com/gookit/color) | 871 | 14 | 2018/07/01 | 3 months ago | Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows. |
| [liner](https://github.com/peterh/liner) | 797 | 22 | 2012/08/15 | 3 months ago | Go readline-like library for command-line interfaces. |
| [complete](https://github.com/posener/complete) | 776 | 15 | 2017/05/05 | 3 months ago | Write bash completions in Go + Go command bash completion. |
| [mow.cli](https://github.com/jawher/mow.cli) | 741 | 19 | 2014/12/18 | 5 days ago | Go library for building CLI applications with sophisticated flag and argument parsing and validation. |
| [flaggy](https://github.com/integrii/flaggy) | 721 | 18 | 2018/03/05 | 4 days ago | A robust and idiomatic flags package with excellent subcommand support. |
| [uitable](https://github.com/gosuri/uitable) | 613 | 14 | 2015/11/13 | 8 months ago | Library to improve readability in terminal apps using tabular data. |
| [ops](https://github.com/nanovms/ops) | 607 | 27 | 2018/09/10 | 2 hours ago | Unikernel Builder/Orchestrator. |
| [cli](https://github.com/mkideal/cli) | 582 | 22 | 2016/02/26 | 1 day ago | Feature-rich and easy to use command-line package based on golang struct tags. |
| [go-colorable](https://github.com/mattn/go-colorable) | 537 | 19 | 2014/07/30 | 5 months ago | Colorable writer for windows. |
| [go-isatty](https://github.com/mattn/go-isatty) | 529 | 11 | 2014/04/01 | 3 hours ago | isatty for golang. |
| [chalk](https://github.com/ttacon/chalk) | 375 | 8 | 2014/07/18 | 1 year ago | Intuitive package for prettifying terminal/console output. |
| [argparse](https://github.com/akamensky/argparse) | 344 | 15 | 2017/11/24 | 4 days ago | Command line argument parser inspired by Python's argparse module. |
| [simpletable](https://github.com/alexeyco/simpletable) | 316 | 4 | 2017/03/29 | 2 months ago | Simple tables in terminal with Go. |
| [tabby](https://github.com/cheynewallace/tabby) | 292 | 3 | 2018/12/17 | 6 months ago | A tiny library for super simple Golang tables. |
| [go-colortext](https://github.com/daviddengcn/go-colortext) | 207 | 9 | 2013/01/23 | 1 year ago | Go library for color output in terminals. |
| [yacspin](https://github.com/theckman/yacspin) | 184 | 5 | 2019/12/29 | 1 year ago | Yet Another CLi Spinner package, for working with terminal spinners. |
| [commandeer](https://github.com/jaffee/commandeer) | 148 | 6 | 2017/10/12 | 3 weeks ago | Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags. |
| [wmenu](https://github.com/dixonwille/wmenu) | 138 | 2 | 2016/04/20 | 1 year ago | Easy to use menu structure for cli applications that prompts users to make choices. |
| [sflags](https://github.com/octago/sflags) | 131 | 6 | 2016/12/04 | 2 weeks ago | Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries. |
| [flag](https://github.com/cosiner/flag) | 115 | 6 | 2016/10/05 | 6 months ago | Simple but powerful command line option parsing library for Go supporting subcommand. |
| [clif](https://github.com/ukautz/clif) | 108 | 3 | 2015/05/30 | 2 years ago | Small command line interface framework. |
| [flag](https://github.com/zhuah/flag) | 102 | 5 | 2016/10/05 | 2 years ago | Simple but powerful command line option parsing library for Go supporting subcommand. |
| [job](https://github.com/liujianping/job) | 101 | 1 | 2019/04/09 | 1 year ago | JOB, make your short-term command as a long-term job. |
| [cli](https://github.com/teris-io/cli) | 90 | 2 | 2017/05/24 | 2 months ago | Simple and complete API for building command line interfaces in Go. |
| [env](https://github.com/codingconcepts/env) | 80 | 1 | 2017/06/14 | 10 months ago | Tag-based environment configuration for structs. |
| [cfmt](https://github.com/mingrammer/cfmt) | 78 | 3 | 2018/03/15 | 2 years ago | Contextual fmt inspired by bootstrap color classes. |
| [cmdr](https://github.com/hedzr/cmdr) | 76 | 4 | 2019/05/15 | 2 weeks ago | A POSIX/GNU style, getopt-like command-line UI Go library. |
| [clir](https://github.com/leaanthony/clir) | 73 | 2 | 2019/11/18 | 1 month ago | A Simple and Clear CLI library. Dependency free. |
| [tabular](https://github.com/InVisionApp/tabular) | 55 | 97 | 2018/04/23 | 3 years ago | Print ASCII tables from command line utilities without the need to pass large sets of data to the API. |
| [gocmd](https://github.com/devfacet/gocmd) | 52 | 3 | 2018/01/08 | 2 months ago | Go library for building command line applications. |
| [wlog](https://github.com/dixonwille/wlog) | 51 | 1 | 2016/04/13 | 1 year ago | Simple logging interface that supports cross-platform color and concurrency. |
| [strumt](https://github.com/antham/strumt) | 44 | 1 | 2017/06/19 | 2 months ago | Library to create prompt chain. |
| [flagvar](https://github.com/sgreben/flagvar) | 36 | 2 | 2018/05/18 | 1 year ago | A collection of flag argument types for Go's standard `flag` package. |
| [go-getoptions](https://github.com/DavidGamba/go-getoptions) | 36 | 4 | 2015/12/18 | 2 weeks ago | Go option parser inspired on the flexibility of Perl’s GetOpt::Long. |
| [cmd](https://github.com/posener/cmd) | 33 | 2 | 2019/10/29 | 9 months ago | Extends the standard `flag` package to support sub commands and more in idomatic way. |
| [ctc](https://github.com/wzshiming/ctc) | 33 | 1 | 2018/04/27 | 1 year ago | The non-invasive cross-platform terminal color library does not need to modify the Print method. |
| [argv](https://github.com/cosiner/argv) | 30 | 1 | 2017/01/22 | 1 year ago | Go library to split command line string as arguments array using the bash syntax. |
| [cfmt](https://github.com/i582/cfmt) | 27 | 2 | 2020/11/13 | 1 week ago | Simple and convenient formatted stylized output fully compatible with fmt library. |
| [colourize](https://github.com/TreyBastian/colourize) | 24 | 3 | 2015/05/11 | 5 years ago | Go library for ANSI colour text in terminals. |
| [go-commander](https://github.com/yitsushi/go-commander) | 23 | 1 | 2016/10/10 | 1 year ago | Go library to simplify CLI workflow. |
| [argv](https://github.com/zhuah/argv) | 19 | 1 | 2017/01/22 | 2 years ago | Go library to split command line string as arguments array using the bash syntax. |
| [sand](https://github.com/Zaba505/sand) | 15 | 1 | 2018/11/18 | 2 years ago | Simple API for creating interpreters and so much more. |
| [ts](https://github.com/liujianping/ts) | 13 | 0 | 2019/06/25 | 2 years ago | Timestamp convert & compare tool. |
| [go-ataman](https://github.com/workanator/go-ataman) | 9 | 2 | 2017/05/17 | 6 months ago | Go library for rendering ANSI colored text templates in terminals. |
| [table](https://github.com/tomlazar/table) | 8 | 1 | 2020/09/22 | 4 months ago | Small library for terminal color based tables . |

## Configuration
        
*Libraries for configuration parsing.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [viper](https://github.com/spf13/viper) | 16139 | 239 | 2014/04/02 | 21 hours ago | Go configuration with fangs. |
| [godotenv](https://github.com/joho/godotenv) | 3963 | 41 | 2013/07/30 | 1 month ago | Go port of Ruby's dotenv library (Loads environment variables from `.env`). |
| [envconfig](https://github.com/kelseyhightower/envconfig) | 3673 | 41 | 2013/11/06 | 2 weeks ago | Go library for managing configuration data from environment variables. |
| [ini](https://github.com/go-ini/ini) | 2537 | 76 | 2014/12/18 | 3 weeks ago | Go package to read and write INI files. |
| [env](https://github.com/caarlos0/env) | 1935 | 25 | 2015/07/28 | 3 days ago | Parse environment variables to Go structs (with defaults). |
| [konfig](https://github.com/lalamove/konfig) | 610 | 14 | 2019/01/18 | 8 months ago | Composable, observable and performant config handling for Go for the distributed processing era. |
| [koanf](https://github.com/knadh/koanf) | 533 | 10 | 2019/06/18 | 4 days ago | Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line. |
| [confita](https://github.com/heetch/confita) | 399 | 25 | 2017/12/21 | 2 weeks ago | Load configuration in cascade from multiple backends into a struct. |
| [cleanenv](https://github.com/ilyakaznacheev/cleanenv) | 313 | 7 | 2019/07/12 | 2 days ago | Minimalistic configuration reader (from files, ENV, and wherever you want). |
| [config](https://github.com/JeremyLoy/config) | 257 | 1 | 2019/04/02 | 2 months ago | Cloud native application configuration. Bind ENV to structs in only two lines. |
| [config](https://github.com/gookit/config) | 253 | 13 | 2018/07/07 | 1 month ago | application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge. |
| [store](https://github.com/tucnak/store) | 253 | 5 | 2015/10/03 | 3 years ago | Lightweight configuration manager for Go. |
| [config](https://github.com/olebedev/config) | 240 | 8 | 2014/04/21 | 1 month ago | JSON or YAML configuration wrapper with environment variables and flags parsing. |
| [hjson-go](https://github.com/hjson/hjson-go) | 238 | 9 | 2016/08/05 | 2 months ago | Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments. |
| [aconfig](https://github.com/cristalhq/aconfig) | 237 | 6 | 2020/06/26 | 1 hour ago | Simple, useful and opinionated config loader. |
| [config](https://github.com/joshbetz/config) | 205 | 2 | 2017/04/02 | 1 year ago | Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP. |
| [envconfig](https://github.com/vrischmann/envconfig) | 203 | 5 | 2015/04/21 | 6 months ago | Read your configuration from environment variables. |
| [fig](https://github.com/kkyr/fig) | 157 | 5 | 2020/01/16 | 1 month ago | Tiny library for reading configuration from a file and from environment variables (with validation & defaults). |
| [gcfg](https://github.com/go-gcfg/gcfg) | 150 | 8 | 2015/08/17 | 1 week ago | read INI-style configuration files into Go structs; supports user-defined types and subsections. |
| [goconfig](https://github.com/gosidekick/goconfig) | 148 | 14 | 2016/12/18 | 10 months ago | Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file. |
| [config](https://github.com/golobby/config) | 147 | 5 | 2019/10/15 | 3 months ago | A lightweight yet powerful config package for Go projects. |
| [goconfig](https://github.com/crgimenes/goconfig) | 131 | 11 | 2016/12/18 | 1 year ago | Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file. |
| [xdg](https://github.com/adrg/xdg) | 112 | 4 | 2014/08/22 | 3 months ago | Go implementation of the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) and [XDG user directories](https://wiki.archlinux.org/index.php/XDG_user_directories). |
| [envh](https://github.com/antham/envh) | 95 | 3 | 2017/01/12 | 2 months ago | Helpers to manage environment variables. |
| [envcfg](https://github.com/tomazk/envcfg) | 93 | 1 | 2014/11/29 | 4 years ago | Un-marshaling environment variables to Go structs. |
| [harvester](https://github.com/beatlabs/harvester) | 85 | 13 | 2019/04/09 | 9 hours ago | Harvester, a easy to use static and dynamic configuration package supportig seeding, env vars and Consul integration. |
| [configuro](https://github.com/sherifabdlnaby/configuro) | 73 | 4 | 2020/04/09 | 4 months ago | opinionated configuration loading & validation framework from ENV and Files focused towards 12-Factor compliant applications. |
| [xdg](https://github.com/OpenPeeDeeP/xdg) | 63 | 3 | 2017/07/20 | 8 months ago | Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html). |
| [gofigure](https://github.com/ian-kent/gofigure) | 59 | 5 | 2014/11/25 | 1 year ago | Go application configuration made easy. |
| [configure](https://github.com/paked/configure) | 54 | 3 | 2015/06/14 | 2 years ago | Provides configuration through multiple sources, including JSON, flags and environment variables. |
| [go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) | 41 | 20 | 2019/01/24 | 3 months ago | Go package that fetches parameters from AWS System Manager - Parameter Store. |
| [configuration](https://github.com/BoRuDar/configuration) | 39 | 2 | 2019/11/27 | 11 months ago | Library for initializing configuration structs from env variables, files, flags and 'default' tag. |
| [ingo](https://github.com/schachmat/ingo) | 35 | 1 | 2016/02/07 | 4 years ago | Flags persisted in an ini-like config file. |
| [go-up](https://github.com/ufoscout/go-up) | 32 | 1 | 2018/02/18 | 1 year ago | A simple configuration library with recursive placeholders resolution and no magic. |
| [mini](https://github.com/sasbury/mini) | 28 | 1 | 2015/04/29 | 2 years ago | Golang package for parsing ini-style configuration files. |
| [hocon](https://github.com/gurkankaymak/hocon) | 27 | 1 | 2020/03/01 | 3 weeks ago | Configuration library for working with the HOCON(a human-friendly JSON superset) format, supports features like environment variables, referencing other values, comments and multiple files. |
| [genv](https://github.com/sakirsensoy/genv) | 23 | 2 | 2019/07/15 | 1 year ago | Read environment variables easily with dotenv support. |
| [conflate](https://github.com/the4thamigo-uk/conflate) | 19 | 0 | 2018/02/01 | 9 months ago | Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema. |
| [envconf](https://github.com/ian-kent/envconf) | 10 | 1 | 2014/10/26 | 6 years ago | Configuration from environment. |
| [go-ssm-config](https://github.com/ianlopshire/go-ssm-config) | 10 | 1 | 2019/12/02 | 6 months ago | Go utility for loading configuration parameters from AWS SSM (Parameter Store). |
| [env](https://github.com/nasermirzaei89/env) | 5 | 0 | 2019/07/24 | 9 months ago | Simple useful package for read environment variables. |
| [go-ini](https://github.com/subpop/go-ini) | 5 | 1 | 2019/09/11 | 3 months ago | A Go package that marshals and unmarshals INI-files. |
| [sprbox](https://github.com/oblq/sprbox) | 4 | 2 | 2018/07/17 | 1 year ago | Build-environment aware toolbox factory and agnostic config parser (YAML, TOML, JSON and Environment vars). |
| [swap](https://github.com/oblq/swap) | 4 | 2 | 2020/04/12 | 4 months ago | Instantiate/configure structs recursively, based on build environment. (YAML, TOML, JSON and env). |
| [typenv](https://github.com/diegomarangoni/typenv) | 4 | 1 | 2020/06/30 | 11 months ago | Minimalistic, zero dependency, typed environment variables library. |

## Continuous Integration
        
*Tools for help with continuous integration.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [drone](https://github.com/drone/drone) | 23506 | 569 | 2014/02/07 | 4 days ago | Drone is a Continuous Integration platform built on Docker, written in Go. |
| [cds](https://github.com/ovh/cds) | 3471 | 87 | 2016/10/11 | 2 hours ago | Enterprise-Grade CI/CD and DevOps Automation Open Source Platform. |
| [goveralls](https://github.com/mattn/goveralls) | 692 | 13 | 2013/04/17 | 1 day ago | Go integration for Coveralls.io continuous code coverage tracking system. |
| [overalls](https://github.com/go-playground/overalls) | 106 | 4 | 2015/07/30 | 1 year ago | Multi-Package go project coverprofile for tools like goveralls. |
| [duci](https://github.com/duck8823/duci) | 66 | 3 | 2018/04/01 | 3 weeks ago | A simple ci server no needs domain specific languages. |
| [gomason](https://github.com/nikogura/gomason) | 50 | 1 | 2017/11/18 | 3 days ago | Test, Build, Sign, and Publish your go binaries from a clean workspace. |
| [roveralls](https://github.com/lawrencewoodman/roveralls) | 14 | 1 | 2016/06/26 | 3 years ago | Recursive coverage testing tool. |

## CSS Preprocessors
        
*Libraries for preprocessing CSS files.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gcss](https://github.com/yosssi/gcss) | 442 | 16 | 2014/09/04 | 6 years ago | Pure Go CSS Preprocessor. |
| [go-libsass](https://github.com/wellington/go-libsass) | 179 | 8 | 2015/04/19 | 8 months ago | Go wrapper to the 100% Sass compatible libsass project. |

## Data Structures
        
*Generic datastructures and algorithms in Go.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gods](https://github.com/emirpasic/gods) | 10187 | 349 | 2015/03/04 | 2 months ago | Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc. |
| [go-datastructures](https://github.com/Workiva/go-datastructures) | 6090 | 329 | 2014/10/29 | 2 months ago | Collection of useful, performant, and thread-safe data structures. |
| [golang-set](https://github.com/deckarep/golang-set) | 1999 | 43 | 2013/07/03 | 3 months ago | Thread-Safe and Non-Thread-Safe high-performance sets for Go. |
| [gota](https://github.com/go-gota/gota) | 1662 | 77 | 2016/02/06 | 6 days ago | Implementation of dataframes, series, and data wrangling methods for Go. |
| [BoomFilters](https://github.com/tylertreat/BoomFilters) | 1362 | 39 | 2015/02/06 | 3 months ago | Probabilistic data structures for processing continuous, unbounded streams. |
| [roaring](https://github.com/RoaringBitmap/roaring) | 1245 | 39 | 2014/07/10 | 6 days ago | Go package implementing compressed bitsets. |
| [bloom](https://github.com/bits-and-blooms/bloom) | 1230 | 37 | 2011/05/21 | 3 weeks ago | Go package implementing Bloom filters. |
| [bloom](https://github.com/willf/bloom) | 1012 | 36 | 2011/05/21 | 2 months ago | Go package implementing Bloom filters. |
| [gocache](https://github.com/eko/gocache) | 888 | 21 | 2019/10/05 | 1 week ago | A complete Go cache library with mutiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more. |
| [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) | 804 | 17 | 2015/06/28 | 6 months ago | Cuckoo filter: a good alternative to a counting bloom filter implemented in Go. |
| [hyperloglog](https://github.com/axiomhq/hyperloglog) | 749 | 17 | 2017/06/18 | 1 year ago | HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction. |
| [bitset](https://github.com/bits-and-blooms/bitset) | 699 | 30 | 2011/05/11 | 3 weeks ago | Go package implementing bitsets. |
| [bitset](https://github.com/willf/bitset) | 662 | 30 | 2011/05/11 | 3 months ago | Go package implementing bitsets. |
| [trie](https://github.com/derekparker/trie) | 539 | 21 | 2014/03/06 | 11 months ago | Trie implementation in Go. |
| [algorithms](https://github.com/shady831213/algorithms) | 534 | 19 | 2018/01/31 | 3 months ago | Algorithms and data structures.CLRS study. |
| [go-geoindex](https://github.com/hailocab/go-geoindex) | 330 | 67 | 2015/01/22 | 3 years ago | In-memory geo index. |
| [gostl](https://github.com/liyue201/gostl) | 289 | 10 | 2019/10/12 | 6 months ago | Data structure and algorithm library for go, designed to provide functions similar to C++ STL. |
| [mafsa](https://github.com/smartystreets-archives/mafsa) | 283 | 16 | 2014/11/07 | 2 years ago | MA-FSA implementation with Minimal Perfect Hashing. |
| [go-edlib](https://github.com/hbollon/go-edlib) | 269 | 9 | 2020/08/18 | 1 month ago | Go string comparison and edit distance algorithms library (Levenshtein, LCS, Hamming, Damerau levenshtein, Jaro-Winkler, etc.) compatible with Unicode. |
| [merkletree](https://github.com/cbergoon/merkletree) | 253 | 7 | 2017/04/12 | 1 year ago | Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures. |
| [ttlcache](https://github.com/ReneKroon/ttlcache) | 249 | 10 | 2014/12/13 | 2 days ago | In-memory string-interface{} cache with various time-based expiration options and callbacks. |
| [hilbert](https://github.com/google/hilbert) | 234 | 22 | 2015/08/06 | 2 years ago | Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves. |
| [goskiplist](https://github.com/ryszard/goskiplist) | 226 | 15 | 2012/05/09 | 1 year ago | Skip list implementation in Go. |
| [deque](https://github.com/gammazero/deque) | 225 | 6 | 2018/04/24 | 2 months ago | Fast ring-buffer deque (double-ended queue). |
| [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) | 184 | 8 | 2016/04/01 | 11 months ago | Go implementation of Adaptive Radix Tree. |
| [binpacker](https://github.com/zhuangsirui/binpacker) | 165 | 13 | 2016/02/02 | 5 days ago | Binary packer and unpacker helps user build custom binary stream. |
| [skiplist](https://github.com/MauriceGit/skiplist) | 159 | 6 | 2018/06/23 | 1 year ago | Very fast Go Skiplist implementation. |
| [levenshtein](https://github.com/agnivade/levenshtein) | 145 | 4 | 2014/07/30 | 1 month ago | Implementation to calculate levenshtein distance in Go. |
| [bloom](https://github.com/zentures/bloom) | 144 | 9 | 2013/09/03 | 3 years ago | Bloom filters implemented in Go. |
| [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) | 139 | 2 | 2019/01/10 | 1 year ago | Concurrent FIFO queue. |
| [iter](https://github.com/disksing/iter) | 136 | 5 | 2019/10/20 | 1 year ago | Go implementation of C++ STL iterators and algorithms. |
| [ring](https://github.com/tannerryan/ring) | 119 | 1 | 2019/01/27 | 10 months ago | Go implementation of a high performance, thread safe bloom filter. |
| [go-rquad](https://github.com/arl/go-rquad) | 116 | 4 | 2016/09/12 | 1 year ago | Region quadtrees with efficient point location and neighbour finding. |
| [ring](https://github.com/TheTannerRyan/ring) | 110 | 1 | 2019/01/27 | 1 year ago | Go implementation of a high performance, thread safe bloom filter. |
| [encoding](https://github.com/zentures/encoding) | 108 | 7 | 2013/09/20 | 3 years ago | Integer Compression Libraries for Go. |
| [bit](https://github.com/yourbasic/bit) | 105 | 8 | 2017/05/03 | 3 years ago | Golang set data structure with bonus bit-twiddling functions. |
| [remember-go](https://github.com/rocketlaunchr/remember-go) | 98 | 5 | 2019/04/04 | 2 months ago | A universal interface for caching slow database queries (backed by redis, memcached, ristretto, or in-memory). |
| [conjungo](https://github.com/InVisionApp/conjungo) | 94 | 107 | 2016/12/29 | 8 months ago | A small, powerful and flexible merge library. |
| [skiplist](https://github.com/gansidui/skiplist) | 72 | 8 | 2014/11/18 | 6 years ago | Skiplist implementation in Go. |
| [go-mcache](https://github.com/OrlovEvgeny/go-mcache) | 68 | 3 | 2018/04/14 | 1 year ago | Fast in-memory key:value store/cache library. Pointer caches. |
| [bloom](https://github.com/yourbasic/bloom) | 62 | 3 | 2017/05/06 | 4 years ago | Golang Bloom filter implementation. |
| [levenshtein](https://github.com/agext/levenshtein) | 59 | 2 | 2016/04/08 | 9 months ago | Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix. |
| [count-min-log](https://github.com/seiflotfy/count-min-log) | 53 | 2 | 2015/08/16 | 4 years ago | Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory). |
| [crunch](https://github.com/superwhiskers/crunch) | 44 | 6 | 2019/02/27 | 3 months ago | Go package implementing buffers for handling various datatypes easily. |
| [nan](https://github.com/kak-tus/nan) | 36 | 3 | 2020/05/05 | 8 months ago | Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers. |
| [concurrent-writer](https://github.com/free/concurrent-writer) | 34 | 5 | 2017/09/18 | 3 years ago | Highly concurrent drop-in replacement for `bufio.Writer`. |
| [hide](https://github.com/emvi/hide) | 34 | 4 | 2019/01/16 | 5 months ago | ID type with marshalling to/from hash to prevent sending IDs to clients. |
| [goset](https://github.com/zoumo/goset) | 33 | 1 | 2017/08/25 | 7 months ago | A useful Set collection implementation for Go. |
| [pipeline](https://github.com/hyfather/pipeline) | 30 | 2 | 2018/04/25 | 2 years ago | An implementation of pipelines with fan-in and fan-out. |
| [deque](https://github.com/edwingeng/deque) | 28 | 3 | 2019/02/01 | 2 months ago | A highly optimized double-ended queue. |
| [typ](https://github.com/gurukami/typ) | 28 | 2 | 2019/03/03 | 1 year ago | Null Types, Safe primitive type conversion and fetching value from complex structures. |
| [timedmap](https://github.com/zekroTJA/timedmap) | 26 | 2 | 2019/01/30 | 1 month ago | Map with expiring key-value pairs. |
| [dict](https://github.com/srfrog/dict) | 19 | 0 | 2019/04/23 | 8 months ago | Python-like dictionaries (dict) for Go. |
| [null](https://github.com/emvi/null) | 19 | 3 | 2018/07/04 | 5 months ago | Nullable Go types that can be marshalled/unmarshalled to/from JSON. |
| [go-ef](https://github.com/amallia/go-ef) | 18 | 2 | 2017/09/22 | 3 years ago | A Go implementation of the Elias-Fano encoding. |
| [mspm](https://github.com/BlackRabbitt/mspm) | 16 | 3 | 2018/05/17 | 3 years ago | Multi-String Pattern Matching Algorithm for information retrieval. |
| [ptrie](https://github.com/viant/ptrie) | 15 | 8 | 2019/05/20 | 10 months ago | An implementation of prefix tree. |
| [set](https://github.com/StudioSol/set) | 15 | 20 | 2018/07/20 | 8 months ago | Simple set data structure implementation in Go using LinkedHashMap. |
| [cmap](https://github.com/lrita/cmap) | 15 | 1 | 2019/11/26 | 10 months ago | a thread-safe concurrent map for go, support using `interface{}` as key and auto scale up shards. |
| [treap](https://github.com/perdata/treap) | 11 | 3 | 2018/09/16 | 1 year ago | Persistent, fast ordered map using tree heaps. |
| [gofal](https://github.com/xxjwxc/gofal) | 9 | 2 | 2019/08/05 | 1 year ago | fractional api for Go. |
| [parsefields](https://github.com/MonaxGT/parsefields) | 6 | 1 | 2019/04/12 | 2 years ago | Tools for parse JSON-like logs for collecting unique fields and events. |
| [goterator](https://github.com/yaa110/goterator) | 4 | 1 | 2020/08/12 | 7 months ago | Iterator implementation to provide map and reduce functionalities. |
| [slices](https://github.com/srfrog/slices) | 3 | 2 | 2020/07/02 | 8 months ago | Functions that operate on slices; like `package strings` but adapted to work with slices. |

## Database
        
*SQL query builder, libraries for building and using SQL.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [prometheus](https://github.com/prometheus/prometheus) | 37589 | 1146 | 2012/11/24 | 2 hours ago | Monitoring system and time series database. |
| [tidb](https://github.com/pingcap/tidb) | 28349 | 1350 | 2015/09/06 | 1 hour ago | TiDB is a distributed SQL database. Inspired by the design of Google F1. |
| [influxdb](https://github.com/influxdata/influxdb) | 21746 | 761 | 2013/09/26 | 56 minutes ago | Scalable datastore for metrics, events, and real-time analytics. |
| [cockroach](https://github.com/cockroachdb/cockroach) | 20867 | 716 | 2014/02/06 | 51 minutes ago | Scalable, Geo-Replicated, Transactional Datastore. |
| [dgraph](https://github.com/dgraph-io/dgraph) | 16326 | 379 | 2015/08/25 | 1 hour ago | Scalable, Distributed, Low Latency, High Throughput Graph Database. |
| [vitess](https://github.com/vitessio/vitess) | 12157 | 514 | 2013/06/27 | 49 minutes ago | vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services. |
| [bolt](https://github.com/boltdb/bolt) | 10426 | 343 | 2013/12/20 | 3 years ago | Low-level key/value database for Go. |
| [groupcache](https://github.com/golang/groupcache) | 10422 | 502 | 2013/07/22 | 2 months ago | Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. |
| [badger](https://github.com/dgraph-io/badger) | 9443 | 249 | 2017/01/26 | 4 days ago | Fast key-value store in Go. |
| [rqlite](https://github.com/rqlite/rqlite) | 8578 | 231 | 2014/08/23 | 5 days ago | The lightweight, distributed, relational database built on SQLite. |
| [pgweb](https://github.com/sosedoff/pgweb) | 6925 | 147 | 2014/10/09 | 2 days ago | Web-based PostgreSQL database browser. |
| [migrate](https://github.com/golang-migrate/migrate) | 6730 | 75 | 2018/01/19 | 5 days ago | Database migrations. CLI and Golang library. |
| [kingshard](https://github.com/flike/kingshard) | 5732 | 406 | 2015/07/04 | 3 weeks ago | kingshard is a high performance proxy for MySQL powered by Golang. |
| [go-cache](https://github.com/patrickmn/go-cache) | 5146 | 112 | 2012/01/02 | 1 month ago | In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications. |
| [bigcache](https://github.com/allegro/bigcache) | 4963 | 120 | 2016/03/23 | 1 month ago | Efficient key/value cache for gigabytes of data. |
| [bbolt](https://github.com/etcd-io/bbolt) | 4602 | 123 | 2017/06/17 | 1 week ago | An embedded key/value database for Go. |
| [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) | 4531 | 105 | 2018/09/30 | 1 hour ago | fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL. |
| [goleveldb](https://github.com/syndtr/goleveldb) | 4439 | 179 | 2013/01/23 | 1 month ago | Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go. |
| [orchestrator](https://github.com/openark/orchestrator) | 4142 | 269 | 2016/11/30 | 1 week ago | MySQL replication topology manager & visualizer. |
| [squirrel](https://github.com/Masterminds/squirrel) | 4033 | 50 | 2014/01/18 | 1 week ago | Go library that helps you build SQL queries. |
| [ledisdb](https://github.com/ledisdb/ledisdb) | 3667 | 185 | 2014/04/30 | 4 months ago | Ledisdb is a high performance NoSQL like Redis based on LevelDB. |
| [go-mysql-elasticsearch](https://github.com/go-mysql-org/go-mysql-elasticsearch) | 3517 | 182 | 2015/01/15 | 5 months ago | Sync your MySQL data into Elasticsearch automatically. |
| [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) | 3419 | 178 | 2015/01/15 | 5 months ago | Sync your MySQL data into Elasticsearch automatically. |
| [orchestrator](https://github.com/github/orchestrator) | 3362 | 299 | 2016/11/30 | 1 year ago | MySQL replication topology manager & visualizer. |
| [buntdb](https://github.com/tidwall/buntdb) | 3336 | 99 | 2016/07/19 | 3 weeks ago | Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support. |
| [ledisdb](https://github.com/siddontang/ledisdb) | 3265 | 188 | 2014/04/30 | 1 year ago | Ledisdb is a high performance NoSQL like Redis based on LevelDB. |
| [go-mysql](https://github.com/go-mysql-org/go-mysql) | 3136 | 163 | 2014/02/21 | 9 hours ago | Go toolset to handle MySQL protocol and replication. |
| [immudb](https://github.com/codenotary/immudb) | 2938 | 50 | 2019/11/07 | 3 hours ago | immudb is a lightweight, high-speed immutable database for systems and applications written in Go. |
| [go-mysql](https://github.com/siddontang/go-mysql) | 2922 | 161 | 2014/02/21 | 3 months ago | Go toolset to handle MySQL protocol and replication. |
| [xo](https://github.com/xo/xo) | 2813 | 71 | 2016/02/05 | 4 days ago | Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server. |
| [prest](https://github.com/prest/prest) | 2731 | 85 | 2016/11/22 | 4 days ago | Simplify and accelerate development, ⚡ instant, realtime, high-performance on any Postgres application, existing or new. |
| [tiedot](https://github.com/HouzuoGuo/tiedot) | 2605 | 159 | 2013/05/26 | 1 year ago | Your NoSQL database powered by Golang. |
| [sql-migrate](https://github.com/rubenv/sql-migrate) | 2173 | 34 | 2014/09/09 | 4 weeks ago | Database migration tool. Allows embedding migrations into the application using go-bindata. |
| [goose](https://github.com/pressly/goose) | 1748 | 45 | 2016/02/25 | 2 weeks ago | Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts. |
| [nutsdb](https://github.com/xujiajun/nutsdb) | 1680 | 50 | 2018/12/07 | 3 months ago | Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as  list, set, sorted set. |
| [gcache](https://github.com/bluele/gcache) | 1598 | 43 | 2015/01/24 | 1 week ago | Cache library with support for expirable Cache, LFU, LRU and ARC. |
| [cache2go](https://github.com/muesli/cache2go) | 1570 | 68 | 2013/11/11 | 1 month ago | In-memory key:value cache which supports automatic invalidation based on timeouts. |
| [gendry](https://github.com/didi/gendry) | 1240 | 63 | 2017/12/01 | 2 months ago | Non-invasive SQL builder and powerful data binder. |
| [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) | 1196 | 72 | 2018/04/11 | 4 months ago | CovenantSQL is a SQL database on blockchain. |
| [fastcache](https://github.com/VictoriaMetrics/fastcache) | 1178 | 29 | 2018/11/22 | 5 days ago | fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead. |
| [goqu](https://github.com/doug-martin/goqu) | 1097 | 35 | 2015/02/21 | 2 weeks ago | Idiomatic SQL builder and query library. |
| [diskv](https://github.com/peterbourgon/diskv) | 1072 | 38 | 2012/03/21 | 2 months ago | Home-grown disk-backed key-value store. |
| [skeema](https://github.com/skeema/skeema) | 915 | 30 | 2016/10/31 | 4 hours ago | Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools. |
| [databunker](https://github.com/securitybunker/databunker) | 858 | 26 | 2019/12/08 | 22 hours ago | Personally identifiable information (PII) storage service built to comply with GDPR and CCPA. |
| [eliasdb](https://github.com/krotik/eliasdb) | 818 | 26 | 2016/08/13 | 1 month ago | Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language. |
| [moss](https://github.com/couchbase/moss) | 816 | 75 | 2016/02/06 | 5 months ago | Moss is a simple LSM key-value storage engine written in 100% Go. |
| [pogreb](https://github.com/akrylysov/pogreb) | 799 | 26 | 2018/01/06 | 2 months ago | Embedded key-value store for read-heavy workloads. |
| [chproxy](https://github.com/Vertamedia/chproxy) | 646 | 30 | 2017/09/18 | 1 week ago | HTTP proxy for ClickHouse database. |
| [gormigrate](https://github.com/go-gormigrate/gormigrate) | 633 | 7 | 2016/08/31 | 1 week ago | Database schema migration helper for Gorm ORM. |
| [dotsql](https://github.com/gchaincl/dotsql) | 592 | 25 | 2014/11/20 | 4 months ago | Go library that helps you keep sql files in one place and use them with ease. |
| [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) | 536 | 28 | 2015/12/10 | 5 months ago | Powerful data retrieval methods as well as DB-agnostic query building capabilities. |
| [jet](https://github.com/go-jet/jet) | 427 | 11 | 2019/03/02 | 1 month ago | Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure. |
| [pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) | 417 | 15 | 2018/12/19 | 9 hours ago | Advanced scheduling for PostgreSQL. |
| [levigo](https://github.com/jmhodges/levigo) | 398 | 23 | 2012/01/17 | 1 year ago | Levigo is a Go wrapper for LevelDB. |
| [dbq](https://github.com/rocketlaunchr/dbq) | 302 | 10 | 2019/07/11 | 4 months ago | Zero boilerplate database operations for Go. |
| [pudge](https://github.com/recoilme/pudge) | 290 | 11 | 2018/11/20 | 1 week ago | Fast and simple  key/value store written using Go's standard library. |
| [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) | 288 | 7 | 2017/04/29 | 2 months ago | Collects small insterts and sends big requests to ClickHouse servers. |
| [sqrl](https://github.com/elgris/sqrl) | 226 | 8 | 2014/06/25 | 5 months ago | SQL query builder, fork of Squirrel with improved performance. |
| [vasto](https://github.com/chrislusf/vasto) | 214 | 19 | 2018/01/16 | 2 years ago | A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption. |
| [kivik](https://github.com/go-kivik/kivik) | 211 | 5 | 2017/02/09 | 1 month ago | Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases. |
| [piladb](https://github.com/fern4lvarez/piladb) | 188 | 12 | 2015/09/08 | 8 months ago | Lightweight RESTful database engine based on stack data structures. |
| [myreplication](https://github.com/2tvenom/myreplication) | 173 | 20 | 2015/02/04 | 2 years ago | MySql binary log replication listener. Supports statement and row based replication. |
| [sqlingo](https://github.com/lqs/sqlingo) | 154 | 13 | 2018/11/18 | 1 month ago | A lightweight DSL to build SQL in Go. |
| [goose](https://github.com/steinbacher/goose) | 144 | 4 | 2016/03/04 | 4 years ago | Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts. |
| [octillery](https://github.com/blastrain/octillery) | 140 | 18 | 2018/11/26 | 1 month ago | Go package for sharding databases ( Supports every ORM or raw SQL ). |
| [golang-scribble](https://github.com/nanobox-io/golang-scribble) | 128 | 5 | 2018/06/21 | 2 years ago | Tiny flat file JSON store. |
| [darwin](https://github.com/GuiaBolso/darwin) | 119 | 3 | 2016/04/05 | 3 months ago | Database schema evolution library for Go. |
| [migrator](https://github.com/lopezator/migrator) | 115 | 5 | 2019/02/04 | 9 months ago | Dead simple Go database migration library. |
| [go-structured-query](https://github.com/bokwoon95/go-structured-query) | 106 | 1 | 2020/05/30 | 1 week ago | Type-safe SQL builder and struct mapper for Go. |
| [slowpoke](https://github.com/recoilme/slowpoke) | 98 | 8 | 2018/02/19 | 1 year ago | Key-value store with persistence. |
| [databunker](https://github.com/paranoidguy/databunker) | 93 | 9 | 2019/12/08 | 7 months ago | Personally identifiable information (PII) storage service built to comply with GDPR and CCPA. |
| [octillery](https://github.com/knocknote/octillery) | 92 | 16 | 2018/11/26 | 11 months ago | Go package for sharding databases ( Supports every ORM or raw SQL ). |
| [cache](https://github.com/akyoto/cache) | 89 | 3 | 2019/05/11 | 1 year ago | In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage. |
| [igor](https://github.com/galeone/igor) | 85 | 7 | 2016/03/10 | 1 year ago | Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax. |
| [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) | 79 | 1 | 2018/08/11 | 4 months ago | A Go package to help write migrations with go-pg/pg. |
| [bcache](https://github.com/iwanbk/bcache) | 66 | 3 | 2018/12/26 | 2 years ago | Eventually consistent distributed in-memory  cache Go library. |
| [unitdb](https://github.com/unit-io/unitdb) | 65 | 5 | 2019/08/29 | 4 days ago | Fast timeseries database for IoT, realtime messaging  applications. Access unitdb with pubsub over tcp or websocket using github.com/unit-io/unitd application. |
| [dbbench](https://github.com/sj14/dbbench) | 59 | 4 | 2018/11/24 | 4 days ago | Database benchmarking tool with support for several databases and scripts. |
| [couchcache](https://github.com/codingsince1985/couchcache) | 53 | 3 | 2015/04/05 | 10 months ago | RESTful caching micro-service backed by Couchbase server. |
| [godbal](https://github.com/xujiajun/godbal) | 52 | 4 | 2018/02/28 | 2 years ago | Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily. |
| [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) | 37 | 6 | 2017/12/18 | 3 years ago | BigCache with clustering support and individual item expiration. |
| [buildsqlx](https://github.com/arthurkushman/buildsqlx) | 36 | 1 | 2019/08/18 | 2 months ago | Go database query builder library for PostgreSQL. |
| [datagen](https://github.com/codingconcepts/datagen) | 35 | 1 | 2019/04/18 | 1 year ago | A fast data generator that's multi-table aware and supports multi-row DML. |
| [gondolier](https://github.com/emvi/gondolier) | 31 | 4 | 2017/10/18 | 2 years ago | Database migration library using struct decorators. |
| [prep](https://github.com/hexdigest/prep) | 28 | 3 | 2017/12/11 | 3 years ago | Use prepared SQL statements without changing your code. |
| [go-fixtures](https://github.com/RichardKnop/go-fixtures) | 26 | 1 | 2015/12/24 | 1 year ago | Django style fixtures for Golang's excellent built-in database/sql library. |
| [coffer](https://github.com/claygod/coffer) | 25 | 5 | 2019/05/13 | 9 months ago | Simple ACID key-value database that supports transactions. |
| [avro](https://github.com/khezen/avro) | 24 | 2 | 2019/04/07 | 1 year ago | Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes. |
| [pravasan](https://github.com/pravasan/pravasan) | 24 | 7 | 2015/01/03 | 2 years ago | Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc. |
| [qry](https://github.com/HnH/qry) | 20 | 3 | 2019/08/20 | 9 months ago | Tool that generates constants from files with raw SQL queries. |
| [sqlf](https://github.com/leporo/sqlf) | 20 | 4 | 2019/07/20 | 1 year ago | Fast SQL query builder. |
| [gosql](https://github.com/twharmon/gosql) | 16 | 1 | 2020/01/08 | 10 months ago | SQL Query builder with better null values support. |
| [tempdb](https://github.com/rafaeljesus/tempdb) | 15 | 3 | 2017/03/17 | 3 years ago | Key-value store for temporary items. |
| [gorocksdb](https://github.com/kapitan-k/gorocksdb) | 12 | 1 | 2017/12/28 | 3 years ago | Gorocksdb is a wrapper for [RocksDB](https://rocksdb.org) written in Go. |
| [rwdb](https://github.com/andizzle/rwdb) | 12 | 2 | 2017/10/04 | 3 years ago | rwdb provides read replica capability for multiple database servers setup. |
| [mpath-go](https://github.com/spacetab-io/mpath-go) | 8 | 4 | 2020/01/09 | 1 year ago | MPTT (Modified Preorder Tree Traversal) package for SQL records - materialized path realisation. |
| [schema](https://github.com/adlio/schema) | 7 | 3 | 2019/09/24 | 6 months ago | Library to embed schema migrations for database/sql-compatible databases inside your Go binaries. |
| [bucket](https://github.com/PumpkinSeed/bucket) | 6 | 3 | 2019/09/22 | 1 year ago | Optimized data structure framework for Couchbase specialized on one bucket usage. |
| [gostore](https://github.com/twharmon/gostore) | 5 | 2 | 2020/01/08 | 1 year ago | Gostore is a simple, durable, embedded key-value storage engine written in Go. |
| [go-pg-migrate](https://github.com/lawzava/go-pg-migrate) | 4 | 1 | 2021/01/16 | 2 weeks ago | CLI-friendly package for go-pg migrations management. |
| [tracedb](https://github.com/unit-io/tracedb) | 3 | 1 | 2019/08/29 | 1 year ago | Fast timeseries database for IoT, realtime messaging  applications. Access tracedb with pubsub over tcp or websocket using github.com/unit-io/trace application. |
| [ttlcache](https://github.com/cheshir/ttlcache) | 3 | 1 | 2021/01/06 | 3 months ago | In-memory key value storage with TTL for each record. |
| [bitcask](https://github.com/prologic/bitcask) | 0 | 1 | 2019/03/12 | 2 hours ago | Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL). |
| [ormlite](https://github.com/pupizoid/ormlite) | 0 | 2 | 2018/06/28 | 6 months ago | Lightweight package containing some ORM-like features and helpers for sqlite databases. |

## Database Drivers
        
*Libraries for connecting and operating databases.*

### Relational Databases
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [mysql](https://github.com/go-sql-driver/mysql) | 11047 | 410 | 2012/12/09 | 1 hour ago | MySQL driver for Go. |
| [pq](https://github.com/lib/pq) | 6650 | 153 | 2012/03/12 | 3 weeks ago | Pure Go Postgres driver for database/sql. |
| [go-sqlite3](https://github.com/mattn/go-sqlite3) | 4947 | 151 | 2011/11/11 | 1 month ago | SQLite3 driver for go that uses database/sql. |
| [pgx](https://github.com/jackc/pgx) | 4255 | 81 | 2013/03/30 | 2 days ago | PostgreSQL driver supporting features beyond those exposed by database/sql. |
| [go-mssqldb](https://github.com/denisenkom/go-mssqldb) | 1413 | 69 | 2013/12/16 | 3 hours ago | Microsoft MSSQL driver for Go. |
| [go-oci8](https://github.com/mattn/go-oci8) | 551 | 41 | 2012/02/29 | 6 months ago | Oracle driver for go that uses database/sql. |
| [goracle](https://github.com/go-goracle/goracle) | 283 | 28 | 2015/03/25 | 1 year ago | Oracle driver for Go, using the ODPI-C driver. |
| [godror](https://github.com/godror/godror) | 264 | 17 | 2019/11/21 | 1 week ago | Oracle driver for Go, using the ODPI-C driver. |
| [firebirdsql](https://github.com/nakagami/firebirdsql) | 151 | 18 | 2013/08/27 | 22 hours ago | Firebird RDBMS SQL driver for Go. |
| [go-adodb](https://github.com/mattn/go-adodb) | 120 | 12 | 2011/11/14 | 1 year ago | Microsoft ActiveX Object DataBase driver for go that uses database/sql. |
| [gofreetds](https://github.com/minus5/gofreetds) | 104 | 22 | 2012/12/06 | 7 months ago | Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org). |
| [calcite-avatica-go](https://github.com/apache/calcite-avatica-go) | 74 | 26 | 2017/08/08 | 9 months ago | Apache Avatica/Phoenix SQL driver for database/sql. |
| [sqinn-go](https://github.com/cvilsmeier/sqinn-go) | 68 | 1 | 2020/06/06 | 1 month ago | SQLite with pure Go. |
| [bgc](https://github.com/viant/bgc) | 15 | 11 | 2016/06/13 | 1 year ago | Datastore Connectivity for BigQuery for go. |

### NoSQL Databases
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [cayley](https://github.com/cayleygraph/cayley) | 13851 | 605 | 2014/06/05 | 3 weeks ago | Graph database with support for multiple backends. |
| [redis](https://github.com/go-redis/redis) | 11940 | 247 | 2012/07/25 | 1 day ago | Redis client for Golang. |
| [redigo](https://github.com/gomodule/redigo) | 8496 | 297 | 2012/04/14 | 1 month ago | Redigo is a Go client for the Redis database. |
| [bleve](https://github.com/blevesearch/bleve) | 7639 | 258 | 2014/04/17 | 2 weeks ago | Modern text indexing library for go. |
| [elastic](https://github.com/olivere/elastic) | 6042 | 171 | 2012/12/06 | 4 days ago | Elasticsearch client for Go. |
| [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) | 5879 | 136 | 2017/02/08 | 1 hour ago | Official MongoDB driver for the Go language. |
| [riot](https://github.com/go-ego/riot) | 5858 | 200 | 2017/06/21 | 9 months ago | Go Open Source, Distributed, Simple and efficient Search Engine. |
| [go-elasticsearch](https://github.com/elastic/go-elasticsearch) | 3481 | 298 | 2017/03/27 | 3 hours ago | Official Elasticsearch client for Go. |
| [mgo](https://github.com/globalsign/mgo) | 1901 | 63 | 2017/04/13 | 4 months ago | (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms. |
| [rethinkdb-go](https://github.com/rethinkdb/rethinkdb-go) | 1564 | 48 | 2013/09/12 | 2 months ago | Go language driver for RethinkDB. |
| [elastigo](https://github.com/mattbaird/elastigo) | 948 | 47 | 2012/10/12 | 2 years ago | Elasticsearch client library. |
| [elasticsql](https://github.com/cch123/elasticsql) | 745 | 33 | 2016/08/24 | 8 months ago | Convert sql to elasticsearch dsl in Go. |
| [qmgo](https://github.com/qiniu/qmgo) | 526 | 9 | 2020/08/04 | 1 month ago | The MongoDB driver for Go. It‘s based on official MongoDB driver but easier to use like Mgo. |
| [redeo](https://github.com/bsm/redeo) | 397 | 26 | 2014/03/06 | 7 months ago | Redis-protocol compatible TCP servers/services. |
| [neoism](https://github.com/jmcvetta/neoism) | 376 | 25 | 2012/07/12 | 1 year ago | Neo4j client for Golang. |
| [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) | 366 | 41 | 2014/07/26 | 2 weeks ago | Aerospike client in Go language. |
| [gokv](https://github.com/philippgille/gokv) | 347 | 9 | 2018/10/08 | 8 months ago | Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more). |
| [mgm](https://github.com/Kamva/mgm) | 329 | 15 | 2019/12/27 | 3 weeks ago | MongoDB model-based ODM for Go (based on official MongoDB driver). |
| [gocb](https://github.com/couchbase/gocb) | 327 | 61 | 2015/01/15 | 2 hours ago | Official Couchbase Go SDK. |
| [go-couchbase](https://github.com/couchbase/go-couchbase) | 313 | 25 | 2012/01/19 | 2 weeks ago | Couchbase client in Go. |
| [go-rejson](https://github.com/nitishm/go-rejson) | 169 | 7 | 2018/04/23 | 3 months ago | Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease. |
| [cachego](https://github.com/faabiosr/cachego) | 155 | 7 | 2016/10/05 | 10 months ago | Golang Cache component for multiple drivers. |
| [godis](https://github.com/piaohao/godis) | 92 | 10 | 2019/06/14 | 1 year ago | redis client implement by golang, inspired by jedis. |
| [skizze](https://github.com/seiflotfy/skizze) | 78 | 7 | 2016/01/17 | 5 years ago | probabilistic data-structures service and storage. |
| [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) | 76 | 7 | 2011/06/04 | 3 years ago | Neo4j REST Client in golang. |
| [dynago](https://github.com/underarmour/dynago) | 71 | 124 | 2015/05/18 | 3 years ago | Dynago is a principle of least surprise client for DynamoDB. |
| [arangolite](https://github.com/solher/arangolite) | 69 | 6 | 2015/10/04 | 4 months ago | Lightweight golang driver for ArangoDB. |
| [go-pilosa](https://github.com/pilosa/go-pilosa) | 46 | 20 | 2016/09/30 | 1 year ago | Go client library for Pilosa. |
| [goforestdb](https://github.com/couchbase/goforestdb) | 30 | 39 | 2014/05/14 | 4 years ago | Go bindings for ForestDB. |
| [goriak](https://github.com/zegl/goriak) | 26 | 4 | 2016/10/05 | 1 month ago | Go language driver for Riak KV. |
| [neo4j](https://github.com/cihangir/neo4j) | 26 | 4 | 2013/05/18 | 6 years ago | Neo4j Rest API Bindings for Golang. |
| [goes](https://github.com/OwnLocal/goes) | 24 | 34 | 2015/12/28 | 8 months ago | Library to interact with Elasticsearch. |
| [dsc](https://github.com/viant/dsc) | 22 | 16 | 2016/06/13 | 1 year ago | Datastore connectivity for SQL, NoSQL, structured files. |
| [xredis](https://github.com/shomali11/xredis) | 15 | 2 | 2017/06/14 | 2 years ago | Typesafe, customizable, clean & easy to use Redis client. |
| [godscache](https://github.com/defcronyke/godscache) | 9 | 3 | 2018/05/08 | 2 years ago | A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached. |
| [asc](https://github.com/viant/asc) | 6 | 11 | 2016/06/13 | 2 years ago | Datastore Connectivity for Aerospike for go. |
| [gocosmos](https://github.com/btnguyen2k/gocosmos) | 3 | 2 | 2020/12/06 | 3 days ago | REST client and standard `database/sql` driver for Azure Cosmos DB. |

## Date and Time
        
*Libraries for working with dates and times.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [now](https://github.com/jinzhu/now) | 3157 | 62 | 2013/11/18 | 1 month ago | Now is a time toolkit for golang. |
| [dateparse](https://github.com/araddon/dateparse) | 1454 | 20 | 2014/04/21 | 3 weeks ago | Parse date's without knowing format in advance. |
| [carbon](https://github.com/uniplaces/carbon) | 600 | 43 | 2016/08/03 | 3 weeks ago | Simple Time extension with a lot of util methods, ported from PHP Carbon library. |
| [durafmt](https://github.com/hako/durafmt) | 390 | 6 | 2016/05/20 | 1 month ago | Time duration formatting library for Go. |
| [timeutil](https://github.com/leekchan/timeutil) | 186 | 8 | 2015/08/02 | 2 years ago | Useful extensions (Timedelta, Strftime, ...) to the golang's time package. |
| [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) | 97 | 4 | 2016/01/31 | 1 month ago | The implementation of the Persian (Solar Hijri) Calendar in Go (golang). |
| [iso8601](https://github.com/relvacode/iso8601) | 92 | 4 | 2017/04/25 | 1 week ago | Efficiently parse ISO8601 date-times without regex. |
| [timespan](https://github.com/SaidinWoT/timespan) | 74 | 6 | 2014/10/07 | 2 years ago | For interacting with intervals of time, defined as a start time and a duration. |
| [date](https://github.com/rickb777/date) | 72 | 3 | 2015/11/23 | 3 months ago | Augments Time for working with dates, date ranges, time spans, periods, and time-of-day. |
| [feiertage](https://github.com/wlbr/feiertage) | 39 | 3 | 2015/11/04 | 9 months ago | Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving... |
| [go-sunrise](https://github.com/nathan-osman/go-sunrise) | 35 | 5 | 2017/06/15 | 1 month ago | Calculate the sunrise and sunset times for a given location. |
| [go-str2duration](https://github.com/xhit/go-str2duration) | 25 | 3 | 2020/02/02 | 11 months ago | Convert string to duration. Support time.Duration returned string and more. |
| [kair](https://github.com/GuilhermeCaruso/kair) | 19 | 1 | 2018/10/03 | 1 year ago | Date and Time - Golang Formatting Library. |
| [nulltime](https://github.com/kirillDanshin/nulltime) | 11 | 2 | 2016/03/06 | 4 years ago | Nullable `time.Time`. |
| [cronrange](https://github.com/1set/cronrange) | 10 | 2 | 2019/11/10 | 1 year ago | Parses Cron-style time range expressions, checks if the given time is within any ranges. |
| [tuesday](https://github.com/osteele/tuesday) | 9 | 3 | 2017/08/10 | 3 weeks ago | Ruby-compatible Strftime function. |
| [strftime](https://github.com/awoodbeck/strftime) | 7 | 2 | 2018/02/10 | 3 years ago | C99-compatible strftime formatter. |
| [go-week](https://github.com/stoewer/go-week) | 5 | 4 | 2018/02/23 | 1 year ago | An efficient package to work with ISO8601 week dates. |

## Distributed Systems
        
*Packages that help with building Distributed Systems.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [kit](https://github.com/go-kit/kit) | 20613 | 694 | 2015/02/03 | 1 day ago | Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc. |
| [go-micro](https://github.com/asim/go-micro) | 16284 | 512 | 2015/01/13 | 10 hours ago | A distributed systems development framework. |
| [nitro](https://github.com/gonitro/nitro) | 14946 | 498 | 2015/01/13 | 7 months ago | A distributed systems development framework. |
| [nitro](https://github.com/asim/nitro) | 14898 | 498 | 2015/01/13 | 7 months ago | A distributed systems development framework. |
| [go-micro](https://github.com/micro/go-micro) | 14444 | 485 | 2015/01/13 | 9 months ago | A distributed systems development framework. |
| [grpc-go](https://github.com/grpc/grpc-go) | 14043 | 492 | 2014/12/08 | 3 days ago | The Go language implementation of gRPC. HTTP/2 based RPC. |
| [micro](https://github.com/micro/micro) | 10216 | 337 | 2015/01/16 | 1 day ago | A distributed systems runtime for the cloud and beyond. |
| [nats-server](https://github.com/nats-io/nats-server) | 9565 | 379 | 2012/10/29 | 22 hours ago | Lightweight, high performance messaging system for microservices, IoT, and cloud native systems. |
| [rpcx](https://github.com/smallnest/rpcx) | 5786 | 343 | 2016/05/18 | 1 week ago | Distributed pluggable RPC service framework like alibaba Dubbo. |
| [raft](https://github.com/hashicorp/raft) | 4866 | 344 | 2013/11/05 | 2 weeks ago | Golang implementation of the Raft consensus protocol, by HashiCorp. |
| [lura](https://github.com/luraproject/lura) | 4307 | 117 | 2016/11/04 | 1 day ago | Ultra performant API Gateway framework with middlewares. |
| [tendermint](https://github.com/tendermint/tendermint) | 4207 | 260 | 2014/05/14 | 59 minutes ago | High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols. |
| [torrent](https://github.com/anacrolix/torrent) | 3936 | 132 | 2015/01/08 | 1 day ago | BitTorrent client package. |
| [krakend](https://github.com/devopsfaith/krakend) | 3891 | 112 | 2016/11/04 | 2 months ago | Ultra performant API Gateway framework with middlewares. |
| [dragonboat](https://github.com/lni/dragonboat) | 3715 | 143 | 2018/12/23 | 3 days ago | A feature complete and high performance multi-group Raft library in Go. |
| [glow](https://github.com/chrislusf/glow) | 2965 | 147 | 2015/06/14 | 2 years ago | Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go. |
| [emitter](https://github.com/emitter-io/emitter) | 2938 | 101 | 2016/10/29 | 1 week ago | High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love. |
| [gleam](https://github.com/chrislusf/gleam) | 2853 | 151 | 2016/08/26 | 1 month ago | Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed. |
| [liftbridge](https://github.com/liftbridge-io/liftbridge) | 2105 | 71 | 2017/10/13 | 1 week ago | Lightweight, fault-tolerant message streams for NATS. |
| [hprose-golang](https://github.com/hprose/hprose-golang) | 1170 | 92 | 2014/02/14 | 3 weeks ago | Very newbility RPC Library, support 25+ languages now. |
| [ringpop-go](https://github.com/uber/ringpop-go) | 689 | 2432 | 2015/06/05 | 4 months ago | Scalable, fault-tolerant application-layer sharding for Go applications. |
| [gorpc](https://github.com/valyala/gorpc) | 637 | 25 | 2014/11/20 | 1 year ago | Simple, fast and scalable RPC library for high load. |
| [rain](https://github.com/cenkalti/rain) | 614 | 16 | 2014/05/21 | 3 months ago | BitTorrent client and library. |
| [go-health](https://github.com/InVisionApp/go-health) | 596 | 115 | 2017/11/29 | 1 year ago | Library for enabling asynchronous dependency health checks in your service. |
| [redislock](https://github.com/bsm/redislock) | 445 | 7 | 2019/06/24 | 3 days ago | Simplified distributed locking implementation using Redis. |
| [go-sundheit](https://github.com/AppsFlyer/go-sundheit) | 414 | 9 | 2019/04/08 | 1 week ago | A library built to provide support for defining async service health checks for golang services. |
| [digota](https://github.com/digota/digota) | 396 | 29 | 2017/08/14 | 4 months ago | grpc ecommerce microservice. |
| [consistent](https://github.com/buraksezer/consistent) | 386 | 14 | 2018/03/25 | 1 month ago | Consistent hashing with bounded loads. |
| [sleuth](https://github.com/ursiform/sleuth) | 337 | 10 | 2016/04/23 | 3 years ago | Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)). |
| [go-jump](https://github.com/dgryski/go-jump) | 329 | 15 | 2014/06/15 | 3 years ago | Port of Google's "Jump" Consistent Hash function. |
| [dht](https://github.com/anacrolix/dht) | 191 | 14 | 2016/12/14 | 1 week ago | BitTorrent Kademlia DHT implementation. |
| [arpc](https://github.com/lesismal/arpc) | 187 | 14 | 2020/05/19 | 3 days ago | More effective network communication, support two-way-calling, notify, broadcast. |
| [jsonrpc](https://github.com/ybbus/jsonrpc) | 179 | 9 | 2016/11/10 | 2 weeks ago | JSON-RPC 2.0 HTTP client implementation. |
| [jsonrpc](https://github.com/osamingo/jsonrpc) | 150 | 5 | 2016/10/28 | 3 months ago | The jsonrpc package helps implement of JSON-RPC 2.0. |
| [celeriac.v1](https://github.com/svcavallar/celeriac.v1) | 67 | 4 | 2015/10/10 | 8 months ago | Library for adding support for interacting and monitoring Celery workers, tasks and events in Go. |
| [doublejump](https://github.com/edwingeng/doublejump) | 60 | 4 | 2018/06/26 | 1 year ago | A revamped Google's jump consistent hash. |
| [semaphore](https://github.com/jexia/semaphore) | 55 | 15 | 2020/02/05 | 1 month ago | A straightforward (micro) service orchestrator. |
| [outboxer](https://github.com/italolelis/outboxer) | 53 | 0 | 2019/02/01 | 12 hours ago | Outboxer is a go library that implements the outbox pattern. |
| [flowgraph](https://github.com/vectaport/flowgraph) | 39 | 1 | 2018/08/29 | 2 months ago | flow-based programming package. |
| [maestro](https://github.com/jexia/maestro) | 34 | 16 | 2020/02/05 | 1 year ago | A straightforward (micro) service orchestrator. |
| [drmaa](https://github.com/dgruber/drmaa) | 33 | 2 | 2013/03/17 | 9 months ago | Job submission library for cluster schedulers based on the DRMAA standard. |
| [go-pdu](https://github.com/pdupub/go-pdu) | 28 | 4 | 2018/10/08 | 4 months ago | A decentralized identity-based social network. |
| [go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) | 22 | 1 | 2020/06/06 | 1 week ago | MySQL based distributed lock. |
| [dynatomic](https://github.com/tylfin/dynatomic) | 14 | 0 | 2019/02/08 | 8 months ago | A library for using DynamoDB as an atomic counter. |
| [micro](https://github.com/gmsec/micro) | 13 | 2 | 2020/05/03 | 1 week ago | A Go distributed systems development framework. |
| [consistenthash](https://github.com/mbrostami/consistenthash) | 9 | 1 | 2020/04/22 | 1 year ago | Consistent hashing with configurable replicas. |

## Dynamic DNS
        
*Tools for updating dynamic DNS records.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [godns](https://github.com/TimothyYe/godns) | 839 | 33 | 2014/05/11 | 1 week ago | A dynamic DNS client tool, supports DNSPod & HE.net, written in Go. |
| [ddns](https://github.com/skibish/ddns) | 193 | 8 | 2017/03/13 | 1 month ago | Personal DDNS client with Digital Ocean Networking DNS as backend. |

## Email
        
*Libraries and tools that implement email creation and sending.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [MailHog](https://github.com/mailhog/MailHog) | 8725 | 143 | 2014/04/16 | 1 month ago | Email and SMTP testing with web and API interface. |
| [hermes](https://github.com/matcornic/hermes) | 2300 | 30 | 2017/03/25 | 7 months ago | Golang package that generates clean, responsive HTML e-mails. |
| [email](https://github.com/jordan-wright/email) | 1770 | 50 | 2013/12/12 | 2 months ago | A robust and flexible email library for Go. |
| [go-imap](https://github.com/emersion/go-imap) | 1310 | 40 | 2016/04/26 | 1 month ago | IMAP library for clients and servers. |
| [sendgrid-go](https://github.com/sendgrid/sendgrid-go) | 738 | 193 | 2013/09/12 | 2 weeks ago | SendGrid's Go library for sending email. |
| [mailgun-go](https://github.com/mailgun/mailgun-go) | 532 | 67 | 2014/02/28 | 1 week ago | Go library for sending mail with the Mailgun API. |
| [email-verifier](https://github.com/AfterShip/email-verifier) | 253 | 22 | 2020/12/18 | 4 hours ago | A Go library for email verification without sending any emails. |
| [go-message](https://github.com/emersion/go-message) | 209 | 14 | 2016/12/31 | 1 month ago | Streaming library for the Internet Message Format and mail messages. |
| [hectane](https://github.com/hectane/hectane) | 207 | 14 | 2015/08/28 | 7 months ago | Lightweight SMTP client providing an HTTP API. |
| [douceur](https://github.com/aymerick/douceur) | 195 | 3 | 2015/04/09 | 1 month ago | CSS inliner for your HTML emails. |
| [go-simple-mail](https://github.com/xhit/go-simple-mail) | 171 | 4 | 2019/09/15 | 3 days ago | Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send. |
| [mailchain](https://github.com/mailchain/mailchain) | 82 | 7 | 2019/04/11 | 3 weeks ago | Send encrypted emails to blockchain addresses written in Go. |
| [go-premailer](https://github.com/vanng822/go-premailer) | 71 | 2 | 2015/02/16 | 4 months ago | Inline styling for HTML mail in Go. |
| [go-dkim](https://github.com/toorop/go-dkim) | 70 | 3 | 2015/04/29 | 8 months ago | DKIM library, to sign & verify email. |
| [smtp](https://github.com/mailhog/smtp) | 63 | 10 | 2014/12/24 | 3 months ago | SMTP server protocol state machine. |
| [go-email-validator](https://github.com/go-email-validator/go-email-validator) | 11 | 3 | 2020/12/10 | 6 days ago | Modular email validator for syntax, disposable, smtp, etc... checking. |

## Embeddable Scripting Languages
        
*Embedding other languages inside your go code.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [otto](https://github.com/robertkrimen/otto) | 5508 | 183 | 2012/10/06 | 10 months ago | JavaScript interpreter written in Go. |
| [gopher-lua](https://github.com/yuin/gopher-lua) | 4164 | 151 | 2015/02/15 | 1 month ago | Lua 5.1 VM and compiler written in Go. |
| [tengo](https://github.com/d5/tengo) | 2341 | 57 | 2019/01/09 | 1 week ago | Bytecode compiled script language for Go. |
| [goja](https://github.com/dop251/goja) | 2267 | 66 | 2016/11/04 | 3 hours ago | ECMAScript 5.1(+) implementation in Go. |
| [go-lua](https://github.com/Shopify/go-lua) | 2113 | 288 | 2013/12/20 | 2 months ago | Port of the Lua 5.2 VM to pure Go. |
| [expr](https://github.com/antonmedv/expr) | 1848 | 43 | 2018/07/14 | 3 weeks ago | Expression evaluation engine for Go: fast, non-Turing complete, dynamic typing, static typing. |
| [go-python](https://github.com/sbinet/go-python) | 1282 | 43 | 2012/07/09 | 2 months ago | naive go bindings to the CPython C-API. |
| [anko](https://github.com/mattn/anko) | 1145 | 47 | 2014/03/28 | 1 month ago | Scriptable interpreter written in Go. |
| [cel-go](https://github.com/google/cel-go) | 831 | 29 | 2018/03/09 | 3 weeks ago | Fast, portable, non-Turing complete expression evaluation with gradual typing. |
| [go-php](https://github.com/deuill/go-php) | 802 | 42 | 2015/09/17 | 2 years ago | PHP bindings for Go. |
| [go-duktape](https://github.com/olebedev/go-duktape) | 767 | 27 | 2015/01/08 | 3 months ago | Duktape JavaScript engine bindings for Go. |
| [golua](https://github.com/aarzilli/golua) | 549 | 33 | 2010/12/06 | 2 months ago | Go bindings for Lua C API. |
| [gisp](https://github.com/jcla1/gisp) | 461 | 21 | 2014/01/11 | 3 years ago | Simple LISP in Go. |
| [gval](https://github.com/PaesslerAG/gval) | 350 | 16 | 2017/09/27 | 1 month ago | A highly customizable expression language written in Go. |
| [gentee](https://github.com/gentee/gentee) | 77 | 3 | 2018/01/14 | 6 months ago | Embeddable scripting programming language. |
| [binder](https://github.com/alexeyco/binder) | 51 | 2 | 2017/04/02 | 2 years ago | Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua). |
| [purl](https://github.com/ian-kent/purl) | 31 | 3 | 2014/11/29 | 6 years ago | Perl 5.18.2 embedded in Go. |
| [ngaro](https://github.com/db47h/ngaro) | 20 | 1 | 2016/08/09 | 3 years ago | Embeddable Ngaro VM implementation enabling scripting in Retro. |
| [ecal](https://github.com/krotik/ecal) | 11 | 1 | 2020/11/30 | 1 month ago | A simple embeddable scripting language which supports concurrent event processing. |

## Error Handling
        
*Libraries for handling errors.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [errors](https://github.com/pkg/errors) | 7068 | 112 | 2015/12/27 | 1 month ago | Package that provides simple error handling primitives. |
| [go-multierror](https://github.com/hashicorp/go-multierror) | 1297 | 225 | 2014/12/15 | 1 month ago | Go (golang) package for representing a list of errors as a single error. |
| [eris](https://github.com/rotisserie/eris) | 818 | 11 | 2019/09/07 | 2 weeks ago | A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors. |
| [errorx](https://github.com/joomcode/errorx) | 749 | 76 | 2018/08/17 | 3 months ago | A feature rich error package with stack traces, composition of errors and more. |
| [tracerr](https://github.com/ztrue/tracerr) | 663 | 11 | 2019/02/06 | 2 years ago | Golang errors with stack trace and source fragments. |
| [errlog](https://github.com/snwfdhmp/errlog) | 396 | 6 | 2019/02/16 | 7 months ago | Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place. |
| [emperror](https://github.com/emperror/emperror) | 215 | 5 | 2017/06/13 | 9 months ago | Error handling tools and best practices for Go libraries and applications. |
| [errors](https://github.com/emperror/errors) | 96 | 4 | 2019/07/09 | 3 months ago | Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives. |
| [errors](https://github.com/bnkamalesh/errors) | 23 | 1 | 2020/07/17 | 1 month ago | Drop-in replacement for builting Go errors. This is a minimal error handling package with custom error types, user friendly messages, Unwrap & Is. With very easy to use and straightforward helper functions. |
| [werr](https://github.com/txgruppi/werr) | 13 | 0 | 2015/08/04 | 5 years ago | Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called. |
| [falcon](https://github.com/SonicRoshan/falcon) | 6 | 2 | 2019/09/09 | 1 year ago | A Simple Yet Highly Powerful Package For Error Handling. |
| [errors](https://github.com/neuronlabs/errors) | 3 | 2 | 2019/07/26 | 1 year ago | Simple golang error handling with classification primitives. |
| [errors](https://github.com/PumpkinSeed/errors) | 2 | 1 | 2020/01/08 | 1 year ago | The most simple error wrapper with awesome performance and minimal memory overhead. |

## Files
        
*Libraries for handling files and file systems.*

## Financial
        
*Packages for accounting and finance.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [decimal](https://github.com/shopspring/decimal) | 3133 | 67 | 2015/02/25 | 1 week ago | Arbitrary-precision fixed-point decimal numbers. |
| [go-money](https://github.com/Rhymond/go-money) | 959 | 16 | 2017/03/20 | 1 month ago | Implementation of Fowler's Money pattern. |
| [accounting](https://github.com/leekchan/accounting) | 658 | 14 | 2015/08/10 | 5 months ago | money and currency formatting for golang. |
| [go-finance](https://github.com/FlashBoys/go-finance) | 534 | 27 | 2016/02/28 | 3 years ago | Comprehensive financial markets data in Go. |
| [techan](https://github.com/sdcoffey/techan) | 481 | 42 | 2017/03/08 | 3 months ago | Technical analysis library with advanced market analysis and trading strategies. |
| [currency](https://github.com/bojanz/currency) | 261 | 5 | 2020/04/16 | 1 month ago | Handles currency amounts, provides currency information and formatting. |
| [orderbook](https://github.com/i25959341/orderbook) | 211 | 18 | 2018/04/24 | 1 month ago | Matching Engine for Limit Order Book in Golang. |
| [go-finance](https://github.com/alpeb/go-finance) | 99 | 7 | 2017/06/01 | 2 months ago | Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations. |
| [transaction](https://github.com/claygod/transaction) | 93 | 9 | 2017/10/11 | 6 days ago | Embedded transactional database of accounts, running in multithreaded mode. |
| [ofxgo](https://github.com/aclindsa/ofxgo) | 91 | 11 | 2015/11/08 | 1 month ago | Query OFX servers and/or parse the responses (with example command-line client). |
| [vat](https://github.com/dannyvankooten/vat) | 83 | 3 | 2016/06/18 | 5 months ago | VAT number validation & EU VAT rates. |
| [sleet](https://github.com/BoltApp/sleet) | 59 | 33 | 2019/11/13 | 1 week ago | One unified interface for multiple Payment Service Providers (PsP) to process online payment. |
| [go-finnhub](https://github.com/m1/go-finnhub) | 58 | 6 | 2020/01/13 | 1 year ago | Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges. |
| [currency](https://github.com/bnkamalesh/currency) | 39 | 6 | 2017/05/09 | 1 year ago | High performant & accurate currency computation package. |
| [fastme](https://github.com/newity/fastme) | 25 | 3 | 2020/10/29 | 1 month ago | Fast extensible matching engine Go implementation. |
| [go-finance](https://github.com/pieterclaerhout/go-finance) | 5 | 1 | 2019/09/30 | 1 year ago | Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers. |

## Forms
        
*Libraries for working with forms.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [nosurf](https://github.com/justinas/nosurf) | 1176 | 34 | 2013/08/22 | 8 months ago | CSRF protection middleware for Go. |
| [binding](https://github.com/mholt/binding) | 781 | 32 | 2014/05/20 | 3 years ago | Binds form and JSON data from net/http Request to struct. |
| [csrf](https://github.com/gorilla/csrf) | 674 | 23 | 2015/08/03 | 1 month ago | CSRF protection for Go web applications & services. |
| [form](https://github.com/go-playground/form) | 478 | 13 | 2016/05/26 | 4 days ago | Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support. |
| [conform](https://github.com/leebenson/conform) | 223 | 5 | 2016/01/05 | 4 months ago | Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags. |
| [formam](https://github.com/monoculum/formam) | 162 | 5 | 2014/10/25 | 1 month ago | decode form's values into a struct. |
| [forms](https://github.com/albrow/forms) | 122 | 7 | 2014/08/07 | 4 years ago | Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files. |
| [qs](https://github.com/sonh/qs) | 57 | 3 | 2020/10/02 | 1 month ago | Go module for encoding structs into URL query parameters. |
| [bind](https://github.com/robfig/bind) | 25 | 3 | 2014/08/06 | 7 years ago | Bind form data to any Go values. |
| [queryparam](https://github.com/TomWright/queryparam) | 9 | 2 | 2018/06/14 | 9 months ago | Decode `url.Values` into usable struct values of standard or custom types. |

## Functional
        
*Packages to support functional programming in Go.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-underscore](https://github.com/tobyhede/go-underscore) | 1200 | 30 | 2014/07/02 | 2 years ago | Useful collection of helpfully functional Go collection utilities. |
| [fpGo](https://github.com/TeaEntityLab/fpGo) | 179 | 6 | 2018/05/24 | 1 hour ago | Monad, Functional Programming features for Golang. |
| [fuego](https://github.com/seborama/fuego) | 90 | 3 | 2018/11/05 | 8 months ago | Functional Experiment in Go. |

## Game Development
        
*Awesome game development libraries.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [ebiten](https://github.com/hajimehoshi/ebiten) | 4781 | 119 | 2013/06/16 | 2 days ago | dead simple 2D game library in Go. |
| [leaf](https://github.com/name5566/leaf) | 4058 | 319 | 2014/08/04 | 1 day ago | Lightweight game server framework. |
| [pixel](https://github.com/faiface/pixel) | 3541 | 100 | 2016/11/19 | 3 days ago | Hand-crafted 2D game library in Go. |
| [goworld](https://github.com/xiaonanln/goworld) | 1884 | 132 | 2017/06/03 | 3 weeks ago | Scalable game server engine, featuring space-entity framework and hot-swapping. |
| [nano](https://github.com/lonng/nano) | 1734 | 67 | 2017/08/02 | 1 week ago | Lightweight, facility, high performance golang based game server framework. |
| [go-sdl2](https://github.com/veandco/go-sdl2) | 1568 | 45 | 2013/06/05 | 1 month ago | Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/). |
| [engine](https://github.com/g3n/engine) | 1486 | 77 | 2017/03/07 | 1 month ago | Go 3D Game Engine. |
| [engo](https://github.com/EngoEngine/engo) | 1390 | 48 | 2014/11/12 | 3 weeks ago | Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm. |
| [termloop](https://github.com/JoelOtter/termloop) | 1216 | 31 | 2015/05/23 | 7 months ago | Terminal-based game engine for Go, built on top of Termbox. |
| [gonet](https://github.com/xtaci/gonet) | 1144 | 135 | 2013/04/11 | 4 years ago | Game server skeleton implemented with golang. |
| [pitaya](https://github.com/topfreegames/pitaya) | 1081 | 67 | 2018/03/19 | 1 week ago | Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK. |
| [oak](https://github.com/oakmound/oak) | 899 | 44 | 2017/07/15 | 6 days ago | Pure Go game engine. |
| [raylib-go](https://github.com/gen2brain/raylib-go) | 617 | 21 | 2017/01/27 | 2 weeks ago | Go bindings for [raylib](http://www.raylib.com/), a simple and easy-to-use library to learn videogames programming. |
| [engine](https://github.com/azul3d/engine) | 490 | 24 | 2016/02/29 | 1 year ago | 3D game engine written in Go. |
| [go-astar](https://github.com/beefsack/go-astar) | 434 | 10 | 2014/05/28 | 10 months ago | Go implementation of the A\* path finding algorithm. |
| [GarageEngine](https://github.com/vova616/GarageEngine) | 320 | 31 | 2012/08/07 | 1 year ago | 2d game engine written in Go working on OpenGL. |
| [go3d](https://github.com/ungerik/go3d) | 200 | 10 | 2011/06/27 | 1 month ago | Performance oriented 2D/3D math package for Go. |
| [glop](https://github.com/runningwild/glop) | 77 | 3 | 2011/04/20 | 5 years ago | Glop (Game Library Of Power) is a fairly simple cross-platform game library. |
| [prototype](https://github.com/gonutz/prototype) | 57 | 2 | 2015/03/04 | 3 days ago | Cross-platform (Windows/Linux/Mac) library for creating desktop games using a minimal API. |
| [tile](https://github.com/kelindar/tile) | 25 | 1 | 2020/08/19 | 4 days ago | Data-oriented and cache-friendly 2D Grid library (TileMap), includes pathfinding, observers and import/export. |
| [go-collada](https://github.com/GlenKelley/go-collada) | 15 | 3 | 2013/09/19 | 7 years ago | Go package for working with the Collada file format. |

## Generation and Generics
        
*Tools to enhance the language with features like generics via code generation.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-linq](https://github.com/ahmetb/go-linq) | 2566 | 73 | 2013/12/19 | 2 months ago | .NET LINQ-like query methods for Go. |
| [jennifer](https://github.com/dave/jennifer) | 2071 | 31 | 2016/12/04 | 5 months ago | Generate arbitrary Go code without templates. |
| [gen](https://github.com/clipperhouse/gen) | 1299 | 33 | 2013/10/13 | 1 year ago | Code generation tool for ‘generics’-like functionality. |
| [goderive](https://github.com/awalterschulze/goderive) | 898 | 21 | 2017/02/10 | 4 days ago | Derives functions from input types. |
| [gowrap](https://github.com/hexdigest/gowrap) | 521 | 11 | 2018/09/15 | 4 days ago | Generate decorators for Go interfaces using simple templates. |
| [interfaces](https://github.com/rjeczalik/interfaces) | 304 | 7 | 2015/12/06 | 2 months ago | Command line tool for generating interface definitions. |
| [go-enum](https://github.com/abice/go-enum) | 214 | 3 | 2017/08/10 | 14 hours ago | Code generation for enums from code comments. |
| [pkgreflect](https://github.com/ungerik/pkgreflect) | 96 | 6 | 2012/09/03 | 3 years ago | Go preprocessor for package scoped reflection. |
| [efaceconv](https://github.com/t0pep0/efaceconv) | 49 | 4 | 2016/11/18 | 3 years ago | Code generation tool for high performance conversion from interface{} to immutable type without allocations. |
| [gotype](https://github.com/wzshiming/gotype) | 37 | 4 | 2017/12/05 | 4 weeks ago | Golang source code parsing, usage like reflect package. |
| [GENERIS](https://github.com/senselogic/GENERIS) | 27 | 1 | 2019/03/10 | 3 months ago | Code generation tool providing generics, free-form macros, conditional compilation and HTML templating. |
| [go-xray](https://github.com/pieterclaerhout/go-xray) | 18 | 3 | 2019/10/01 | 1 year ago | Helpers for making the use of reflection easier. |
| [typeregistry](https://github.com/xiaoxin01/typeregistry) | 11 | 1 | 2020/01/14 | 1 year ago | A library to create type dynamically. |

## Geographic
        
*Geographic tools and servers*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [tile38](https://github.com/tidwall/tile38) | 7508 | 206 | 2016/03/04 | 19 hours ago | Geolocation DB with spatial index and realtime geofencing. |
| [geo](https://github.com/golang/geo) | 1232 | 78 | 2014/12/03 | 4 weeks ago | S2 geometry library in Go. |
| [mbtileserver](https://github.com/consbio/mbtileserver) | 251 | 17 | 2014/11/01 | 3 weeks ago | A simple Go-based server for map tiles stored in mbtiles format. |
| [osm](https://github.com/paulmach/osm) | 167 | 12 | 2016/02/02 | 2 months ago | Library for reading, writing and working with OpenStreetMap data and APIs. |
| [geocache](https://github.com/melihmucuk/geocache) | 131 | 6 | 2016/06/21 | 5 years ago | In-memory cache that is suitable for geolocation based applications. |
| [wgs84](https://github.com/wroge/wgs84) | 61 | 1 | 2019/06/08 | 7 months ago | Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM). |
| [geoserver](https://github.com/hishamkaram/geoserver) | 55 | 1 | 2018/03/26 | 1 month ago | geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API. |
| [gismanager](https://github.com/hishamkaram/gismanager) | 38 | 0 | 2018/09/29 | 2 years ago | Publish Your GIS Data(Vector Data) to PostGIS and Geoserver. |
| [pbf](https://github.com/maguro/pbf) | 25 | 3 | 2017/09/18 | 2 months ago | OpenStreetMap PBF golang encoder/decoder. |
| [s2-geojson](https://github.com/pantrif/s2-geojson) | 13 | 1 | 2020/03/27 | 1 year ago | Convert geojson to s2 cells & demonstrating some S2 geometry features on map. |

## Go Compilers
        
*Tools for compiling Go to other languages.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gopherjs](https://github.com/gopherjs/gopherjs) | 10304 | 256 | 2013/08/27 | 5 days ago | Compiler from Go to JavaScript. |
| [llgo](https://github.com/go-llvm/llgo) | 1095 | 63 | 2011/11/05 | 6 years ago | LLVM-based compiler for Go. |
| [tardisgo](https://github.com/tardisgo/tardisgo) | 409 | 30 | 2014/01/08 | 4 years ago | Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler. |
| [c4go](https://github.com/Konstantin8105/c4go) | 271 | 17 | 2018/03/28 | 2 months ago | Transpile C code to Go code. |
| [f4go](https://github.com/Konstantin8105/f4go) | 24 | 4 | 2018/07/08 | 6 months ago | Transpile FORTRAN 77 code to Go code. |

## Goroutines
        
*Tools for managing and working with Goroutines.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [ants](https://github.com/panjf2000/ants) | 5979 | 148 | 2018/05/19 | 2 hours ago | A high-performance and low-cost goroutine pool in Go. |
| [goworker](https://github.com/benmanns/goworker) | 2571 | 74 | 2013/07/22 | 1 month ago | goworker is a Go-based background worker. |
| [tunny](https://github.com/Jeffail/tunny) | 2462 | 74 | 2014/04/02 | 15 hours ago | Goroutine pool for golang. |
| [grpool](https://github.com/ivpusic/grpool) | 641 | 29 | 2015/07/22 | 2 years ago | Lightweight Goroutine pool. |
| [pool](https://github.com/go-playground/pool) | 625 | 14 | 2015/10/28 | 2 weeks ago | Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation. |
| [workerpool](https://github.com/gammazero/workerpool) | 575 | 15 | 2016/05/17 | 1 month ago | Goroutine pool that limits the concurrency of task execution, not the number of tasks queued. |
| [gowp](https://github.com/xxjwxc/gowp) | 302 | 15 | 2019/09/14 | 1 month ago | gowp is concurrency limiting goroutine pool. |
| [pond](https://github.com/alitto/pond) | 234 | 7 | 2020/03/21 | 2 days ago | Minimalistic and High-performance goroutine worker pool written in Go. |
| [go-floc](https://github.com/workanator/go-floc) | 203 | 7 | 2017/07/03 | 2 months ago | Orchestrate goroutines with ease. |
| [go-flow](https://github.com/kamildrazkiewicz/go-flow) | 168 | 10 | 2016/09/25 | 2 years ago | Control goroutines execution order. |
| [semaphore](https://github.com/marusama/semaphore) | 115 | 2 | 2017/11/22 | 3 months ago | Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations). |
| [artifex](https://github.com/mborders/artifex) | 111 | 7 | 2018/10/31 | 10 months ago | Simple in-memory job queue for Golang using worker-based dispatching. |
| [go-workers](https://github.com/catmullet/go-workers) | 111 | 4 | 2020/10/06 | 2 weeks ago | Easily and safely run workers for large data processing pipelines. |
| [GoSlaves](https://github.com/dgrr/GoSlaves) | 95 | 4 | 2017/09/17 | 1 year ago | Simple and Asynchronous Goroutine pool library. |
| [async](https://github.com/StudioSol/async) | 86 | 13 | 2017/06/30 | 7 months ago | A safe way to execute functions asynchronously, recovering them in case of panic. |
| [semaphore](https://github.com/kamilsk/semaphore) | 85 | 1 | 2016/10/08 | 1 year ago | Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context. |
| [gpool](https://github.com/sherifabdlnaby/gpool) | 80 | 1 | 2018/12/03 | 1 year ago | manages a resizeable pool of context-aware goroutines to bound concurrency. |
| [errgroup](https://github.com/neilotoole/errgroup) | 80 | 2 | 2020/06/26 | 2 weeks ago | Drop-in alternative to `sync/errgroup`, limited to a pool of N worker goroutines. |
| [worker-pool](https://github.com/vardius/worker-pool) | 76 | 5 | 2017/10/04 | 5 months ago | goworker is a Go simple async worker pool. |
| [cyclicbarrier](https://github.com/marusama/cyclicbarrier) | 69 | 2 | 2018/01/11 | 1 year ago | CyclicBarrier for golang. |
| [threadpool](https://github.com/shettyh/threadpool) | 60 | 3 | 2017/09/06 | 1 year ago | Golang threadpool implementation. |
| [gollback](https://github.com/vardius/gollback) | 58 | 1 | 2019/05/11 | 1 year ago | asynchronous simple function utilities, for managing execution of closures and callbacks. |
| [Hunch](https://github.com/AaronJan/Hunch) | 54 | 1 | 2019/06/05 | 9 months ago | Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive. |
| [routine](https://github.com/x-mod/routine) | 41 | 3 | 2019/03/04 | 9 months ago | go routine control with context, support: Main, Go, Pool and some useful Executors. |
| [kyoo](https://github.com/dirkaholic/kyoo) | 33 | 2 | 2020/01/06 | 1 year ago | Provides an unlimited job queue and concurrent worker pools. |
| [nursery](https://github.com/arunsworld/nursery) | 31 | 4 | 2019/11/23 | 4 days ago | Structured concurrency in Go. |
| [parallel-fn](https://github.com/rafaeljesus/parallel-fn) | 30 | 3 | 2017/06/18 | 3 years ago | Run functions in parallel. |
| [async](https://github.com/reugn/async) | 23 | 1 | 2019/12/28 | 10 months ago | An alternative sync library for Go (Future, Promise, Locks). |
| [goccm](https://github.com/zenthangplus/goccm) | 22 | 1 | 2019/08/16 | 2 weeks ago | Go Concurrency Manager package limits the number of goroutines that allowed to run concurrently. |
| [go-trylock](https://github.com/subchen/go-trylock) | 20 | 1 | 2018/04/26 | 2 months ago | TryLock support on read-write lock for Golang. |
| [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) | 20 | 1 | 2018/08/08 | 1 year ago | Like `sync.WaitGroup` with error handling and concurrency control. |
| [stl](https://github.com/ssgreg/stl) | 18 | 2 | 2018/06/19 | 11 months ago | Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism. |
| [gohive](https://github.com/loveleshsharma/gohive) | 12 | 3 | 2019/05/31 | 1 year ago | A highly performant and easy to use Goroutine pool for Go. |
| [channelify](https://github.com/ddelizia/channelify) | 12 | 1 | 2020/10/05 | 4 months ago | Transform your function to return channels for easy and powerful parallel processing. |
| [conexec](https://github.com/ITcathyh/conexec) | 10 | 2 | 2019/12/24 | 1 year ago | A concurrent toolkit to help execute funcs concurrently in an efficient and safe way. It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency. |
| [queue](https://github.com/AnikHasibul/queue) | 9 | 0 | 2018/12/21 | 2 years ago | Gives you a `sync.WaitGroup` like queue group accessibility. Helps you to throttle and limit goroutines, wait for the end of the all goroutines and much more. |
| [hands](https://github.com/duanckham/hands) | 7 | 1 | 2020/04/04 | 1 year ago | A process controller used to control the execution and return strategies of multiple goroutines. |
| [go-tools](https://github.com/nikhilsaraf/go-tools) | 5 | 2 | 2018/11/14 | 2 years ago | Manage a pool of goroutines using this lightweight library with a simple API. |
| [concurrency-limiter](https://github.com/vivek-ng/concurrency-limiter) | 4 | 1 | 2020/11/22 | 7 months ago | Concurrency limiter with support for timeouts , dynamic priority and context cancellation of goroutines. |
| [breaker](https://github.com/kamilsk/breaker) | 0 | 0 | 2019/02/15 | 1 day ago | Flexible mechanism to make execution flow interruptible. |

## GUI
        
*Interaction*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [fyne](https://github.com/fyne-io/fyne) | 13484 | 223 | 2018/02/04 | 19 hours ago | Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android. |
| [qt](https://github.com/therecipe/qt) | 8629 | 313 | 2014/11/19 | 6 months ago | Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi). |
| [webview](https://github.com/webview/webview) | 8554 | 223 | 2017/08/19 | 1 month ago | Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux). |
| [ui](https://github.com/andlabs/ui) | 7906 | 371 | 2014/02/17 | 5 months ago | Platform-native GUI library for Go. Cross platform. |
| [robotgo](https://github.com/go-vgo/robotgo) | 6733 | 232 | 2016/09/26 | 1 month ago | Go Native cross-platform GUI system automation. Control the mouse, keyboard and other. |
| [webview](https://github.com/zserge/webview) | 6166 | 211 | 2017/08/19 | 1 year ago | Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux). |
| [walk](https://github.com/lxn/walk) | 5526 | 262 | 2010/09/16 | 4 days ago | Windows application library kit for Go. |
| [go-app](https://github.com/maxence-charriere/go-app) | 4936 | 145 | 2016/10/12 | 1 week ago | Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress. |
| [go-astilectron](https://github.com/asticode/go-astilectron) | 3902 | 138 | 2017/04/22 | 3 weeks ago | Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron). |
| [app](https://github.com/maxence-charriere/app) | 3314 | 111 | 2016/10/12 | 1 year ago | Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress. |
| [go-sciter](https://github.com/sciter-sdk/go-sciter) | 2119 | 124 | 2015/10/15 | 2 months ago | Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform. |
| [systray](https://github.com/getlantern/systray) | 1870 | 62 | 2014/11/12 | 2 months ago | Cross platform Go library to place an icon and menu in the notification area. |
| [gotk3](https://github.com/gotk3/gotk3) | 1518 | 62 | 2015/08/13 | 2 days ago | Go bindings for GTK3. |
| [gosx-notifier](https://github.com/deckarep/gosx-notifier) | 540 | 15 | 2013/11/25 | 1 year ago | OSX Desktop Notifications library for Go. |
| [gowd](https://github.com/dtylman/gowd) | 322 | 27 | 2017/03/29 | 2 years ago | Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform. |
| [trayhost](https://github.com/shurcooL/trayhost) | 212 | 7 | 2014/04/25 | 1 year ago | Cross-platform Go library to place an icon in the host operating system's taskbar. |
| [go-appindicator](https://github.com/dawidd6/go-appindicator) | 17 | 5 | 2019/05/04 | 6 months ago | Go bindings for libappindicator3 C library. |
| [activity-tracker](https://github.com/prashantgupta24/activity-tracker) | 12 | 2 | 2019/03/12 | 2 years ago | OSX library to notify about any (pluggable) activity on your machine. |
| [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) | 9 | 2 | 2019/03/30 | 2 years ago | OSX Sleep/Wake notifications in golang. |

## Hardware
        
*Libraries, tools, and tutorials for interacting with hardware.*

## Images
        
*Libraries for manipulating images.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gocv](https://github.com/hybridgroup/gocv) | 4141 | 139 | 2017/09/18 | 7 hours ago | Go package for computer vision using OpenCV 3.3+. |
| [imaging](https://github.com/disintegration/imaging) | 3824 | 76 | 2012/12/06 | 6 months ago | Simple Go image processing package. |
| [imaginary](https://github.com/h2non/imaginary) | 3732 | 77 | 2015/03/04 | 3 months ago | Fast and simple HTTP microservice for image resizing. |
| [bild](https://github.com/anthonynsimon/bild) | 3239 | 67 | 2016/08/01 | 4 months ago | Collection of image processing algorithms in pure Go. |
| [gg](https://github.com/fogleman/gg) | 2927 | 91 | 2016/02/18 | 3 months ago | 2D rendering in pure Go. |
| [ln](https://github.com/fogleman/ln) | 2918 | 93 | 2016/01/10 | 2 years ago | 3D line art rendering in Go. |
| [resize](https://github.com/nfnt/resize) | 2670 | 81 | 2012/08/02 | 7 months ago | Image resizing for Go with common interpolation methods. |
| [pt](https://github.com/fogleman/pt) | 1954 | 59 | 2015/01/23 | 2 years ago | Path tracing engine written in Go. |
| [svgo](https://github.com/ajstarks/svgo) | 1685 | 50 | 2010/03/05 | 1 week ago | Go Language Library for SVG generation. |
| [smartcrop](https://github.com/muesli/smartcrop) | 1527 | 34 | 2014/04/07 | 1 month ago | Finds good crops for arbitrary images and crop sizes. |
| [picfit](https://github.com/thoas/picfit) | 1498 | 54 | 2014/12/06 | 2 months ago | An image resizing server written in Go. |
| [bimg](https://github.com/h2non/bimg) | 1496 | 36 | 2015/03/17 | 3 days ago | Small package for fast and efficient image processing using libvips. |
| [gift](https://github.com/disintegration/gift) | 1452 | 50 | 2014/07/12 | 7 months ago | Package of image processing filters. |
| [imagick](https://github.com/gographics/imagick) | 1322 | 55 | 2013/04/30 | 2 months ago | Go binding to ImageMagick's MagickWand C API. |
| [go-opencv](https://github.com/go-opencv/go-opencv) | 1238 | 64 | 2013/12/09 | 2 years ago | Go bindings for OpenCV. |
| [geopattern](https://github.com/pravj/geopattern) | 1128 | 21 | 2014/10/22 | 2 years ago | Create beautiful generative image patterns from a string. |
| [stegify](https://github.com/DimitarPetrov/stegify) | 939 | 21 | 2018/11/29 | 1 year ago | Go tool for LSB steganography, capable of hiding any file within an image. |
| [canvas](https://github.com/tdewolff/canvas) | 751 | 19 | 2017/05/20 | 4 days ago | Vector graphics to PDF, SVG or rasterized image. |
| [image2ascii](https://github.com/qeesung/image2ascii) | 555 | 9 | 2018/10/20 | 2 years ago | Convert image to ASCII. |
| [draft](https://github.com/lucasepe/draft) | 496 | 13 | 2020/06/05 | 6 months ago | Generate High Level Microservice Architecture diagrams for GraphViz using simple YAML syntax. |
| [govips](https://github.com/davidbyttow/govips) | 490 | 10 | 2016/12/25 | 3 weeks ago | A lightning fast image processing and resizing library for Go. |
| [govatar](https://github.com/o1egl/govatar) | 443 | 9 | 2016/01/18 | 4 months ago | Library and CMD tool for generating funny avatars. |
| [mort](https://github.com/aldor007/mort) | 436 | 19 | 2017/11/19 | 4 months ago | Storage and image processing server written in Go. |
| [goimagehash](https://github.com/corona10/goimagehash) | 416 | 11 | 2017/07/28 | 4 months ago | Go Perceptual image hashing package. |
| [go-nude](https://github.com/koyachi/go-nude) | 333 | 16 | 2014/05/02 | 2 years ago | Nudity detection with Go. |
| [rez](https://github.com/bamiaux/rez) | 200 | 9 | 2014/01/16 | 4 years ago | Image resizing in pure Go and SIMD. |
| [darkroom](https://github.com/gojek/darkroom) | 165 | 9 | 2019/07/01 | 1 week ago | An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency. |
| [mergi](https://github.com/noelyahan/mergi) | 141 | 7 | 2018/09/24 | 1 year ago | Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate). |
| [img](https://github.com/hawx/img) | 137 | 5 | 2012/07/28 | 6 years ago | Selection of image manipulation tools. |
| [gltf](https://github.com/qmuntal/gltf) | 113 | 4 | 2019/01/15 | 3 months ago | Efficient and robust glTF 2.0 reader, writer and validator. |
| [go-cairo](https://github.com/ungerik/go-cairo) | 107 | 6 | 2012/08/22 | 3 months ago | Go binding for the cairo graphics library. |
| [steganography](https://github.com/auyer/steganography) | 101 | 4 | 2018/05/21 | 2 months ago | Pure Go Library for LSB steganography. |
| [cameron](https://github.com/aofei/cameron) | 69 | 4 | 2018/05/05 | 4 months ago | An avatar generator for Go. |
| [go-gd](https://github.com/bolknote/go-gd) | 53 | 4 | 2011/05/12 | 3 years ago | Go binding for GD library. |
| [gridder](https://github.com/shomali11/gridder) | 43 | 4 | 2020/04/10 | 1 year ago | A Grid based 2D Graphics library. |
| [goimghdr](https://github.com/corona10/goimghdr) | 36 | 1 | 2018/02/25 | 2 years ago | The imghdr module determines the type of image contained in a file for Go. |
| [tga](https://github.com/ftrvxmtrx/tga) | 28 | 3 | 2012/10/08 | 6 years ago | Package tga is a TARGA image format decoder/encoder. |
| [go-webcolors](https://github.com/jyotiska/go-webcolors) | 25 | 2 | 2014/04/24 | 5 years ago | Port of webcolors library from Python to Go. |
| [webp-server](https://github.com/mehdipourfar/webp-server) | 16 | 1 | 2020/11/22 | 5 months ago | Simple and minimal image server capable of storing, resizing, converting and caching images. |
| [mpo](https://github.com/donatj/mpo) | 7 | 1 | 2015/04/14 | 1 year ago | Decoder and conversion tool for MPO 3D Photos. |

## IoT
        
*Libraries for programming devices of the IoT.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [flogo](https://github.com/TIBCOSoftware/flogo) | 1784 | 154 | 2016/07/10 | 7 months ago | Project Flogo is an Open Source Framework for IoT Edge Apps & Integration. |
| [mainflux](https://github.com/mainflux/mainflux) | 1462 | 106 | 2015/07/06 | 6 hours ago | Industrial IoT Messaging and Device Management Server. |
| [gatt](https://github.com/paypal/gatt) | 981 | 56 | 2014/04/23 | 1 year ago | Gatt is a Go package for building Bluetooth Low Energy peripherals. |
| [heedy](https://github.com/heedy/heedy) | 277 | 25 | 2015/01/16 | 2 weeks ago | Open-Source Platform for Quantified Self & IoT. |
| [devices](https://github.com/goiot/devices) | 241 | 15 | 2016/05/30 | 5 years ago | Suite of libraries for IoT devices, experimental for x/exp/io. |
| [sensorbee](https://github.com/sensorbee/sensorbee) | 203 | 19 | 2016/02/19 | 1 year ago | Lightweight stream processing engine for IoT. |
| [huego](https://github.com/amimof/huego) | 184 | 4 | 2017/05/16 | 1 week ago | An extensive Philips Hue client library for Go. |
| [eywa](https://github.com/xcodersun/eywa) | 48 | 8 | 2016/02/20 | 4 years ago | Project Eywa is essentially a connection manager that keeps track of connected devices. |

## Job Scheduler
        
*Libraries for scheduling jobs.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gocron](https://github.com/go-co-op/gocron) | 924 | 18 | 2020/03/20 | 1 month ago | Easy and fluent Go job scheduling. This is an actively maintained fork of [jasonlvhit/gocron](https://github.com/jasonlvhit/gocron). |
| [gron](https://github.com/roylee0704/gron) | 864 | 16 | 2016/06/04 | 5 months ago | Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly. |
| [jobrunner](https://github.com/bamzi/jobrunner) | 856 | 27 | 2015/10/21 | 7 months ago | Smart and featureful cron job scheduler with job queuing and live monitoring built in. |
| [jobs](https://github.com/albrow/jobs) | 482 | 18 | 2015/02/09 | 3 years ago | Persistent and flexible background jobs library. |
| [scheduler](https://github.com/carlescere/scheduler) | 368 | 15 | 2015/02/03 | 6 months ago | Cronjobs scheduling made easy. |
| [go-cron](https://github.com/rk/go-cron) | 202 | 9 | 2011/04/15 | 1 year ago | Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons. |
| [go-quartz](https://github.com/reugn/go-quartz) | 145 | 8 | 2019/04/14 | 4 months ago | Simple, zero-dependency scheduling library for Go. |
| [leprechaun](https://github.com/kilgaloon/leprechaun) | 83 | 8 | 2018/04/08 | 6 months ago | Job scheduler that supports webhooks, crons and classic scheduling. |
| [clockwork](https://github.com/whiteShtef/clockwork) | 28 | 1 | 2018/04/23 | 9 months ago | Simple and intuitive job scheduling library in Go. |
| [cronticker](https://github.com/krayzpipes/cronticker) | 1 | 1 | 2020/11/28 | 6 months ago | A ticker implementation to support cron schedules. |

## JSON
        
*Libraries for working with JSON.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gjson](https://github.com/tidwall/gjson) | 8595 | 152 | 2016/08/11 | 2 days ago | Get a JSON value with one line of code. |
| [gojson](https://github.com/ChimeraCoder/gojson) | 2375 | 46 | 2012/12/27 | 1 year ago | Automatically generate Go (golang) struct definitions from example JSON. |
| [fastjson](https://github.com/valyala/fastjson) | 1262 | 28 | 2018/05/28 | 1 month ago | Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection. |
| [kazaam](https://github.com/qntfy/kazaam) | 200 | 22 | 2016/07/19 | 6 days ago | API for arbitrary transformation of JSON documents. |
| [gojq](https://github.com/elgs/gojq) | 171 | 5 | 2015/12/30 | 7 months ago | JSON query in Golang. |
| [jsondiff](https://github.com/wI2L/jsondiff) | 118 | 2 | 2020/11/28 | 6 months ago | JSON diff library for Go based on RFC6902 (JSON Patch). |
| [jettison](https://github.com/wI2L/jettison) | 108 | 6 | 2019/08/30 | 6 months ago | Fast and flexible JSON encoder for Go. |
| [jsongo](https://github.com/ricardolonga/jsongo) | 96 | 1 | 2015/08/07 | 4 years ago | Fluent API to make it easier to create Json objects. |
| [gjo](https://github.com/skanehira/gjo) | 94 | 8 | 2019/02/23 | 2 months ago | Small utility to create JSON objects. |
| [jaydiff](https://github.com/yazgazan/jaydiff) | 85 | 2 | 2017/04/24 | 5 months ago | JSON diff utility written in Go. |
| [json2go](https://github.com/m-zajac/json2go) | 82 | 3 | 2017/06/10 | 2 months ago | Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all. |
| [ajson](https://github.com/spyzhov/ajson) | 61 | 2 | 2019/03/07 | 1 year ago | Abstract JSON for golang with JSONPath support. |
| [jsonf](https://github.com/miolini/jsonf) | 61 | 3 | 2015/05/25 | 7 months ago | Console tool for highlighted formatting and struct query fetching JSON. |
| [mp](https://github.com/sanbornm/mp) | 44 | 2 | 2014/06/15 | 5 years ago | Simple cli email parser. It currently takes stdin and outputs JSON. |
| [go-respond](https://github.com/nicklaw5/go-respond) | 41 | 1 | 2017/03/12 | 2 years ago | Go package for handling common HTTP JSON responses. |
| [go-jsonerror](https://github.com/ddymko/go-jsonerror) | 10 | 1 | 2018/10/18 | 1 year ago | Go-JsonError is ment to allow us to easily create json response errors that follow the JsonApi spec. |
| [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) | 9 | 2 | 2016/07/08 | 4 years ago | Go bindings based on the JSON API errors reference. |
| [jsonhal](https://github.com/RichardKnop/jsonhal) | 9 | 2 | 2016/01/15 | 1 year ago | Simple Go package to make custom structs marshal into HAL compatible JSON responses. |
| [ej](https://github.com/lucassscaravelli/ej) | 7 | 2 | 2020/01/04 | 1 year ago | Write and read JSON from different sources succinctly. |
| [dynjson](https://github.com/cocoonspace/dynjson) | 6 | 2 | 2020/05/06 | 3 months ago | Client-customizable JSON formats for dynamic APIs. |
| [mapslice-json](https://github.com/mickep76/mapslice-json) | 5 | 1 | 2020/02/19 | 1 year ago | Go MapSlice for ordered marshal/ unmarshal of maps in JSON. |
| [epoch](https://github.com/vtopc/epoch) | 5 | 1 | 2019/12/15 | 3 months ago | Contains primitives for marshaling/unmarshaling Unix timestamp/epoch to/from build-in time.Time type in JSON. |
| [jzon](https://github.com/zerosnake0/jzon) | 4 | 1 | 2019/11/12 | 3 months ago | JSON library with standard compatible API/behavior. |
| [jsonic](https://github.com/sinhashubham95/jsonic) | 2 | 1 | 2021/01/09 | 5 months ago | Utilities to handle and query JSON without defining structs in a type safe manner. |

## Logging
        
*Libraries for generating and working with log files.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [logrus](https://github.com/sirupsen/logrus) | 18203 | 309 | 2013/10/16 | 2 weeks ago | Structured logger for Go. |
| [zap](https://github.com/uber-go/zap) | 13053 | 252 | 2016/02/18 | 3 days ago | Fast, structured, leveled logging in Go. |
| [zerolog](https://github.com/rs/zerolog) | 4892 | 55 | 2017/05/12 | 2 weeks ago | Zero-allocation JSON logger. |
| [go-spew](https://github.com/davecgh/go-spew) | 4489 | 62 | 2013/01/09 | 7 months ago | Implements a deep pretty printer for Go data structures to aid in debugging. |
| [glog](https://github.com/golang/glog) | 2749 | 89 | 2013/07/16 | 1 month ago | Leveled execution logs for Go. |
| [lumberjack](https://github.com/natefinch/lumberjack) | 2634 | 55 | 2014/06/14 | 1 week ago | Simple rolling logger, implements io.WriteCloser. |
| [tail](https://github.com/hpcloud/tail) | 2130 | 98 | 2013/02/05 | 2 months ago | Go package striving to emulate the features of the BSD tail program. |
| [seelog](https://github.com/cihub/seelog) | 1546 | 90 | 2011/11/17 | 2 years ago | Logging functionality with flexible dispatching, filtering, and formatting. |
| [log](https://github.com/apex/log) | 1146 | 34 | 2015/12/21 | 5 months ago | Structured logging package for Go. |
| [log15](https://github.com/inconshreveable/log15) | 1012 | 26 | 2014/05/20 | 8 months ago | Simple, powerful logging for Go. |
| [onelog](https://github.com/francoispqt/onelog) | 395 | 10 | 2018/05/06 | 2 years ago | Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenarios. Also, it is one of the logger with the lowest allocation. |
| [log](https://github.com/phuslu/log) | 382 | 16 | 2019/07/07 | 1 week ago | Structured Logging Made Easy. |
| [logxi](https://github.com/mgutz/logxi) | 347 | 10 | 2015/03/01 | 1 year ago | 12-factor app logger that is fast and makes you happy. |
| [logutils](https://github.com/hashicorp/logutils) | 293 | 239 | 2013/10/09 | 1 year ago | Utilities for slightly better logging in Go (Golang) extending the standard logger. |
| [log](https://github.com/go-playground/log) | 275 | 11 | 2016/02/07 | 1 year ago | Simple, configurable and scalable Structured Logging for Go. |
| [go-logger](https://github.com/apsdehal/go-logger) | 265 | 7 | 2014/09/26 | 2 years ago | Simple logger of Go Programs, with level handlers. |
| [httpretty](https://github.com/henvic/httpretty) | 229 | 5 | 2020/01/24 | 6 months ago | Pretty-prints your regular HTTP requests on your terminal for debugging (similar to http.DumpRequest). |
| [sqldb-logger](https://github.com/simukti/sqldb-logger) | 184 | 3 | 2019/11/02 | 1 month ago | A logger for Go SQL database driver without modify existing *sql.DB stdlib usage. |
| [rollingwriter](https://github.com/arthurkiller/rollingwriter) | 178 | 8 | 2017/02/12 | 9 months ago | RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation. |
| [logger](https://github.com/azer/logger) | 148 | 6 | 2014/09/30 | 8 months ago | Minimalistic logging library for Go. |
| [xlog](https://github.com/rs/xlog) | 135 | 8 | 2015/10/22 | 4 months ago | Structured logger for `net/context` aware HTTP handlers with flexible dispatching. |
| [logur](https://github.com/logur/logur) | 128 | 6 | 2018/12/09 | 9 months ago | An opinionated logger interface and collection of logging best practices with adapters and integrations for well-known libraries ([logrus](https://github.com/sirupsen/logrus), [go-kit log](https://github.com/go-kit/kit/tree/master/log), [zap](https://github.com/uber-go/zap), [zerolog](https://github.com/rs/zerolog), etc). |
| [glg](https://github.com/kpango/glg) | 115 | 6 | 2017/06/21 | 6 days ago | glg is simple and fast leveled logging library for Go. |
| [ozzo-log](https://github.com/go-ozzo/ozzo-log) | 114 | 12 | 2015/10/22 | 6 months ago | High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail). |
| [logvoyage](https://github.com/firstrow/logvoyage) | 88 | 5 | 2015/03/29 | 4 years ago | Full-featured logging saas written in golang. |
| [log](https://github.com/alexcesaro/log) | 45 | 6 | 2014/04/19 | 5 years ago | Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs. |
| [go-cronowriter](https://github.com/utahta/go-cronowriter) | 42 | 1 | 2017/02/04 | 3 months ago | Simple writer that rotate log files automatically based on current date and time, like cronolog. |
| [gologger](https://github.com/sadlil/gologger) | 39 | 6 | 2015/09/02 | 3 years ago | Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch. |
| [go-log](https://github.com/ian-kent/go-log) | 37 | 2 | 2014/05/02 | 3 years ago | Log4j implementation in Go. |
| [logex](https://github.com/chzyer/logex) | 37 | 8 | 2014/10/10 | 4 years ago | Golang log lib, supports tracking and level, wrap by standard log lib. |
| [go-log](https://github.com/siddontang/go-log) | 28 | 6 | 2014/05/18 | 2 years ago | Log lib supports level and multi handlers. |
| [distillog](https://github.com/amoghe/distillog) | 26 | 1 | 2015/10/12 | 3 years ago | distilled levelled logging (think of it as stdlib + log levels). |
| [journald](https://github.com/ssgreg/journald) | 26 | 2 | 2017/08/23 | 4 months ago | Go implementation of systemd Journal's native API for logging. |
| [logrusly](https://github.com/sebest/logrusly) | 26 | 4 | 2014/09/11 | 11 months ago | [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/). |
| [log](https://github.com/teris-io/log) | 24 | 2 | 2017/10/28 | 3 years ago | Structured log interface for Go cleanly separates logging facade from its implementation. |
| [mlog](https://github.com/jbrodriguez/mlog) | 24 | 1 | 2014/10/20 | 2 years ago | Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output. |
| [gomol](https://github.com/aphistic/gomol) | 17 | 2 | 2015/08/30 | 2 years ago | Multiple-output, structured logging for Go with extensible logging outputs. |
| [zkits-logger](https://github.com/edoger/zkits-logger) | 15 | 1 | 2020/03/31 | 1 week ago | A powerful zero-dependency JSON logger. |
| [glo](https://github.com/lajosbencz/glo) | 14 | 1 | 2019/01/19 | 2 years ago | PHP Monolog inspired logging facility with identical severity levels. |
| [logrusiowriter](https://github.com/cabify/logrusiowriter) | 12 | 92 | 2019/08/09 | 1 year ago | `io.Writer` implementation using [logrus](https://github.com/sirupsen/logrus) logger. |
| [go-log](https://github.com/subchen/go-log) | 11 | 2 | 2017/05/07 | 3 years ago | Simple and configurable Logging in Go, with level, formatters and writers. |
| [logmatic](https://github.com/mborders/logmatic) | 10 | 2 | 2018/11/07 | 6 months ago | Colorized logger for Golang with dynamic log level configuration. |
| [logdump](https://github.com/ewwwwwqm/logdump) | 9 | 2 | 2017/01/13 | 3 years ago | Package for multi-level logging. |
| [logmatic](https://github.com/borderstech/logmatic) | 9 | 2 | 2018/11/07 | 2 years ago | Colorized logger for Golang with dynamic log level configuration. |
| [logo](https://github.com/mbndr/logo) | 9 | 2 | 2017/02/07 | 6 months ago | Golang logger to different configurable writers. |
| [go-log](https://github.com/pieterclaerhout/go-log) | 8 | 2 | 2019/10/01 | 1 year ago | A logging library with strack traces, object dumping and optional timestamps. |
| [log](https://github.com/aerogo/log) | 8 | 2 | 2017/06/10 | 1 year ago | An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection). |
| [xlog](https://github.com/xfxdev/xlog) | 6 | 1 | 2016/05/05 | 2 years ago | Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format. |
| [kemba](https://github.com/clok/kemba) | 5 | 1 | 2020/07/13 | 5 days ago | A tiny debug logging tool inspired by [debug](https://github.com/visionmedia/debug), great for CLI tools and applications. |

## Machine Learning
        
*Libraries for Machine Learning.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [golearn](https://github.com/sjwhitworth/golearn) | 7909 | 434 | 2013/12/26 | 2 months ago | General Machine Learning library for Go. |
| [gorgonia](https://github.com/gorgonia/gorgonia) | 4088 | 188 | 2016/09/14 | 14 hours ago | graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms. |
| [tfgo](https://github.com/galeone/tfgo) | 1748 | 59 | 2017/05/23 | 1 month ago | Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python. |
| [gosseract](https://github.com/otiai10/gosseract) | 1497 | 48 | 2013/10/11 | 4 days ago | Go package for OCR (Optical Character Recognition), by using Tesseract C++ library. |
| [gorse](https://github.com/zhenghaoz/gorse) | 1299 | 4 | 2018/08/14 | 4 hours ago | An offline recommender system backend based on collaborative filtering written in Go. |
| [goml](https://github.com/cdipaolo/goml) | 1197 | 74 | 2015/06/27 | 1 month ago | On-line Machine Learning in Go. |
| [eaopt](https://github.com/MaxHalford/eaopt) | 740 | 28 | 2016/01/31 | 3 months ago | An evolutionary optimization library. |
| [bayesian](https://github.com/jbrukh/bayesian) | 708 | 34 | 2011/11/23 | 11 months ago | Naive Bayesian Classification for Golang. |
| [CloudForest](https://github.com/ryanbressler/CloudForest) | 686 | 44 | 2012/10/22 | 7 months ago | Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go. |
| [gobrain](https://github.com/goml/gobrain) | 481 | 27 | 2014/04/29 | 7 months ago | Neural Networks written in go. |
| [ocrserver](https://github.com/otiai10/ocrserver) | 388 | 14 | 2015/11/15 | 1 month ago | A simple OCR API server, seriously easy to be deployed by Docker and Heroku. |
| [onnx-go](https://github.com/owulveryck/onnx-go) | 336 | 12 | 2018/08/28 | 1 month ago | Go Interface to Open Neural Network Exchange (ONNX). |
| [go-deep](https://github.com/patrikeh/go-deep) | 317 | 17 | 2017/12/09 | 3 months ago | A feature-rich neural network library in Go. |
| [regommend](https://github.com/muesli/regommend) | 290 | 16 | 2014/02/05 | 1 year ago | Recommendation & collaborative filtering engine. |
| [go-galib](https://github.com/thoj/go-galib) | 185 | 15 | 2009/11/30 | 5 years ago | Genetic Algorithms library written in Go / golang. |
| [goptuna](https://github.com/c-bata/goptuna) | 184 | 8 | 2019/07/24 | 2 weeks ago | Bayesian optimization framework for black-box functions written in Go. Everything will be optimized. |
| [goRecommend](https://github.com/timkaye11/goRecommend) | 174 | 10 | 2014/07/16 | 7 years ago | Recommendation Algorithms library written in Go. |
| [shield](https://github.com/eaigner/shield) | 141 | 11 | 2013/04/10 | 1 year ago | Bayesian text classifier with flexible tokenizers and storage backends for Go. |
| [goga](https://github.com/tomcraven/goga) | 108 | 9 | 2015/10/20 | 4 years ago | Genetic algorithm library for Go. |
| [go-fann](https://github.com/vksnk/go-fann) | 103 | 8 | 2011/03/10 | 6 years ago | Go bindings for Fast Artificial Neural Networks(FANN) library. |
| [libsvm](https://github.com/datastream/libsvm) | 67 | 11 | 2012/07/31 | 5 years ago | libsvm golang version derived work based on LIBSVM 3.14. |
| [gonet](https://github.com/dathoangnd/gonet) | 67 | 5 | 2020/01/11 | 1 year ago | Neural Network for Go. |
| [goscore](https://github.com/asafschers/goscore) | 65 | 7 | 2017/08/19 | 1 year ago | Go Scoring API for PMML. |
| [neural-go](https://github.com/schuyler/neural-go) | 62 | 3 | 2011/10/17 | 10 months ago | Multilayer perceptron network implemented in Go, with training via backpropagation. |
| [go-pr](https://github.com/daviddengcn/go-pr) | 58 | 7 | 2013/06/07 | 8 years ago | Pattern recognition package in Go lang. |
| [neat](https://github.com/jinyeom/neat) | 58 | 13 | 2016/11/17 | 3 years ago | Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT). |
| [go-featureprocessing](https://github.com/nikolaydubina/go-featureprocessing) | 57 | 1 | 2020/12/18 | 3 weeks ago | Fast and convenient feature processing for low latency machine leraning in Go. |
| [fonet](https://github.com/Fontinalis/fonet) | 44 | 5 | 2017/10/03 | 1 month ago | A Deep Neural Network library written in Go. |
| [golinear](https://github.com/danieldk/golinear) | 41 | 6 | 2013/04/05 | 2 years ago | liblinear bindings for Go. |
| [Varis](https://github.com/Xamber/Varis) | 36 | 7 | 2017/10/10 | 2 years ago | Golang Neural Network. |
| [go-cluster](https://github.com/e-XpertSolutions/go-cluster) | 28 | 7 | 2017/10/04 | 2 years ago | Go implementation of the k-modes and k-prototypes clustering algorithms. |
| [godist](https://github.com/e-dard/godist) | 28 | 3 | 2014/09/05 | 6 years ago | Various probability distributions, and associated methods. |
| [probab](https://github.com/ThePaw/probab) | 16 | 2 | 2015/09/14 | 5 years ago | Probability distribution functions. Bayesian inference. Written in pure Go. |
| [evoli](https://github.com/khezen/evoli) | 15 | 5 | 2015/06/12 | 3 months ago | Genetic Algorithm and Particle Swarm Optimization library. |
| [gomind](https://github.com/surenderthakran/gomind) | 13 | 3 | 2017/10/19 | 2 years ago | A simplistic Neural Network Library in Go. |
| [randomForest](https://github.com/malaschitz/randomForest) | 11 | 3 | 2018/10/25 | 1 month ago | Easy to use Random Forest library for Go. |

## Messaging
        
*Libraries that implement messaging systems.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [sarama](https://github.com/Shopify/sarama) | 7407 | 430 | 2013/07/05 | 3 hours ago | Go library for Apache Kafka. |
| [gorush](https://github.com/appleboy/gorush) | 5569 | 190 | 2016/03/22 | 1 day ago | Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm). |
| [machinery](https://github.com/RichardKnop/machinery) | 5396 | 151 | 2015/04/05 | 1 week ago | Asynchronous task queue/job queue based on distributed message passing. |
| [centrifugo](https://github.com/centrifugal/centrifugo) | 5136 | 195 | 2015/03/31 | 9 hours ago | Real-time messaging (Websockets or SockJS) server in Go. |
| [go-socket.io](https://github.com/googollee/go-socket.io) | 4160 | 131 | 2013/07/13 | 1 week ago | socket.io library for golang, a realtime application framework. |
| [nats.go](https://github.com/nats-io/nats.go) | 3439 | 163 | 2012/08/15 | 3 days ago | Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library. |
| [benthos](https://github.com/Jeffail/benthos) | 3217 | 86 | 2016/03/22 | 1 day ago | A message streaming bridge between a range of protocols. |
| [confluent-kafka-go](https://github.com/confluentinc/confluent-kafka-go) | 2781 | 269 | 2016/07/12 | 5 days ago | confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform. |
| [apns2](https://github.com/sideshow/apns2) | 2523 | 77 | 2016/01/05 | 5 months ago | HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps. |
| [mercure](https://github.com/dunglas/mercure) | 2473 | 58 | 2018/07/14 | 1 hour ago | Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events). |
| [melody](https://github.com/olahol/melody) | 2175 | 60 | 2015/05/13 | 1 month ago | Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling. |
| [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) | 1985 | 232 | 2013/12/27 | 4 years ago | gopush-cluster is a go push server cluster. |
| [go-nsq](https://github.com/nsqio/go-nsq) | 1934 | 65 | 2013/08/29 | 2 weeks ago | the official Go package for NSQ. |
| [mangos-v1](https://github.com/nanomsg/mangos-v1) | 1532 | 83 | 2014/10/25 | 1 year ago | Pure go implementation of the Nanomsg ("Scalable Protocols") with transport interoperability. |
| [asynq](https://github.com/hibiken/asynq) | 1355 | 36 | 2019/11/15 | 1 week ago | A simple, reliable, and efficient distributed task queue for Go built on top of Redis. |
| [uniqush-push](https://github.com/uniqush/uniqush-push) | 1264 | 79 | 2011/08/29 | 1 year ago | Redis backed unified push service for server-side notifications to mobile devices. |
| [Beaver](https://github.com/Clivern/Beaver) | 1109 | 27 | 2018/10/20 | 1 month ago | A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps. |
| [EventBus](https://github.com/asaskevich/EventBus) | 942 | 27 | 2014/12/19 | 2 weeks ago | The lightweight event bus with async compatibility. |
| [zmq4](https://github.com/pebbe/zmq4) | 917 | 43 | 2013/10/18 | 2 days ago | Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2). |
| [gollum](https://github.com/trivago/gollum) | 899 | 38 | 2015/06/20 | 1 week ago | A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations. |
| [dbus](https://github.com/godbus/dbus) | 594 | 19 | 2014/03/27 | 2 days ago | Native Go bindings for D-Bus. |
| [golongpoll](https://github.com/jcuga/golongpoll) | 558 | 21 | 2015/11/02 | 2 months ago | HTTP longpoll server library that makes web pub-sub simple. |
| [mangos](https://github.com/nanomsg/mangos) | 420 | 23 | 2018/10/12 | 3 months ago | Pure go implementation of the Nanomsg ("Scalability Protocols") with transport interoperability. |
| [emitter](https://github.com/olebedev/emitter) | 406 | 10 | 2015/11/10 | 1 year ago | Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins. |
| [glue](https://github.com/desertbit/glue) | 379 | 17 | 2015/06/07 | 1 year ago | Robust Go and Javascript Socket Library (Alternative to Socket.io). |
| [pubsub](https://github.com/cskr/pubsub) | 354 | 9 | 2012/04/01 | 1 year ago | Simple pubsub package for go. |
| [bus](https://github.com/mustafaturan/bus) | 211 | 5 | 2019/04/27 | 2 months ago | Minimalist message bus implementation for internal communication. |
| [rabtap](https://github.com/jandelgado/rabtap) | 184 | 11 | 2017/11/11 | 3 months ago | RabbitMQ swiss army knife cli app. |
| [message-bus](https://github.com/vardius/message-bus) | 181 | 8 | 2017/10/04 | 5 months ago | messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD. |
| [guble](https://github.com/smancke/guble) | 148 | 13 | 2015/11/15 | 3 years ago | Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence. |
| [oplog](https://github.com/dailymotion/oplog) | 107 | 92 | 2014/11/06 | 5 years ago | Generic oplog/replication system for REST APIs. |
| [hub](https://github.com/leandro-lugaresi/hub) | 106 | 2 | 2018/04/13 | 8 months ago | A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges. |
| [rabbus](https://github.com/rafaeljesus/rabbus) | 89 | 8 | 2017/05/07 | 2 years ago | A tiny wrapper over amqp exchanges and queues. |
| [drone-line](https://github.com/appleboy/drone-line) | 75 | 5 | 2016/09/13 | 3 weeks ago | Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI. |
| [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) | 67 | 9 | 2017/01/15 | 3 years ago | A tiny wrapper around NSQ topic and channel. |
| [go-mq](https://github.com/cheshir/go-mq) | 65 | 6 | 2017/06/19 | 1 month ago | RabbitMQ client with declarative configuration. |
| [RapidMQ](https://github.com/sybrexsys/RapidMQ) | 62 | 5 | 2016/10/04 | 3 years ago | RapidMQ is a lightweight and reliable library for managing of the local messages queue. |
| [redisqueue](https://github.com/robinjoseph08/redisqueue) | 59 | 2 | 2019/07/07 | 3 months ago | redisqueue provides a producer and consumer of a queue that uses Redis streams. |
| [go-notify](https://github.com/TheCreeper/go-notify) | 54 | 2 | 2015/03/01 | 7 months ago | Native implementation of the freedesktop notification spec. |
| [commander](https://github.com/jeroenrinzema/commander) | 54 | 1 | 2018/04/20 | 2 months ago | A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka. |
| [go-res](https://github.com/jirenius/go-res) | 49 | 2 | 2018/07/15 | 1 month ago | Package for building REST/real-time services where clients are synchronized seamlessly, using NATS and Resgate. |
| [event](https://github.com/agoalofalife/event) | 41 | 4 | 2017/07/02 | 3 years ago | Implementation of the pattern observer. |
| [commander](https://github.com/CloudProud/commander) | 38 | 1 | 2018/04/20 | 1 year ago | A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka. |
| [hare](https://github.com/leozz37/hare) | 27 | 1 | 2020/12/01 | 2 months ago | A user friendly library for sending messages and listening to TCP sockets. |
| [ami](https://github.com/kak-tus/ami) | 20 | 1 | 2018/10/27 | 1 year ago | Go client to reliable queues based on Redis Cluster Streams. |
| [gosd](https://github.com/alexsniffin/gosd) | 18 | 1 | 2020/05/17 | 7 months ago | A library for scheduling when to dispatch a message to a channel. |
| [go-vitotrol](https://github.com/maxatome/go-vitotrol) | 16 | 7 | 2016/11/03 | 4 months ago | Client library to Viessmann Vitotrol web service. |
| [rmqconn](https://github.com/sbabiv/rmqconn) | 15 | 1 | 2019/01/14 | 1 year ago | RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed. |
| [jazz](https://github.com/socifi/jazz) | 12 | 4 | 2018/10/22 | 2 years ago | A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages. |
| [gaurun-client](https://github.com/osamingo/gaurun-client) | 9 | 1 | 2017/06/29 | 3 months ago | Gaurun Client written in Go. |

## Microsoft Office
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [unioffice](https://github.com/unidoc/unioffice) | 2905 | 72 | 2017/08/29 | 3 weeks ago | Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents. |

### Microsoft Excel
        
*Libraries for working with Microsoft Excel.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [excelize](https://github.com/360EntSecGroup-Skylar/excelize) | 9039 | 200 | 2016/08/29 | 4 hours ago | Golang library for reading and writing Microsoft Excel™ (XLSX) files. |
| [xlsx](https://github.com/tealeg/xlsx) | 5050 | 175 | 2011/06/28 | 4 days ago | Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs. |
| [xlsx](https://github.com/plandem/xlsx) | 136 | 13 | 2017/08/26 | 8 months ago | Fast and safe way to read/update your existing Microsoft Excel files in Go programs. |
| [go-excel](https://github.com/szyhf/go-excel) | 124 | 3 | 2017/09/03 | 1 month ago | A simple and light reader to read a relate-db-like excel as a table. |
| [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) | 15 | 2 | 2017/03/13 | 2 years ago | Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files. |

## Miscellaneous
        

### Dependency Injection
        
*Libraries for working with dependency injection.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [fx](https://github.com/uber-go/fx) | 2083 | 60 | 2016/10/27 | 2 days ago | A dependency injection based application framework for Go (built on top of dig). |
| [dig](https://github.com/uber-go/dig) | 1973 | 49 | 2017/03/21 | 2 weeks ago | A reflection based dependency injection toolkit for Go. |
| [container](https://github.com/golobby/container) | 206 | 6 | 2019/09/23 | 6 days ago | A powerful IoC Container with fluent and easy-to-use interface. |
| [dingo](https://github.com/i-love-flamingo/dingo) | 105 | 24 | 2018/10/29 | 2 months ago | A dependency injection toolkit for Go, based on Guice. |
| [di](https://github.com/goava/di) | 95 | 6 | 2020/02/03 | 2 weeks ago | A dependency injection container for go programming language. |
| [di](https://github.com/goioc/di) | 82 | 4 | 2020/06/11 | 2 months ago | Spring-inspired Dependency Injection Container. |
| [inject](https://github.com/defval/inject) | 53 | 1 | 2019/02/03 | 1 year ago | A reflection based dependency injection container with simple interface. |
| [alice](https://github.com/magic003/alice) | 44 | 2 | 2017/04/08 | 4 years ago | Additive dependency injection container for Golang. |
| [linker](https://github.com/logrange/linker) | 32 | 4 | 2018/12/04 | 1 year ago | A reflection based dependency injection and inversion of control library with components lifecycle support. |
| [wire](https://github.com/Fs02/wire) | 32 | 2 | 2018/07/05 | 1 year ago | Strict Runtime Dependency Injection for Golang. |
| [gocontainer](https://github.com/vardius/gocontainer) | 14 | 0 | 2019/06/06 | 1 year ago | Simple Dependency Injection Container. |

### Project Layout
        
*Unofficial set of patterns for structuring projects.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [project-layout](https://github.com/golang-standards/project-layout) | 24833 | 536 | 2017/09/09 | 1 month ago | Set of common historical and emerging project layout patterns in the Go ecosystem. |
| [go-restful-api](https://github.com/qiangxue/go-restful-api) | 1038 | 52 | 2016/08/15 | 1 year ago | An idiomatic Go RESTful API starter kit following SOLID principles and Clean Architecture with a common project layout. |
| [modern-go-application](https://github.com/sagikazarmark/modern-go-application) | 980 | 24 | 2018/09/14 | 5 months ago | Go application boilerplate and example applying modern practices. |
| [cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) | 461 | 9 | 2016/12/18 | 5 months ago | A Go application boilerplate template for quick starting projects following production best practices. |
| [seed](https://github.com/golang-templates/seed) | 181 | 4 | 2020/04/30 | 8 hours ago | Go application GitHub repository template. |
| [scaffold](https://github.com/catchplay/scaffold) | 97 | 5 | 2018/12/11 | 2 years ago | Scaffold generates a starter Go project layout. Lets you focus on business logic implemented. |
| [go-sample](https://github.com/zitryss/go-sample) | 86 | 1 | 2019/01/24 | 2 years ago | A sample layout for Go application projects with the real code. |
| [go-todo-backend](https://github.com/Fs02/go-todo-backend) | 80 | 4 | 2020/06/25 | 1 month ago | Go Todo Backend example using modular project layout for product microservice. |
| [gobase](https://github.com/wajox/gobase) | 8 | 3 | 2020/12/15 | 2 months ago | A simple skeleton for golang application with basic setup for real golang application. |

### Strings
        
*Libraries for working with strings.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [xstrings](https://github.com/huandu/xstrings) | 906 | 24 | 2015/01/06 | 6 months ago | Collection of useful string functions ported from other languages. |
| [strutil](https://github.com/ozgio/strutil) | 121 | 2 | 2018/08/16 | 3 weeks ago | String utilities. |
| [stringy](https://github.com/gobeam/stringy) | 67 | 2 | 2020/04/03 | 1 month ago | String manipulation library to convert string to camel case, snake case, kebab case / slugify etc. |
| [Stringy](https://github.com/gobeam/Stringy) | 30 | 1 | 2020/04/03 | 1 year ago | String manipulation library to convert string to camel case, snake case, kebab case / slugify etc. |

### Uncategorized
        
*These libraries were placed here because none of the other categories seemed to fit.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gopsutil](https://github.com/shirou/gopsutil) | 6496 | 204 | 2014/04/18 | 2 days ago | Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc). |
| [archiver](https://github.com/mholt/archiver) | 3259 | 52 | 2016/04/08 | 3 weeks ago | Library and command for making and extracting .zip and .tar.gz archives. |
| [gofakeit](https://github.com/brianvoe/gofakeit) | 1940 | 20 | 2015/04/24 | 3 weeks ago | Random data generator written in go. |
| [gatus](https://github.com/TwinProduction/gatus) | 1586 | 24 | 2019/09/04 | 8 hours ago | Automated service health dashboard. |
| [gosms](https://github.com/haxpax/gosms) | 1337 | 57 | 2015/01/23 | 5 months ago | Your own local SMS gateway in Go that can be used to send SMS. |
| [go-resiliency](https://github.com/eapache/go-resiliency) | 1213 | 27 | 2014/11/29 | 8 months ago | Resiliency patterns for golang. |
| [base64Captcha](https://github.com/mojocn/base64Captcha) | 1134 | 47 | 2017/12/12 | 2 days ago | Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha. |
| [go-commons-pool](https://github.com/jolestar/go-commons-pool) | 963 | 50 | 2015/12/28 | 2 months ago | Generic object pool for Golang. |
| [llvm](https://github.com/llir/llvm) | 716 | 33 | 2014/09/19 | 3 days ago | Library for interacting with LLVM IR in pure Go. |
| [shortid](https://github.com/teris-io/shortid) | 684 | 10 | 2016/01/04 | 7 months ago | Distributed generation of super short, unique, non-sequential, URL friendly IDs. |
| [ghorg](https://github.com/gabrie30/ghorg) | 450 | 12 | 2018/03/29 | 2 months ago | Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, and Bitbucket. |
| [health](https://github.com/dimiro1/health) | 424 | 6 | 2016/03/08 | 1 year ago | Easy to use, extensible health check library. |
| [go-conv](https://github.com/cstockton/go-conv) | 370 | 9 | 2016/10/11 | 4 years ago | Package conv provides fast and intuitive conversions across Go types. |
| [banner](https://github.com/dimiro1/banner) | 348 | 6 | 2016/03/25 | 6 months ago | Add beautiful banners into your Go applications. |
| [gountries](https://github.com/pariz/gountries) | 310 | 10 | 2016/01/13 | 2 months ago | Package that exposes country and subdivision data. |
| [stateless](https://github.com/qmuntal/stateless) | 278 | 5 | 2019/09/11 | 3 weeks ago | A fluent library for creating state machines. |
| [ffmt](https://github.com/go-ffmt/ffmt) | 231 | 7 | 2015/02/14 | 3 months ago | Beautify data display for Humans. |
| [shoutrrr](https://github.com/containrrr/shoutrrr) | 219 | 9 | 2019/04/11 | 5 days ago | Notification library providing easy access to various messaging services like slack, mattermost, gotify and smtp among others. |
| [lk](https://github.com/hyperboloide/lk) | 210 | 7 | 2016/07/14 | 1 year ago | A simple licensing library for golang. |
| [antch](https://github.com/antchfx/antch) | 207 | 16 | 2017/09/28 | 1 year ago | A fast, powerful and extensible web crawling & scraping framework. |
| [battery](https://github.com/distatus/battery) | 189 | 4 | 2016/03/12 | 1 month ago | Cross-platform, normalized battery information library. |
| [healthcheck](https://github.com/etherlabsio/healthcheck) | 186 | 8 | 2017/08/18 | 3 weeks ago | An opinionated and concurrent health-check HTTP handler for RESTful services. |
| [bitio](https://github.com/icza/bitio) | 160 | 8 | 2016/05/31 | 1 year ago | Highly optimized bit-level Reader and Writer for Go. |
| [stats](https://github.com/go-playground/stats) | 152 | 3 | 2015/09/14 | 4 years ago | Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc... |
| [go-unarr](https://github.com/gen2brain/go-unarr) | 140 | 6 | 2015/11/01 | 9 months ago | Decompression library for RAR, TAR, ZIP and 7z archives. |
| [turtle](https://github.com/hackebrot/turtle) | 122 | 2 | 2017/09/08 | 1 week ago | Emojis for Go. |
| [gommit](https://github.com/antham/gommit) | 95 | 3 | 2016/08/30 | 2 weeks ago | Analyze git commit messages to ensure they follow defined patterns. |
| [gotoprom](https://github.com/cabify/gotoprom) | 90 | 95 | 2018/10/10 | 1 year ago | Type-safe metrics builder wrapper library for the official Prometheus client. |
| [indigo](https://github.com/osamingo/indigo) | 86 | 1 | 2016/08/31 | 5 months ago | Distributed unique ID generator of using Sonyflake and encoded by Base58. |
| [captcha](https://github.com/steambap/captcha) | 78 | 5 | 2017/09/12 | 2 weeks ago | Package captcha provides an easy to use, unopinionated API for captcha generation. |
| [morse](https://github.com/alwindoss/morse) | 68 | 3 | 2018/08/15 | 2 years ago | Library to convert to and from morse code. |
| [persian](https://github.com/mavihq/persian) | 56 | 5 | 2017/10/16 | 3 weeks ago | Some utilities for Persian language in go. |
| [pdfgen](https://github.com/hyperboloide/pdfgen) | 52 | 4 | 2015/11/30 | 3 years ago | HTTP service to generate PDF from Json requests. |
| [xkg](https://github.com/go-xkg/xkg) | 52 | 2 | 2015/01/05 | 6 years ago | X Keyboard Grabber. |
| [faker](https://github.com/pioz/faker) | 39 | 3 | 2020/07/22 | 2 months ago | Random fake data and struct generator for Go. |
| [browscap_go](https://github.com/digitalcrab/browscap_go) | 37 | 6 | 2014/09/18 | 1 year ago | GoLang Library for [Browser Capabilities Project](http://browscap.org/). |
| [datacounter](https://github.com/miolini/datacounter) | 36 | 1 | 2015/10/14 | 1 year ago | Go counters for readers/writer/http.ResponseWriter. |
| [autoflags](https://github.com/artyom/autoflags) | 34 | 5 | 2014/05/15 | 2 months ago | Go package to automatically define command line flags from struct fields. |
| [sandid](https://github.com/aofei/sandid) | 30 | 1 | 2018/06/12 | 4 months ago | Every grain of sand on earth has its own ID. |
| [url-shortener](https://github.com/pantrif/url-shortener) | 29 | 1 | 2018/06/04 | 3 years ago | A modern, powerful, and robust URL shortener microservice with mysql support. |
| [gosh](https://github.com/osamingo/gosh) | 26 | 0 | 2018/05/25 | 6 months ago | Provide Go Statistics Handler, Struct, Measure Method. |
| [xdg](https://github.com/rkoesters/xdg) | 26 | 3 | 2013/12/15 | 1 month ago | FreeDesktop.org (xdg) Specs implemented in Go. |
| [metrics](https://github.com/pascaldekloe/metrics) | 20 | 1 | 2019/01/29 | 4 months ago | Library for metrics instrumentation and Prometheus exposition. |
| [shellwords](https://github.com/Wing924/shellwords) | 15 | 1 | 2017/09/28 | 3 years ago | A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell. |
| [anagent](https://github.com/mudler/anagent) | 13 | 2 | 2017/12/29 | 2 years ago | Minimalistic, pluggable Golang evloop/timer handler with dependency-injection. |
| [avgRating](https://github.com/kirillDanshin/avgRating) | 10 | 2 | 2017/08/05 | 3 years ago | Calculate average score and rating based on Wilson Score Equation. |
| [hostutils](https://github.com/Wing924/hostutils) | 9 | 1 | 2017/09/26 | 2 years ago | A golang library for packing and unpacking FQDNs list. |
| [numa](https://github.com/lrita/numa) | 6 | 3 | 2018/12/10 | 6 months ago | NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code. |

## Natural Language Processing
        
*Libraries for working with human languages.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [prose](https://github.com/jdkato/prose) | 2772 | 61 | 2017/02/17 | 5 months ago | Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only. |
| [gse](https://github.com/go-ego/gse) | 1598 | 58 | 2017/06/23 | 1 week ago | Go efficient text segmentation; support english, chinese, japanese and other. |
| [gojieba](https://github.com/yanyiwu/gojieba) | 1538 | 68 | 2015/09/12 | 1 month ago | This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm. |
| [when](https://github.com/olebedev/when) | 1120 | 25 | 2016/12/27 | 4 months ago | Natural EN and RU language date/time parser with pluggable rules. |
| [go-pinyin](https://github.com/mozillazg/go-pinyin) | 983 | 37 | 2014/11/09 | 2 months ago | CN Hanzi to Hanyu Pinyin converter. |
| [spago](https://github.com/nlpodyssey/spago) | 942 | 28 | 2020/01/05 | 1 week ago | Self-contained Machine Learning and Natural Language Processing library in Go. |
| [kagome](https://github.com/ikawaha/kagome) | 579 | 22 | 2014/06/26 | 1 month ago | JP morphological analyzer written in pure Go. |
| [whatlanggo](https://github.com/abadojack/whatlanggo) | 498 | 15 | 2017/02/20 | 5 months ago | Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc). |
| [nlp](https://github.com/shixzie/nlp) | 369 | 23 | 2017/01/25 | 3 years ago | Extract values from strings and fill your structs with nlp. |
| [nlp](https://github.com/james-bowman/nlp) | 331 | 24 | 2017/03/15 | 2 months ago | Go Natural Language Processing library supporting LSA (Latent Semantic Analysis). |
| [sentences](https://github.com/neurosnap/sentences) | 306 | 14 | 2015/08/07 | 3 weeks ago | Sentence tokenizer:  converts text into a list of sentences. |
| [getlang](https://github.com/rylans/getlang) | 118 | 4 | 2018/03/01 | 6 months ago | Fast natural language detection package. |
| [go-nlp](https://github.com/nuance/go-nlp) | 89 | 6 | 2011/05/02 | 9 years ago | Utilities for working with discrete probability distributions and other tools useful for doing NLP work. |
| [go-unidecode](https://github.com/mozillazg/go-unidecode) | 89 | 2 | 2016/07/08 | 2 months ago | ASCII transliterations of Unicode text. |
| [RAKE.Go](https://github.com/afjoseph/RAKE.Go) | 82 | 7 | 2016/12/17 | 1 year ago | Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE). |
| [gounidecode](https://github.com/fiam/gounidecode) | 73 | 5 | 2012/05/01 | 5 years ago | Unicode transliterator (also known as unidecode) for Go. |
| [textcat](https://github.com/pebbe/textcat) | 65 | 6 | 2012/09/21 | 4 months ago | Go package for n-gram based text categorization, with support for utf-8 and raw text. |
| [go-stem](https://github.com/agonopol/go-stem) | 61 | 4 | 2011/09/23 | 3 years ago | Implementation of the porter stemming algorithm. |
| [MMSEGO](https://github.com/awsong/MMSEGO) | 59 | 5 | 2012/04/18 | 9 years ago | This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm. |
| [stemmer](https://github.com/dchest/stemmer) | 49 | 4 | 2011/03/21 | 4 years ago | Stemmer packages for Go programming language. Includes English and German stemmers. |
| [go2vec](https://github.com/danieldk/go2vec) | 41 | 7 | 2015/01/27 | 2 years ago | Reader and utility functions for word2vec embeddings. |
| [porter2](https://github.com/zentures/porter2) | 40 | 3 | 2015/01/21 | 9 months ago | Really fast Porter 2 stemmer. |
| [petrovich](https://github.com/striker2000/petrovich) | 34 | 1 | 2016/12/26 | 4 months ago | Petrovich is the library which inflects Russian names to given grammatical case. |
| [address](https://github.com/bojanz/address) | 31 | 2 | 2020/10/07 | 1 month ago | Handles address representation, validation and formatting. |
| [snowball](https://github.com/goodsign/snowball) | 27 | 1 | 2012/12/11 | 4 years ago | Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/). |
| [mystem](https://github.com/dveselov/mystem) | 26 | 3 | 2016/08/30 | 4 years ago | CGo bindings to Yandex.Mystem - russian morphology analyzer. |
| [paicehusk](https://github.com/rookii/paicehusk) | 26 | 3 | 2012/09/29 | 7 years ago | Golang implementation of the Paice/Husk Stemming Algorithm. |
| [go-localize](https://github.com/m1/go-localize) | 25 | 2 | 2019/12/23 | 3 months ago | Simple and easy to use i18n (Internationalization and localization) engine - used for translating locale strings. |
| [iuliia-go](https://github.com/mehanizm/iuliia-go) | 23 | 2 | 2020/04/27 | 3 weeks ago | Transliterate Cyrillic → Latin in every possible way. |
| [icu](https://github.com/goodsign/icu) | 19 | 0 | 2012/12/11 | 4 years ago | Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1. |
| [golibstemmer](https://github.com/rjohnsondev/golibstemmer) | 18 | 2 | 2012/08/06 | 7 years ago | Go bindings for the snowball libstemmer library including porter 2. |
| [govader](https://github.com/jonreiter/govader) | 15 | 1 | 2020/01/19 | 4 months ago | Go implementation of [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment). |
| [gotokenizer](https://github.com/xujiajun/gotokenizer) | 12 | 1 | 2018/10/11 | 2 years ago | A tokenizer based on the dictionary and Bigram language models for Go. (Now only support chinese segmentation) |
| [shamoji](https://github.com/osamingo/shamoji) | 12 | 2 | 2017/07/23 | 5 months ago | The shamoji is word filtering package written in Go. |
| [transliterator](https://github.com/alexsergivan/transliterator) | 12 | 1 | 2020/04/17 | 1 year ago | Provides one-way string transliteration with supporting of language-specific transliteration rules. |
| [detectlanguage-go](https://github.com/detectlanguage/detectlanguage-go) | 10 | 2 | 2019/12/14 | 9 months ago | Language Detection API Go Client. Supports batch requests, short phrase or single word language detection. |
| [libtextcat](https://github.com/goodsign/libtextcat) | 10 | 2 | 2012/12/10 | 8 years ago | Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2. |
| [porter](https://github.com/a2800276/porter) | 8 | 1 | 2013/09/17 | 7 years ago | This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm. |
| [gosentiwordnet](https://github.com/dinopuguh/gosentiwordnet) | 7 | 1 | 2020/04/21 | 4 months ago | Sentiment analyzer using sentiwordnet lexicon in Go. |

## Networking
        
*Libraries for working with various layers of the network.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [fasthttp](https://github.com/valyala/fasthttp) | 15529 | 405 | 2015/10/18 | 4 days ago | Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http. |
| [kcptun](https://github.com/xtaci/kcptun) | 12497 | 595 | 2016/02/26 | 2 weeks ago | Extremely simple & fast udp tunnel based on KCP protocol. |
| [webrtc](https://github.com/pion/webrtc) | 7445 | 245 | 2018/05/18 | 30 minutes ago | A pure Go implementation of the WebRTC API. |
| [dns](https://github.com/miekg/dns) | 5647 | 174 | 2010/08/03 | 4 days ago | Go library for working with DNS. |
| [quic-go](https://github.com/lucas-clemente/quic-go) | 5562 | 200 | 2016/04/06 | 4 days ago | An implementation of the QUIC protocol in pure Go. |
| [gnet](https://github.com/panjf2000/gnet) | 4834 | 140 | 2019/02/24 | 1 hour ago | `gnet` is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go. |
| [gopacket](https://github.com/google/gopacket) | 4231 | 141 | 2015/03/16 | 6 days ago | Go library for packet processing with libpcap bindings. |
| [httplab](https://github.com/gchaincl/httplab) | 3705 | 64 | 2017/02/08 | 2 years ago | HTTPLabs let you inspect HTTP requests and forge responses. |
| [kcp-go](https://github.com/xtaci/kcp-go) | 3011 | 148 | 2015/06/16 | 2 months ago | KCP - Fast and Reliable ARQ Protocol. |
| [gobgp](https://github.com/osrg/gobgp) | 2240 | 119 | 2014/09/14 | 1 week ago | BGP implemented in the Go Programming Language. |
| [ssh](https://github.com/gliderlabs/ssh) | 2075 | 54 | 2016/10/03 | 2 weeks ago | Higher-level API for building SSH servers (wraps crypto/ssh). |
| [fortio](https://github.com/fortio/fortio) | 1963 | 43 | 2017/10/10 | 2 weeks ago | Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC. |
| [water](https://github.com/songgao/water) | 1262 | 47 | 2013/03/25 | 2 months ago | Simple TUN/TAP library. |
| [go-getter](https://github.com/hashicorp/go-getter) | 1194 | 230 | 2015/10/12 | 1 week ago | Go library for downloading files or directories from various sources using a URL. |
| [gev](https://github.com/Allenxuxu/gev) | 1189 | 38 | 2019/09/01 | 1 week ago | gev is a lightweight, fast non-blocking TCP network library based on Reactor mode. |
| [nff-go](https://github.com/intel-go/nff-go) | 1071 | 81 | 2017/03/29 | 2 months ago | Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF). |
| [sftp](https://github.com/pkg/sftp) | 1023 | 56 | 2013/11/05 | 2 days ago | Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt. |
| [grab](https://github.com/cavaliercoder/grab) | 872 | 17 | 2016/01/05 | 5 months ago | Go package for managing file downloads. |
| [ftp](https://github.com/jlaffaye/ftp) | 814 | 25 | 2011/05/06 | 1 month ago | Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959). |
| [mdns](https://github.com/hashicorp/mdns) | 779 | 230 | 2014/01/29 | 2 months ago | Simple mDNS (Multicast DNS) client/server library in Golang. |
| [gosnmp](https://github.com/gosnmp/gosnmp) | 738 | 50 | 2012/08/27 | 2 weeks ago | Native Go library for performing SNMP actions. |
| [vssh](https://github.com/yahoo/vssh) | 721 | 20 | 2020/06/09 | 7 months ago | Go library for building network and server automation over SSH protocol. |
| [lhttp](https://github.com/fanux/lhttp) | 624 | 58 | 2015/12/29 | 3 years ago | Powerful websocket framework, build your IM server more easily. |
| [cidranger](https://github.com/yl2chen/cidranger) | 623 | 16 | 2017/08/21 | 3 months ago | Fast IP to CIDR lookup for Go. |
| [gosnmp](https://github.com/soniah/gosnmp) | 563 | 46 | 2012/08/27 | 9 months ago | Native Go library for performing SNMP actions. |
| [peerdiscovery](https://github.com/schollz/peerdiscovery) | 492 | 18 | 2018/04/22 | 1 month ago | Pure Go library for cross-platform local peer discovery using UDP multicast. |
| [gotcp](https://github.com/gansidui/gotcp) | 485 | 40 | 2014/04/13 | 4 years ago | Go package for quickly writing tcp applications. |
| [stun](https://github.com/gortc/stun) | 466 | 21 | 2016/04/24 | 1 month ago | Go implementation of RFC 5389 STUN protocol. |
| [go-stun](https://github.com/ccding/go-stun) | 445 | 15 | 2013/08/17 | 3 months ago | Go implementation of the STUN client (RFC 3489 and RFC 5389). |
| [gopcap](https://github.com/akrennmair/gopcap) | 427 | 23 | 2009/11/19 | 1 month ago | Go wrapper for libpcap. |
| [gmqtt](https://github.com/DrmagicE/gmqtt) | 400 | 26 | 2018/09/16 | 1 day ago | Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1. |
| [raw](https://github.com/mdlayher/raw) | 397 | 13 | 2015/07/06 | 2 months ago | Package raw enables reading and writing data at the device driver level for a network interface. |
| [tcp_server](https://github.com/firstrow/tcp_server) | 381 | 19 | 2014/10/13 | 3 months ago | Go library for building tcp servers faster. |
| [gaio](https://github.com/xtaci/gaio) | 365 | 14 | 2019/12/20 | 1 month ago | High performance async-io networking for Golang in proactor mode. |
| [winrm](https://github.com/masterzen/winrm) | 315 | 19 | 2013/12/30 | 2 weeks ago | Go WinRM client to remotely execute commands on Windows machines. |
| [arp](https://github.com/mdlayher/arp) | 256 | 10 | 2015/07/06 | 1 year ago | Package arp implements the ARP protocol, as described in RFC 826. |
| [buffstreams](https://github.com/StabbyCutyou/buffstreams) | 244 | 14 | 2015/06/29 | 11 months ago | Streaming protocolbuffer data over TCP made easy. |
| [ethernet](https://github.com/mdlayher/ethernet) | 225 | 13 | 2015/07/03 | 2 years ago | Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags. |
| [gnxi](https://github.com/google/gnxi) | 183 | 32 | 2017/09/26 | 2 months ago | A collection of tools for Network Management that use the gNMI and gNOI protocols. |
| [jazigo](https://github.com/udhos/jazigo) | 166 | 13 | 2016/06/07 | 1 year ago | Jazigo is a tool written in Go for retrieving configuration for multiple network devices. |
| [utp](https://github.com/anacrolix/utp) | 159 | 17 | 2015/03/20 | 5 months ago | Go uTP micro transport protocol implementation. |
| [canopus](https://github.com/zubairhamed/canopus) | 144 | 14 | 2015/02/24 | 3 years ago | CoAP Client/Server implementation (RFC 7252). |
| [sslb](https://github.com/eduardonunesp/sslb) | 130 | 9 | 2015/10/18 | 1 year ago | It's a Super Simples Load Balancer, just a little project to achieve some kind of performance. |
| [xtcp](https://github.com/xfxdev/xtcp) | 121 | 15 | 2016/03/31 | 1 year ago | TCP Server Framework with simultaneous full duplex communication, graceful shutdown, and custom protocol. |
| [dhcp6](https://github.com/mdlayher/dhcp6) | 70 | 4 | 2015/05/22 | 2 years ago | Package dhcp6 implements a DHCPv6 server, as described in RFC 3315. |
| [ether](https://github.com/songgao/ether) | 69 | 4 | 2014/05/21 | 5 years ago | Cross-platform Go package for sending and receiving ethernet frames. |
| [packet](https://github.com/aerogo/packet) | 56 | 5 | 2017/10/29 | 1 year ago | Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed. |
| [linkio](https://github.com/ian-kent/linkio) | 49 | 2 | 2014/12/24 | 3 years ago | Network link speed simulation for Reader/Writer interfaces. |
| [portproxy](https://github.com/aybabtme/portproxy) | 45 | 0 | 2014/12/13 | 6 years ago | Simple TCP proxy which adds CORS support to API's which don't support it. |
| [go-powerdns](https://github.com/joeig/go-powerdns) | 36 | 2 | 2018/06/21 | 2 weeks ago | PowerDNS API bindings for Golang. |
| [graval](https://github.com/koofr/graval) | 26 | 8 | 2014/04/22 | 9 months ago | Experimental FTP server framework. |
| [publicip](https://github.com/polera/publicip) | 23 | 2 | 2016/12/28 | 4 years ago | Package publicip returns your public facing IPv4 address (internet egress). |
| [panoptes-stream](https://github.com/yahoo/panoptes-stream) | 23 | 9 | 2020/10/09 | 4 months ago | A cloud native distributed streaming network telemetry (gNMI, Juniper JTI and Cisco MDT). |
| [golibwireshark](https://github.com/sunwxg/golibwireshark) | 20 | 2 | 2015/11/16 | 3 years ago | Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data. |
| [gohooks](https://github.com/averageflow/gohooks) | 12 | 1 | 2020/10/30 | 6 months ago | GoHooks make it easy to send and consume secured web-hooks from a Go application. Inspired by Spatie's Laravel Webhook Client and Server. |
| [goshark](https://github.com/sunwxg/goshark) | 11 | 1 | 2015/11/01 | 3 years ago | Package goshark use tshark to decode IP packet and create data struct to analyse packet. |
| [llb](https://github.com/kirillDanshin/llb) | 11 | 1 | 2016/02/21 | 5 years ago | It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response. |
| [httpproxy](https://github.com/wzshiming/httpproxy) | 9 | 2 | 2018/07/18 | 6 months ago | HTTP proxy handler and dialer. |
| [tspool](https://github.com/two/tspool) | 9 | 1 | 2018/10/27 | 2 years ago | A TCP Library use worker pool to improve performance and protect your server. |
| [gosocsvr](https://github.com/Rakeki/gosocsvr) | 5 | 2 | 2019/11/12 | 1 year ago | Socket server made simple. |

### HTTP Clients
        
*Libraries for making HTTP requests.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [resty](https://github.com/go-resty/resty) | 4519 | 88 | 2015/08/28 | 2 months ago | Simple HTTP and REST client for Go inspired by Ruby rest-client. |
| [heimdall](https://github.com/gojek/heimdall) | 1976 | 50 | 2018/01/19 | 2 weeks ago | An enchanced http client with retry and hystrix capabilities. |
| [grequests](https://github.com/levigross/grequests) | 1801 | 34 | 2015/06/11 | 7 months ago | A Go "clone" of the great and famous Requests library. |
| [sling](https://github.com/dghubble/sling) | 1333 | 32 | 2015/04/02 | 1 month ago | Sling is a Go HTTP client library for creating and sending API requests. |
| [gentleman](https://github.com/h2non/gentleman) | 904 | 20 | 2016/02/21 | 4 months ago | Full-featured plugin-driven HTTP client library. |
| [pester](https://github.com/sethgrid/pester) | 555 | 6 | 2015/05/20 | 1 year ago | Go HTTP client calls with retries, backoff, and concurrency. |
| [request](https://github.com/monaco-io/request) | 126 | 10 | 2020/03/25 | 1 month ago | HTTP client for golang. If you have experience about axios or requests, you will love it. No 3rd dependency. |
| [sreq](https://github.com/winterssy/sreq) | 50 | 0 | 2019/12/04 | 1 year ago | A simple, user-friendly and concurrent safe HTTP request library for Go. |
| [rq](https://github.com/ddo/rq) | 39 | 3 | 2017/12/26 | 1 year ago | A nicer interface for golang stdlib HTTP client. |
| [go-http-client](https://github.com/bozd4g/go-http-client) | 23 | 1 | 2019/12/14 | 2 months ago | Make http calls simply and easily. |
| [httpretry](https://github.com/ybbus/httpretry) | 14 | 2 | 2020/02/05 | 1 year ago | Enriches the default go HTTP client with retry functionality. |

## OpenGL
        
*Libraries for using OpenGL in Go.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [glfw](https://github.com/go-gl/glfw) | 1114 | 39 | 2013/05/19 | 2 months ago | Go bindings for GLFW 3. |
| [gl](https://github.com/go-gl/gl) | 816 | 39 | 2015/02/22 | 2 months ago | Go bindings for OpenGL (generated via glow). |
| [mathgl](https://github.com/go-gl/mathgl) | 382 | 28 | 2013/02/13 | 9 months ago | Pure Go math package specialized for 3D math, with inspiration from GLM. |
| [gl](https://github.com/goxjs/gl) | 150 | 15 | 2015/05/18 | 6 months ago | Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android). |
| [glfw](https://github.com/goxjs/glfw) | 70 | 7 | 2014/12/27 | 1 year ago | Go cross-platform glfw library for creating an OpenGL context and receiving events. |
| [go-glmatrix](https://github.com/technohippy/go-glmatrix) | 2 | 1 | 2020/07/02 | 5 months ago | Go port of [glMatrix](http://glmatrix.net/) library. |

## ORM
        
*Libraries that implement Object-Relational Mapping or datamapping techniques.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gorm](https://github.com/go-gorm/gorm) | 24418 | 497 | 2013/10/25 | 4 days ago | The fantastic ORM library for Golang, aims to be developer friendly. |
| [ent](https://github.com/ent/ent) | 7656 | 121 | 2019/06/12 | 1 hour ago | An entity framework for Go. Simple, yet powerful ORM for modeling and querying data. |
| [ent](https://github.com/facebook/ent) | 6615 | 123 | 2019/06/12 | 5 months ago | An entity framework for Go. Simple, yet powerful ORM for modeling and querying data. |
| [xorm](https://github.com/go-xorm/xorm) | 6186 | 262 | 2013/05/09 | 1 year ago | Simple and powerful ORM for Go. |
| [pg](https://github.com/go-pg/pg) | 4717 | 90 | 2013/04/24 | 7 hours ago | PostgreSQL ORM with focus on PostgreSQL specific features and performance. |
| [sqlboiler](https://github.com/volatiletech/sqlboiler) | 4053 | 82 | 2016/02/21 | 2 days ago | ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema. |
| [gorp](https://github.com/go-gorp/gorp) | 3501 | 113 | 2012/01/04 | 4 months ago | Go Relational Persistence, ORM-ish library for Go. |
| [ent](https://github.com/facebookincubator/ent) | 3067 | 65 | 2019/06/12 | 10 months ago | An entity framework for Go. Simple, yet powerful ORM for modeling and querying data. |
| [db](https://github.com/upper/db) | 2646 | 61 | 2013/10/23 | 34 minutes ago | Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers. |
| [gormt](https://github.com/xxjwxc/gormt) | 1288 | 18 | 2019/05/05 | 3 days ago | Mysql database to golang gorm struct. |
| [reform](https://github.com/go-reform/reform) | 1149 | 23 | 2016/02/25 | 2 weeks ago | Better ORM for Go, based on non-empty interfaces and code generation. |
| [pop](https://github.com/gobuffalo/pop) | 1090 | 24 | 2018/02/07 | 1 week ago | Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. |
| [go-queryset](https://github.com/jirfag/go-queryset) | 622 | 22 | 2017/09/03 | 1 week ago | 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM. |
| [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) | 601 | 15 | 2017/12/27 | 3 months ago | A flexible and powerful SQL string builder library plus a zero-config ORM. |
| [qbs](https://github.com/coocood/qbs) | 549 | 45 | 2013/02/02 | 4 years ago | Stands for Query By Struct. A Go ORM. |
| [rel](https://github.com/go-rel/rel) | 372 | 8 | 2019/10/06 | 1 week ago | Modern Database Access Layer for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API. |
| [zoom](https://github.com/albrow/zoom) | 277 | 19 | 2013/07/17 | 1 year ago | Blazing-fast datastore and querying engine built on Redis. |
| [grimoire](https://github.com/Fs02/grimoire) | 149 | 6 | 2018/03/05 | 11 months ago | Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3). |
| [gosql](https://github.com/rushteam/gosql) | 143 | 6 | 2020/04/27 | 3 weeks ago | A easy ORM for mysql. |
| [gorm](https://github.com/jinzhu/gorm) | 137 | 10 | 2013/10/25 | 10 months ago | The fantastic ORM library for Golang, aims to be developer friendly. |
| [go-store](https://github.com/gosuri/go-store) | 102 | 9 | 2015/03/22 | 4 years ago | Simple and fast Redis backed key-value store library for Go. |
| [marlow](https://github.com/dadleyy/marlow) | 83 | 5 | 2017/09/15 | 10 months ago | Generated ORM from project structs for compile time safety assurances. |
| [go-firestorm](https://github.com/jschoedt/go-firestorm) | 23 | 1 | 2018/12/04 | 2 months ago | A simple ORM for Google/Firebase Cloud Firestore. |
| [lore](https://github.com/abrahambotros/lore) | 7 | 1 | 2017/04/29 | 3 years ago | Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go. |
| [marlow](https://github.com/marlow/marlow) | 6 | 2 | 2020/08/11 | 10 months ago | Generated ORM from project structs for compile time safety assurances. |
| [rel](https://github.com/Fs02/rel) | 1 | 0 | 2019/10/06 | 9 months ago | Golang SQL Repository Layer for Clean (Onion) Architecture. |

## Package Management
        
*Unofficial libraries for package and dependency management.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [dep](https://github.com/golang/dep) | 13159 | 267 | 2016/10/07 | 10 months ago | Go dependency tool. |
| [glide](https://github.com/Masterminds/glide) | 8109 | 193 | 2014/07/09 | 4 months ago | Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip. |
| [godep](https://github.com/tools/godep) | 5612 | 147 | 2013/05/01 | 3 years ago | dependency tool for go, godep helps build packages reproducibly by fixing their dependencies. |
| [govendor](https://github.com/kardianos/govendor) | 5004 | 98 | 2015/04/12 | 1 year ago | Go Package Manager. Go vendor tool that works with the standard vendor file. |
| [gopm](https://github.com/gpmgo/gopm) | 2492 | 85 | 2013/05/15 | 1 year ago | Go Package Manager. |
| [gom](https://github.com/mattn/gom) | 1390 | 36 | 2013/09/11 | 1 year ago | Go Manager - bundle for go. |
| [gpm](https://github.com/pote/gpm) | 1196 | 31 | 2013/09/05 | 3 years ago | Barebones dependency manager for Go. |
| [goop](https://github.com/petejkim/goop) | 776 | 36 | 2014/06/18 | 5 years ago | Simple dependency manager for Go (golang), inspired by Bundler. |
| [modgv](https://github.com/lucasepe/modgv) | 381 | 7 | 2020/09/12 | 9 months ago | Converts 'go mod graph' output into Graphviz's DOT language. |
| [nut](https://github.com/jingweno/nut) | 242 | 6 | 2015/01/23 | 6 years ago | Vendor Go dependencies. |
| [nut](https://github.com/owenthereal/nut) | 240 | 6 | 2015/01/23 | 6 years ago | Vendor Go dependencies. |
| [johnny-deps](https://github.com/VividCortex/johnny-deps) | 215 | 22 | 2013/07/19 | 6 months ago | Minimal dependency version using Git. |
| [gigo](https://github.com/LyricalSecurity/gigo) | 199 | 5 | 2015/05/01 | 2 years ago | PIP-like dependency tool for golang, with support for private repositories and hashes. |
| [mvn-golang](https://github.com/raydac/mvn-golang) | 129 | 11 | 2016/03/24 | 1 week ago | plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure. |
| [VenGO](https://github.com/DamnWidget/VenGO) | 120 | 9 | 2014/10/17 | 5 years ago | create and manage exportable isolated go virtual environments. |
| [gop](https://github.com/lunny/gop) | 49 | 7 | 2017/02/18 | 2 years ago | Build and manage your Go applications out of GOPATH. |

## Performance
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [jaeger](https://github.com/jaegertracing/jaeger) | 13807 | 344 | 2016/04/15 | 4 hours ago | A distributed tracing system. |
| [pixie](https://github.com/pixie-labs/pixie) | 1676 | 51 | 2020/02/27 | 3 days ago | No instrumentation tracing for Golang applications via eBPF. |
| [profile](https://github.com/pkg/profile) | 1501 | 40 | 2014/10/22 | 2 months ago | Simple profiling support package for Go. |
| [statsviz](https://github.com/arl/statsviz) | 1397 | 21 | 2020/08/14 | 2 months ago | Live visualization of your Go application runtime statistics. |
| [tracer](https://github.com/kamilsk/tracer) | 47 | 3 | 2019/06/22 | 4 months ago | Simple, lightweight tracing. |

## Query Language
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [graphql](https://github.com/graphql-go/graphql) | 7800 | 154 | 2015/07/19 | 1 month ago | Implementation of GraphQL for Go. |
| [graphql-go](https://github.com/graph-gophers/graphql-go) | 3799 | 90 | 2016/10/18 | 1 month ago | GraphQL server with a focus on ease of use. |
| [gojsonq](https://github.com/thedevsaddam/gojsonq) | 1699 | 34 | 2018/05/19 | 3 months ago | A simple Go package to Query over JSON Data. |
| [dasel](https://github.com/TomWright/dasel) | 943 | 6 | 2020/09/22 | 2 months ago | Query and update data structures using selectors from the command line. Comparable to jq/yq but supports JSON, YAML, TOML and XML with zero runtime dependencies. |
| [jsonql](https://github.com/elgs/jsonql) | 244 | 10 | 2015/12/29 | 7 months ago | JSON query expression library in Golang. |
| [rql](https://github.com/a8m/rql) | 213 | 10 | 2018/06/05 | 3 weeks ago | Resource Query Language for REST API. |
| [graphql](https://github.com/tmc/graphql) | 53 | 11 | 2015/04/18 | 4 years ago | graphql parser + utilities. |
| [jsonslice](https://github.com/bhmj/jsonslice) | 52 | 0 | 2018/05/02 | 9 months ago | Jsonpath queries with advanced filters. |
| [api-fu](https://github.com/ccbrown/api-fu) | 33 | 3 | 2019/07/30 | 1 month ago | Comprehensive GraphQL implementation. |
| [straf](https://github.com/SonicRoshan/straf) | 27 | 1 | 2019/08/16 | 1 year ago | Easily Convert Golang structs to GraphQL objects. |
| [rest-query-parser](https://github.com/timsolov/rest-query-parser) | 23 | 2 | 2020/02/10 | 1 week ago | Query Parser for REST API. Filtering, validations, both `AND`, `OR` operations are supported directly in the query. |
| [jsonpath](https://github.com/AsaiYusuke/jsonpath) | 5 | 1 | 2020/11/29 | 4 months ago | A query library for retrieving part of JSON based on JSONPath syntax. |
| [gws](https://github.com/Zaba505/gws) | 4 | 1 | 2020/06/08 | 10 months ago | Apollos' "GraphQL over Websocket" client and server implementation. |

## Resource Embedding
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [packr](https://github.com/gobuffalo/packr) | 3246 | 46 | 2017/03/15 | 3 days ago | The simple and easy way to embed static files into Go binaries. |
| [statik](https://github.com/rakyll/statik) | 3219 | 49 | 2014/02/04 | 8 months ago | Embeds static files into a Go executable. |
| [go.rice](https://github.com/GeertJohan/go.rice) | 2230 | 57 | 2013/10/23 | 4 months ago | go.rice is a Go package that makes working with resources such as HTML, JS, CSS, images, and templates very easy. |
| [vfsgen](https://github.com/shurcooL/vfsgen) | 931 | 20 | 2015/05/18 | 10 months ago | Generates a vfsdata.go file that statically implements the given virtual filesystem. |
| [esc](https://github.com/mjibson/esc) | 599 | 15 | 2014/01/26 | 1 year ago | Embeds files into Go programs and provides http.FileSystem interfaces to them. |
| [fileb0x](https://github.com/UnnoTed/fileb0x) | 585 | 17 | 2016/01/23 | 4 months ago | Simple tool to embed files in go with focus on "customization" and ease to use. |
| [go-resources](https://github.com/omeid/go-resources) | 172 | 7 | 2015/02/21 | 1 month ago | Unfancy resources embedding with Go. |
| [statics](https://github.com/go-playground/statics) | 62 | 3 | 2015/10/07 | 4 years ago | Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks. |
| [go-embed](https://github.com/pyros2097/go-embed) | 28 | 3 | 2015/12/06 | 6 months ago | Generates go code to embed resource files into your library or executable. |
| [templify](https://github.com/wlbr/templify) | 26 | 3 | 2016/05/22 | 1 year ago | Embed external template files into Go code to create single file binaries. |
| [mule](https://github.com/wlbr/mule) | 9 | 2 | 2020/01/17 | 11 months ago | Embed external resources like images, movies ... into Go source code to create single file binaries using `go generate`. Focussed on simplicity. |

## Science and Data Analysis
        
*Libraries for scientific computing and data analyzing.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gonum](https://github.com/gonum/gonum) | 5002 | 118 | 2017/03/25 | 1 week ago | Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more. |
| [stats](https://github.com/montanaflynn/stats) | 2017 | 52 | 2014/12/16 | 2 months ago | Statistics package with common functions missing from the Golang standard library. |
| [plot](https://github.com/gonum/plot) | 1930 | 60 | 2013/07/23 | 1 week ago | gonum/plot provides an API for building and drawing plots in Go. |
| [gosl](https://github.com/cpmech/gosl) | 1590 | 72 | 2015/02/09 | 3 weeks ago | Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more. |
| [streamtools](https://github.com/nytlabs/streamtools) | 1311 | 72 | 2013/07/05 | 6 years ago | general purpose, graphical tool for dealing with streams of data. |
| [go-dsp](https://github.com/mjibson/go-dsp) | 739 | 29 | 2011/11/02 | 3 years ago | Digital Signal Processing for Go. |
| [chart](https://github.com/vdobler/chart) | 679 | 45 | 2011/06/27 | 1 month ago | Simple Chart Plotting library for Go. Supports many graphs types. |
| [goraph](https://github.com/gyuho/goraph) | 642 | 40 | 2014/02/27 | 3 years ago | Pure Go graph theory library(data structure, algorith visualization). |
| [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) | 568 | 26 | 2018/10/01 | 2 months ago | Dataframes for machine-learning and statistics (similar to pandas). |
| [graph](https://github.com/yourbasic/graph) | 457 | 22 | 2017/04/27 | 1 month ago | Library of basic graph algorithms. |
| [orb](https://github.com/paulmach/orb) | 402 | 22 | 2016/03/28 | 1 month ago | 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support. |
| [ewma](https://github.com/VividCortex/ewma) | 336 | 25 | 2013/07/05 | 2 weeks ago | Exponentially-weighted moving averages. |
| [calendarheatmap](https://github.com/nikolaydubina/calendarheatmap) | 295 | 9 | 2020/07/01 | 6 days ago | Calendar heatmap in plain Go inspired by Github contribution activity. |
| [gohistogram](https://github.com/VividCortex/gohistogram) | 153 | 18 | 2013/07/02 | 6 months ago | Approximate histograms for data streams. |
| [TextRank](https://github.com/DavidBelicza/TextRank) | 141 | 8 | 2018/01/09 | 3 days ago | TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support. |
| [sparse](https://github.com/james-bowman/sparse) | 118 | 9 | 2017/05/16 | 3 months ago | Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries. |
| [pagerank](https://github.com/alixaxel/pagerank) | 70 | 8 | 2015/08/06 | 3 weeks ago | Weighted PageRank algorithm implemented in Go. |
| [geom](https://github.com/skelterjohn/geom) | 47 | 5 | 2011/06/07 | 3 years ago | 2D geometry for golang. |
| [evaler](https://github.com/soniah/evaler) | 44 | 5 | 2012/09/04 | 3 years ago | Simple floating point arithmetic expression evaluator. |
| [goent](https://github.com/kzahedi/goent) | 25 | 1 | 2017/08/08 | 2 years ago | GO Implementation of Entropy Measures. |
| [triangolatte](https://github.com/tchayen/triangolatte) | 24 | 2 | 2018/07/18 | 1 month ago | 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs. |
| [decimal](https://github.com/db47h/decimal) | 22 | 3 | 2020/05/27 | 1 year ago | Package decimal implements arbitrary-precision decimal floating-point arithmetic. |
| [piecewiselinear](https://github.com/sgreben/piecewiselinear) | 18 | 4 | 2018/10/21 | 7 months ago | Tiny linear interpolation library. |
| [GoStats](https://github.com/OGFris/GoStats) | 15 | 3 | 2018/07/22 | 2 years ago | GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions. |
| [PiHex](https://github.com/claygod/PiHex) | 14 | 3 | 2016/07/22 | 9 months ago | Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi. |
| [ode](https://github.com/ChristopherRabotin/ode) | 13 | 4 | 2016/11/11 | 4 years ago | Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions. |
| [assocentity](https://github.com/ndabAP/assocentity) | 6 | 2 | 2018/12/21 | 8 months ago | Package assocentity returns the average distance from words to a given entity. |
| [go-gt](https://github.com/ThePaw/go-gt) | 5 | 0 | 2015/09/14 | 5 years ago | Graph theory algorithms written in "Go" language. |
| [rootfinding](https://github.com/khezen/rootfinding) | 5 | 3 | 2018/10/30 | 1 year ago | root-finding algorithms library for finding roots of quadratic functions. |
| [bradleyterry](https://github.com/seanhagen/bradleyterry) | 4 | 2 | 2019/04/30 | 2 years ago | Provides a Bradley-Terry Model for pairwise comparisons. |

## Security
        
*Libraries that are used to help make your application more secure.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [lego](https://github.com/go-acme/lego) | 4695 | 99 | 2015/06/08 | 9 hours ago | Pure Go ACME client library and CLI tool (for use with Let's Encrypt). |
| [cameradar](https://github.com/Ullaakut/cameradar) | 2614 | 126 | 2016/05/20 | 2 months ago | Tool and library to remotely hack RTSP streams from surveillance cameras. |
| [memguard](https://github.com/awnumar/memguard) | 1961 | 47 | 2017/04/22 | 3 months ago | A pure Go library for handling sensitive values in memory. |
| [acmetool](https://github.com/hlandau/acmetool) | 1860 | 66 | 2015/11/15 | 3 months ago | ACME (Let's Encrypt) client tool with automatic renewal. |
| [secure](https://github.com/unrolled/secure) | 1775 | 37 | 2014/05/20 | 2 months ago | HTTP middleware for Go that facilitates some quick security wins. |
| [themis](https://github.com/cossacklabs/themis) | 1313 | 41 | 2015/05/06 | 5 hours ago | high-level cryptographic library for solving typical data security tasks (secure data storage, secure messaging, zero-knowledge proof authentication), available for 14 languages, best fit for multi-platform apps. |
| [acra](https://github.com/cossacklabs/acra) | 770 | 39 | 2016/11/14 | 2 months ago | Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system. |
| [nacl](https://github.com/kevinburke/nacl) | 507 | 13 | 2017/07/20 | 3 months ago | Go implementation of the NaCL set of API's. |
| [firewalld-rest](https://github.com/prashantgupta24/firewalld-rest) | 305 | 9 | 2020/06/12 | 10 months ago | A rest application to dynamically update firewalld rules on a linux server. |
| [badactor](https://github.com/jaredfolkins/badactor) | 296 | 8 | 2014/12/12 | 1 year ago | In-memory, application-driven jailer built in the spirit of fail2ban. |
| [ssh-vault](https://github.com/ssh-vault/ssh-vault) | 295 | 10 | 2016/09/29 | 8 hours ago | encrypt/decrypt using ssh keys. |
| [go-password-validator](https://github.com/wagslane/go-password-validator) | 280 | 9 | 2020/10/14 | 3 months ago | Password validator based on raw cryptographic entropy values. |
| [optimus-go](https://github.com/pjebs/optimus-go) | 278 | 5 | 2015/05/05 | 1 year ago | ID hashing and Obfuscation using Knuth's Algorithm. |
| [go-password-validator](https://github.com/lane-c-wagner/go-password-validator) | 259 | 8 | 2020/10/14 | 6 months ago | Password validator based on raw cryptographic entropy values. |
| [passlib](https://github.com/hlandau/passlib) | 243 | 11 | 2014/12/21 | 3 months ago | Futureproof password hashing library. |
| [go-yara](https://github.com/hillu/go-yara) | 215 | 19 | 2015/01/25 | 1 month ago | Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)". |
| [simple-scrypt](https://github.com/elithrar/simple-scrypt) | 171 | 7 | 2015/04/14 | 3 months ago | Scrypt package with a simple, obvious API and automatic cost calibration built-in. |
| [argon2pw](https://github.com/raja/argon2pw) | 86 | 4 | 2018/03/13 | 2 years ago | Argon2 password hash generation with constant-time password comparison. |
| [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) | 43 | 2 | 2017/10/19 | 7 months ago | A probably paranoid package for securely hashing and encrypting passwords. |
| [certificates](https://github.com/mvmaasakkers/certificates) | 21 | 0 | 2019/03/04 | 7 months ago | An opinionated tool for generating tls certificates. |
| [go-generate-password](https://github.com/m1/go-generate-password) | 19 | 2 | 2019/11/14 | 8 months ago | Password generator that can be used on the cli or as a library. |
| [secureio](https://github.com/xaionaro-go/secureio) | 17 | 2 | 2018/12/25 | 1 year ago | An keyexchanging+authenticating+encrypting wrapper and multiplexer for `io.ReadWriteCloser` based on XChaCha20-poly1305, ECDH and ED25519. |
| [goArgonPass](https://github.com/dwin/goArgonPass) | 14 | 3 | 2018/05/30 | 7 months ago | Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations. |
| [argon2-hashing](https://github.com/andskur/argon2-hashing) | 12 | 2 | 2019/01/02 | 1 year ago | light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package. |
| [sslmgr](https://github.com/adrianosela/sslmgr) | 11 | 2 | 2019/04/02 | 1 year ago | SSL certificates made easy with a high level wrapper around acme/autocert. |

## Serialization
        
*Libraries and tools for binary serialization.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go](https://github.com/json-iterator/go) | 9503 | 233 | 2016/11/30 | 3 weeks ago | High-performance 100% compatible drop-in replacement of "encoding/json". |
| [protobuf](https://github.com/golang/protobuf) | 7754 | 213 | 2014/11/23 | 3 months ago | Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers. |
| [protobuf](https://github.com/gogo/protobuf) | 4700 | 98 | 2014/12/03 | 1 week ago | Protocol Buffers for Go with Gadgets. |
| [mapstructure](https://github.com/mitchellh/mapstructure) | 4660 | 65 | 2013/05/20 | 3 days ago | Go library for decoding generic map values into native Go structures. |
| [go](https://github.com/ugorji/go) | 1554 | 52 | 2013/05/30 | 1 month ago | High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support. |
| [colfer](https://github.com/pascaldekloe/colfer) | 610 | 33 | 2015/09/05 | 1 day ago | Code generation for the Colfer binary format. |
| [csvutil](https://github.com/jszwec/csvutil) | 542 | 7 | 2017/10/30 | 4 months ago | High Performance, idiomatic CSV record encoding and decoding to native Go structures. |
| [cbor](https://github.com/fxamacker/cbor) | 289 | 6 | 2019/05/15 | 1 week ago | Small, safe, and easy CBOR encoding and decoding library. |
| [go-capnproto](https://github.com/glycerine/go-capnproto) | 279 | 11 | 2013/11/07 | 1 year ago | Cap'n Proto library and parser for go. |
| [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) | 149 | 10 | 2012/12/23 | 2 years ago | GoLang library for working with PHP session format and PHP Serialize/Unserialize functions. |
| [structomap](https://github.com/danhper/structomap) | 123 | 7 | 2015/05/13 | 2 years ago | Library to easily and dynamically generate maps from static structures. |
| [bambam](https://github.com/glycerine/bambam) | 62 | 4 | 2014/09/17 | 4 years ago | generator for Cap'n Proto schemas from go. |
| [asn1](https://github.com/Logicalis/asn1) | 47 | 9 | 2016/02/29 | 2 years ago | Asn.1 BER and DER encoding library for golang. |
| [binstruct](https://github.com/ghostiam/binstruct) | 32 | 1 | 2018/10/23 | 1 year ago | Golang binary decoder for mapping data into the structure. |
| [elastic](https://github.com/epiclabs-io/elastic) | 15 | 1 | 2020/02/25 | 1 month ago | Convert slices, maps or any other unknown value across different types at run-time, no matter what. |
| [fwencoder](https://github.com/o1egl/fwencoder) | 14 | 1 | 2017/12/25 | 1 year ago | Fixed width file parser (encoding and decoding library) for Go. |
| [pletter](https://github.com/vimeda/pletter) | 14 | 8 | 2019/07/09 | 1 week ago | A standard way to wrap a proto message for message brokers. |
| [bel](https://github.com/csweichel/bel) | 12 | 2 | 2019/02/20 | 11 months ago | Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC. |
| [bel](https://github.com/32leaves/bel) | 8 | 1 | 2019/02/20 | 2 years ago | Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC. |
| [fixedwidth](https://github.com/huydang284/fixedwidth) | 5 | 1 | 2019/08/11 | 1 year ago | Fixed-width text formatting (UTF-8 supported). |
| [go-lctree](https://github.com/sbourlon/go-lctree) | 2 | 1 | 2020/05/04 | 1 year ago | Provides a CLI and primitives to serialize and deserialize [LeetCode binary trees](https://support.leetcode.com/hc/en-us/articles/360011883654-What-does-1-null-2-3-mean-in-binary-tree-representation). |
| [unitpacking](https://github.com/recolude/unitpacking) | 2 | 2 | 2021/01/17 | 2 months ago | Library to pack unit vectors into as fewest bytes as possible. |

## Server Applications
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [etcd](https://github.com/etcd-io/etcd) | 36523 | 1372 | 2013/07/06 | 3 hours ago | Highly-available key value store for shared configuration and service discovery. |
| [caddy](https://github.com/caddyserver/caddy) | 33937 | 769 | 2015/01/13 | 1 hour ago | Caddy is an alternative, HTTP/2 web server that's easy to configure and use. |
| [minio](https://github.com/minio/minio) | 28423 | 581 | 2015/01/14 | 3 hours ago | Minio is a distributed object storage server. |
| [roadrunner](https://github.com/spiral/roadrunner) | 5724 | 148 | 2017/12/26 | 5 hours ago | High-performance PHP application server, load-balancer and process manager. |
| [devd](https://github.com/cortesi/devd) | 3137 | 69 | 2015/09/27 | 4 months ago | Local webserver for developers. |
| [sftpgo](https://github.com/drakkan/sftpgo) | 2752 | 61 | 2019/07/20 | 1 day ago | Fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. It can serve local filesystem and Cloud Storage backends such as S3 and Google Cloud Storage. |
| [algernon](https://github.com/xyproto/algernon) | 1825 | 51 | 2015/03/10 | 1 week ago | HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber. |
| [flagr](https://github.com/checkr/flagr) | 1617 | 76 | 2017/10/03 | 5 days ago | Flagr is an open-source feature flagging and A/B testing service. |
| [fider](https://github.com/getfider/fider) | 1602 | 34 | 2017/01/17 | 10 hours ago | Fider is an open platform to collect and organize customer feedback. |
| [flipt](https://github.com/markphelps/flipt) | 1518 | 15 | 2016/11/05 | 14 hours ago | A self contained feature flag solution written in Go and Vue. |
| [trickster](https://github.com/trickstercache/trickster) | 1448 | 44 | 2018/03/29 | 1 month ago | HTTP reverse proxy cache and time series accelerator. |
| [discovery](https://github.com/bilibili/discovery) | 1432 | 60 | 2018/04/20 | 2 months ago | A registry for resilient mid-tier load balancing and failover. |
| [trickster](https://github.com/tricksterproxy/trickster) | 1403 | 41 | 2018/03/29 | 1 month ago | HTTP reverse proxy cache and time series accelerator. |
| [jackal](https://github.com/ortuman/jackal) | 1099 | 41 | 2017/11/13 | 3 weeks ago | An XMPP server written in Go. |
| [trickster](https://github.com/Comcast/trickster) | 1053 | 35 | 2018/03/29 | 1 year ago | HTTP reverse proxy cache and time series accelerator. |
| [go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) | 339 | 1 | 2020/12/11 | 1 week ago | A feature flag solution, with only a YAML file in the backend (S3, GitHub, HTTP, local file ...), no server to install, just add a file in a central system and refer to it. |
| [dudeldu](https://github.com/krotik/dudeldu) | 129 | 3 | 2016/09/07 | 1 year ago | A simple SHOUTcast server. |
| [lets-proxy2](https://github.com/rekby/lets-proxy2) | 56 | 4 | 2019/04/12 | 1 month ago | Reverse proxy for handle https with issue certificates in fly from lets-encrypt. |
| [psql-streamer](https://github.com/blind-oracle/psql-streamer) | 28 | 4 | 2019/04/28 | 1 year ago | Stream database events from PostgreSQL to Kafka. |
| [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) | 22 | 1 | 2018/10/23 | 9 months ago | Nginx log parser and exporter to Prometheus. |
| [simple-jwt-provider](https://github.com/leberKleber/simple-jwt-provider) | 18 | 2 | 2019/12/18 | 1 month ago | Simple and lightweight provider which exhibits JWTs, supports login, password-reset (via mail) and user management. |
| [protoxy](https://github.com/camgraff/protoxy) | 16 | 2 | 2020/09/03 | 8 months ago | A proxy server that converts JSON request bodies to Protocol Buffers. |
| [go-proxy-cache](https://github.com/fabiocicerchia/go-proxy-cache) | 10 | 1 | 2020/11/12 | 3 weeks ago | Simple Reverse Proxy with Caching, written in Go, using Redis. |
| [riemann-relay](https://github.com/blind-oracle/riemann-relay) | 0 | 1 | 2019/04/23 | 1 year ago | Relay to load-balance Riemann events and/or convert them to Carbon. |

## Stream Processing
        
*Libraries and tools for stream processing and reactive programming.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-streams](https://github.com/reugn/go-streams) | 676 | 19 | 2019/04/30 | 2 weeks ago | Go stream processing library. |
| [machine](https://github.com/whitaker-io/machine) | 87 | 4 | 2020/10/13 | 1 week ago | Go library for writing and generating stream workers with built in metrics and traceability. |
| [stream](https://github.com/youthlin/stream) | 37 | 2 | 2020/11/12 | 7 months ago | Go Stream, like Java 8 Stream: Filter/Map/FlatMap/Peek/Sorted/ForEach/Reduce... |

## Template Engines
        
*Libraries and tools for templating and lexing.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gofpdf](https://github.com/jung-kurt/gofpdf) | 3823 | 103 | 2015/03/13 | 1 year ago | PDF document generator with high level support for text, drawing and images. |
| [sprig](https://github.com/Masterminds/sprig) | 2412 | 31 | 2013/11/22 | 5 days ago | Useful template functions for Go templates. |
| [quicktemplate](https://github.com/valyala/quicktemplate) | 2137 | 59 | 2016/03/06 | 3 months ago | Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it. |
| [pongo2](https://github.com/flosch/pongo2) | 1996 | 60 | 2013/08/23 | 1 week ago | Django-like template-engine for Go. |
| [hero](https://github.com/shiyanhui/hero) | 1462 | 43 | 2017/01/15 | 1 year ago | Hero is a handy, fast and powerful go template engine. |
| [mustache](https://github.com/hoisie/mustache) | 1013 | 35 | 2009/12/30 | 1 month ago | Go implementation of the Mustache template language. |
| [amber](https://github.com/eknkc/amber) | 874 | 20 | 2012/10/31 | 9 months ago | Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade. |
| [ace](https://github.com/yosssi/ace) | 801 | 23 | 2014/07/13 | 3 years ago | Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold. |
| [jet](https://github.com/CloudyKit/jet) | 798 | 23 | 2016/03/31 | 4 months ago | Jet template engine. |
| [gorazor](https://github.com/sipin/gorazor) | 782 | 58 | 2014/05/01 | 7 months ago | Razor view engine for Golang. |
| [fasttemplate](https://github.com/valyala/fasttemplate) | 509 | 20 | 2015/08/19 | 6 months ago | Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/). |
| [ego](https://github.com/benbjohnson/ego) | 491 | 17 | 2014/02/23 | 4 months ago | Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled. |
| [raymond](https://github.com/aymerick/raymond) | 432 | 11 | 2015/04/22 | 3 weeks ago | Complete handlebars implementation in Go. |
| [maroto](https://github.com/johnfercher/maroto) | 408 | 10 | 2019/05/20 | 1 week ago | A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple. |
| [goview](https://github.com/foolin/goview) | 237 | 5 | 2019/04/14 | 6 months ago | Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application. |
| [soy](https://github.com/robfig/soy) | 155 | 12 | 2013/12/15 | 3 days ago | Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/). |
| [liquid](https://github.com/osteele/liquid) | 127 | 6 | 2017/06/26 | 6 days ago | Go implementation of Shopify Liquid templates. |
| [kasia.go](https://github.com/ziutek/kasia.go) | 72 | 2 | 2010/12/07 | 5 years ago | Templating system for HTML and other text documents - go implementation. |
| [velvet](https://github.com/gobuffalo/velvet) | 72 | 6 | 2016/12/29 | 4 years ago | Complete handlebars implementation in Go. |
| [extemplate](https://github.com/dannyvankooten/extemplate) | 38 | 4 | 2018/08/10 | 3 weeks ago | Tiny wrapper around html/template to allow for easy file-based template inheritance. |
| [gospin](https://github.com/m1/gospin) | 27 | 3 | 2019/02/22 | 2 months ago | Article spinning and spintax/spinning syntax engine, useful for A/B, testing pieces of text/articles and creating more natural conversations. |
| [damsel](https://github.com/dskinner/damsel) | 24 | 4 | 2012/05/02 | 5 years ago | Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others. |

## Testing
        
*Libraries for testing codebases and generating test data.*

### Testing Frameworks
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [testify](https://github.com/stretchr/testify) | 13727 | 178 | 2012/10/16 | 5 hours ago | Sacred extension to the standard go testing package. |
| [go-cmp](https://github.com/google/go-cmp) | 2373 | 27 | 2017/07/07 | 1 month ago | Package for comparing Go values in tests. |
| [httpexpect](https://github.com/gavv/httpexpect) | 1714 | 35 | 2016/04/29 | 2 weeks ago | Concise, declarative, and easy to use end-to-end HTTP and REST API testing. |
| [godog](https://github.com/cucumber/godog) | 1386 | 95 | 2015/06/10 | 3 days ago | Cucumber or Behat like BDD framework for Go. |
| [godog](https://github.com/DATA-DOG/godog) | 895 | 30 | 2015/06/10 | 1 year ago | Cucumber or Behat like BDD framework for Go. |
| [goblin](https://github.com/franela/goblin) | 803 | 16 | 2013/09/19 | 1 week ago | Mocha like testing framework fo Go. |
| [go-vcr](https://github.com/dnaeon/go-vcr) | 742 | 11 | 2015/12/14 | 2 weeks ago | Record and replay your HTTP interactions for fast, deterministic and accurate tests. |
| [baloo](https://github.com/h2non/baloo) | 712 | 11 | 2016/05/29 | 2 years ago | Expressive and versatile end-to-end HTTP API testing made easy. |
| [testfixtures](https://github.com/go-testfixtures/testfixtures) | 679 | 6 | 2016/04/05 | 1 week ago | A helper for Rails' like test fixtures to test database applications. |
| [gnomock](https://github.com/orlangure/gnomock) | 490 | 10 | 2020/01/31 | 5 hours ago | integration testing with real dependencies (database, cache, even Kubernetes or AWS) running in Docker, without mocks. |
| [go-mutesting](https://github.com/zimmski/go-mutesting) | 404 | 8 | 2014/12/26 | 2 weeks ago | Mutation testing for Go source code. |
| [goc](https://github.com/qiniu/goc) | 391 | 18 | 2020/05/07 | 4 hours ago | Goc is a comprehensive coverage testing system for The Go Programming Language. |
| [gofight](https://github.com/appleboy/gofight) | 378 | 13 | 2016/03/29 | 2 weeks ago | API Handler Testing for Golang Router framework. |
| [frisby](https://github.com/hofstadter-io/frisby) | 264 | 9 | 2015/09/15 | 1 year ago | REST API testing framework. |
| [embedded-postgres](https://github.com/fergusstrange/embedded-postgres) | 263 | 3 | 2019/11/16 | 4 weeks ago | Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test. |
| [frisby](https://github.com/verdverm/frisby) | 257 | 8 | 2015/09/15 | 1 year ago | REST API testing framework. |
| [gotest.tools](https://github.com/gotestyourself/gotest.tools) | 246 | 7 | 2017/08/08 | 1 month ago | A collection of packages to augment the go testing package and support common patterns. |
| [go-carpet](https://github.com/msoap/go-carpet) | 214 | 4 | 2016/02/28 | 2 months ago | Tool for viewing test coverage in terminal. |
| [charlatan](https://github.com/percolate/charlatan) | 194 | 48 | 2017/10/06 | 1 year ago | Tool to generate fake interface implementations for tests. |
| [endly](https://github.com/viant/endly) | 188 | 16 | 2017/08/28 | 3 months ago | Declarative end to end functional testing. |
| [commander](https://github.com/commander-cli/commander) | 186 | 7 | 2019/02/22 | 1 week ago | Tool for testing cli applications on windows, linux and osx. |
| [go-testdeep](https://github.com/maxatome/go-testdeep) | 183 | 2 | 2018/05/26 | 20 hours ago | Extremely flexible golang deep comparison, extends the go testing package. |
| [cupaloy](https://github.com/bradleyjkemp/cupaloy) | 165 | 2 | 2017/08/07 | 2 months ago | Simple snapshot testing addon for your test framework. |
| [commander](https://github.com/SimonBaeumer/commander) | 154 | 9 | 2019/02/22 | 1 year ago | Tool for testing cli applications on windows, linux and osx. |
| [dbcleaner](https://github.com/khaiql/dbcleaner) | 131 | 2 | 2017/01/17 | 1 year ago | Clean database for testing purpose, inspired by `database_cleaner` in Ruby. |
| [gospec](https://github.com/luontola/gospec) | 114 | 4 | 2009/11/24 | 7 years ago | BDD-style testing framework for the Go programming language. |
| [wstest](https://github.com/posener/wstest) | 84 | 2 | 2017/03/31 | 6 months ago | Websocket client for unit-testing a websocket http.Handler. |
| [gocrest](https://github.com/corbym/gocrest) | 81 | 3 | 2017/12/23 | 6 months ago | Composable hamcrest-like matchers for Go assertions. |
| [testcase](https://github.com/adamluzsi/testcase) | 69 | 3 | 2019/04/22 | 4 days ago | Idiomatic testing framework for Behavior Driven Development. |
| [jsonassert](https://github.com/kinbiko/jsonassert) | 67 | 0 | 2018/10/26 | 2 months ago | Package for verifying that your JSON payloads are serialized correctly. |
| [gospecify](https://github.com/stesla/gospecify) | 53 | 6 | 2009/11/20 | 9 years ago | This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec. |
| [restit](https://github.com/go-restit/restit) | 53 | 7 | 2014/06/25 | 1 year ago | Go micro framework to help writing RESTful API integration test. |
| [gomatch](https://github.com/jfilipczyk/gomatch) | 39 | 2 | 2019/01/27 | 5 months ago | library created for testing JSON against patterns. |
| [covergates](https://github.com/covergates/covergates) | 39 | 4 | 2020/05/29 | 6 months ago | Self-hosted code coverage report review and management service. |
| [dsunit](https://github.com/viant/dsunit) | 38 | 10 | 2016/06/13 | 1 year ago | Datastore testing for SQL, NoSQL, structured files. |
| [go-hit](https://github.com/Eun/go-hit) | 35 | 1 | 2019/06/04 | 1 month ago | Hit is an http integration test framework written in golang. |
| [assert](https://github.com/go-playground/assert) | 34 | 2 | 2015/07/20 | 8 months ago | Basic Assertion Library used along side native go testing, with building blocks for custom assertions. |
| [hamcrest](https://github.com/rdrdr/hamcrest) | 26 | 3 | 2010/12/22 | 6 months ago | fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results. |
| [flute](https://github.com/suzuki-shunsuke/flute) | 16 | 0 | 2019/07/06 | 3 weeks ago | HTTP client testing framework. |
| [schema](https://github.com/jgroeneveld/schema) | 15 | 1 | 2015/08/13 | 1 year ago | Quick and easy expression matching for JSON schemas used in requests and responses. |
| [badio](https://github.com/cavaliercoder/badio) | 10 | 0 | 2016/02/11 | 5 years ago | Extensions to Go's `testing/iotest` package. |
| [biff](https://github.com/fulldump/biff) | 10 | 1 | 2018/03/28 | 10 months ago | Bifurcation testing framework, BDD compatible. |
| [gogiven](https://github.com/corbym/gogiven) | 10 | 4 | 2017/12/31 | 3 years ago | YATSPEC-like BDD testing framework for Go. |
| [gosuite](https://github.com/pavlo/gosuite) | 10 | 1 | 2016/10/15 | 4 years ago | Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests. |
| [testsql](https://github.com/zhulongcheng/testsql) | 10 | 2 | 2018/09/22 | 1 year ago | Generate test data from SQL files before testing and clear it after finished. |
| [stop-and-go](https://github.com/elgohr/stop-and-go) | 6 | 0 | 2020/11/06 | 5 months ago | Testing helper for concurrency. |
| [trial](https://github.com/jgroeneveld/trial) | 5 | 0 | 2015/06/18 | 1 year ago | Quick and easy extendable assertions without introducing much boilerplate. |
| [tt](https://github.com/vcaesar/tt) | 5 | 1 | 2018/04/03 | 1 month ago | Simple and colorful test tools. |

### Mock
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [chromedp](https://github.com/chromedp/chromedp) | 6465 | 153 | 2017/01/24 | 1 week ago | a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol. |
| [mock](https://github.com/golang/mock) | 5834 | 78 | 2015/06/12 | 2 days ago | Mocking framework for the Go programming language. |
| [go-fuzz](https://github.com/dvyukov/go-fuzz) | 4081 | 91 | 2015/04/15 | 1 month ago | Randomized testing system. |
| [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) | 3638 | 36 | 2014/02/07 | 1 month ago | Mock SQL driver for testing database interactions. |
| [selenoid](https://github.com/aerokube/selenoid) | 1940 | 99 | 2016/08/22 | 2 weeks ago | alternative Selenium hub server that launches browsers within containers. |
| [hoverfly](https://github.com/SpectoLabs/hoverfly) | 1759 | 63 | 2015/11/30 | 2 months ago | HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI. |
| [rod](https://github.com/go-rod/rod) | 1645 | 33 | 2020/01/21 | 4 days ago | A Devtools driver to make web automation and scraping easy. |
| [gock](https://github.com/h2non/gock) | 1421 | 19 | 2016/03/02 | 6 days ago | Versatile HTTP mocking made easy. |
| [httpmock](https://github.com/jarcoal/httpmock) | 1102 | 9 | 2014/02/24 | 4 months ago | Easy mocking of HTTP responses from external resources. |
| [gofuzz](https://github.com/google/gofuzz) | 1100 | 28 | 2014/07/31 | 1 month ago | Library for populating go objects with random values. |
| [cdp](https://github.com/mafredri/cdp) | 561 | 18 | 2017/03/12 | 1 month ago | Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it. |
| [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) | 544 | 9 | 2014/05/21 | 4 days ago | Tool for generating self-contained mock objects. |
| [playwright-go](https://github.com/mxschmitt/playwright-go) | 422 | 14 | 2020/08/16 | 1 month ago | browser automation library to control Chromium, Firefox and WebKit with a single API. |
| [go-txdb](https://github.com/DATA-DOG/go-txdb) | 368 | 7 | 2015/07/08 | 2 months ago | Single transaction based database driver mainly for testing purposes. |
| [minimock](https://github.com/gojuno/minimock) | 357 | 11 | 2016/08/03 | 3 weeks ago | Mock generator for Go interfaces. |
| [ggr](https://github.com/aerokube/ggr) | 273 | 26 | 2016/06/16 | 1 month ago | a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs. |
| [rod](https://github.com/ysmood/rod) | 273 | 8 | 2020/01/21 | 1 year ago | A chrome devtools controller that is easy and safe to use. |
| [tavor](https://github.com/zimmski/tavor) | 232 | 12 | 2014/05/18 | 2 years ago | Generic fuzzing and delta-debugging framework. |
| [govcr](https://github.com/seborama/govcr) | 98 | 2 | 2016/07/10 | 1 year ago | HTTP mock for Golang: record and replay HTTP interactions for offline testing. |
| [timex](https://github.com/cabify/timex) | 55 | 79 | 2020/01/02 | 11 months ago | A test-friendly replacement for the native `time` package. |
| [mockhttp](https://github.com/tv42/mockhttp) | 22 | 2 | 2011/06/11 | 6 years ago | Mock object for Go http.ResponseWriter. |
| [go-localstack](https://github.com/elgohr/go-localstack) | 12 | 0 | 2020/03/18 | 2 days ago | Tool for using localstack in AWS testing. |
| [mockit](https://github.com/pasdam/mockit) | 8 | 1 | 2020/01/01 | 2 weeks ago | Allows functions and method easy mocking, without defining new types; it's similar to Mockito for Java. |

### Fail injection
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [failpoint](https://github.com/pingcap/failpoint) | 594 | 90 | 2019/04/02 | 1 week ago | An implementation of [failpoints](http://www.freebsd.org/cgi/man.cgi?query=fail) for Golang. |

## Text Processing
        
*Libraries for parsing and manipulating texts.*

### Specific Formats
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [colly](https://github.com/gocolly/colly) | 14283 | 321 | 2017/09/29 | 1 week ago | Fast and Elegant Scraping Framework for Gophers. |
| [goquery](https://github.com/PuerkitoBio/goquery) | 10371 | 264 | 2012/08/29 | 1 day ago | GoQuery brings a syntax and a set of features similar to jQuery to the Go language. |
| [blackfriday](https://github.com/russross/blackfriday) | 4748 | 92 | 2011/05/27 | 1 week ago | Markdown processor in Go. |
| [sh](https://github.com/mvdan/sh) | 3850 | 54 | 2016/01/16 | 2 weeks ago | Shell parser and formatter. |
| [toml](https://github.com/BurntSushi/toml) | 3513 | 86 | 2013/02/26 | 4 days ago | TOML configuration format (encoder/decoder with reflection). |
| [go-humanize](https://github.com/dustin/go-humanize) | 2737 | 34 | 2012/01/13 | 6 days ago | Formatters for time, numbers, and memory size to human readable format. |
| [bluemonday](https://github.com/microcosm-cc/bluemonday) | 1966 | 27 | 2013/11/20 | 3 days ago | HTML Sanitizer. |
| [gofeed](https://github.com/mmcdole/gofeed) | 1668 | 44 | 2016/01/23 | 3 weeks ago | Parse RSS and Atom feeds in Go. |
| [inject](https://github.com/facebookarchive/inject) | 1333 | 46 | 2013/10/21 | 2 years ago | Package inject provides a reflect based injector. |
| [go-toml](https://github.com/pelletier/go-toml) | 1054 | 33 | 2013/02/24 | 11 hours ago | Go library for the TOML format with query support and handy cli tools. |
| [commonregex](https://github.com/mingrammer/commonregex) | 777 | 21 | 2017/03/23 | 1 year ago | A collection of common regular expressions for Go. |
| [slug](https://github.com/gosimple/slug) | 654 | 13 | 2014/03/31 | 4 months ago | URL-friendly slugify with multiple languages support. |
| [mxj](https://github.com/clbanning/mxj) | 474 | 26 | 2014/02/03 | 4 months ago | Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. |
| [dataflowkit](https://github.com/slotix/dataflowkit) | 465 | 22 | 2017/02/09 | 1 year ago | Web scraping Framework to turn websites into structured data. |
| [gographviz](https://github.com/awalterschulze/gographviz) | 437 | 12 | 2015/03/14 | 2 months ago | Parses the Graphviz DOT language. |
| [htmlquery](https://github.com/antchfx/htmlquery) | 379 | 12 | 2017/12/05 | 1 month ago | An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression. |
| [go-runewidth](https://github.com/mattn/go-runewidth) | 371 | 12 | 2013/06/21 | 1 month ago | Functions to get fixed width of the character or string. |
| [omniparser](https://github.com/jf-tech/omniparser) | 358 | 9 | 2020/08/16 | 5 days ago | A versatile ETL library that parses text input (CSV/txt/JSON/XML/EDI/X12/EDIFACT/etc) in streaming fashion and transforms data into JSON output using data-driven schema. |
| [gotext](https://github.com/leonelquinteros/gotext) | 301 | 6 | 2016/06/19 | 2 months ago | GNU gettext utilities for Go. |
| [goq](https://github.com/andrewstuart/goq) | 199 | 7 | 2017/02/20 | 2 years ago | Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery). |
| [goribot](https://github.com/zhshch2002/goribot) | 196 | 11 | 2019/09/08 | 11 months ago | A simple golang spider/scraping framework,build a spider in 3 lines. |
| [html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) | 185 | 6 | 2018/05/15 | 2 hours ago | Convert HTML to Markdown. Even works with entire websites and can be extended through rules. |
| [go-nmea](https://github.com/adrianmo/go-nmea) | 152 | 7 | 2015/07/22 | 3 weeks ago | NMEA parser library for the Go language. |
| [sdp](https://github.com/gortc/sdp) | 111 | 8 | 2016/05/13 | 1 year ago | SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)]. |
| [go-zero-width](https://github.com/trubitsyn/go-zero-width) | 95 | 1 | 2018/06/18 | 11 months ago | Zero-width character detection and removal for Go. |
| [podcast](https://github.com/eduncan911/podcast) | 94 | 5 | 2017/02/02 | 8 months ago | iTunes Compliant and RSS 2. |
| [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) | 86 | 10 | 2016/07/05 | 1 month ago | Editorconfig file parser and manipulator for Go. |
| [align](https://github.com/Guitarbum722/align) | 69 | 5 | 2017/04/29 | 5 months ago | A general purpose application that aligns text. |
| [go-slugify](https://github.com/mozillazg/go-slugify) | 67 | 2 | 2016/07/16 | 1 year ago | Make pretty slug with multiple languages support. |
| [genex](https://github.com/alixaxel/genex) | 60 | 3 | 2015/03/09 | 1 year ago | Count and expand Regular Expressions into all matching Strings. |
| [go-vcard](https://github.com/emersion/go-vcard) | 60 | 4 | 2017/03/21 | 1 month ago | Parse and format vCard. |
| [goregen](https://github.com/zach-klippenstein/goregen) | 57 | 2 | 2014/12/27 | 9 hours ago | Library for generating random strings from regular expressions. |
| [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) | 54 | 3 | 2017/11/15 | 3 weeks ago | Fixed-width text formatting (encoder/decoder with reflection). |
| [guesslanguage](https://github.com/endeveit/guesslanguage) | 53 | 1 | 2014/12/16 | 3 years ago | Functions to determine the natural language of a unicode text. |
| [did](https://github.com/ockam-network/did) | 52 | 14 | 2018/11/02 | 6 months ago | DID (Decentralized Identifiers) Parser and Stringer in Go. |
| [allot](https://github.com/sbstjn/allot) | 48 | 1 | 2016/10/16 | 2 months ago | Placeholder and wildcard text parsing for CLI tools and bots. |
| [pagser](https://github.com/foolin/pagser) | 36 | 1 | 2020/04/19 | 1 year ago | Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler. |
| [gonameparts](https://github.com/polera/gonameparts) | 33 | 0 | 2015/05/17 | 1 year ago | Parses human names into individual name parts. |
| [slugify](https://github.com/avelino/slugify) | 27 | 2 | 2015/04/13 | 3 years ago | Go slugify application that handles string. |
| [codetree](https://github.com/aerogo/codetree) | 17 | 3 | 2016/11/26 | 1 year ago | Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure. |
| [enca](https://github.com/endeveit/enca) | 11 | 1 | 2014/12/17 | 5 years ago | Minimal cgo bindings for [libenca](http://cihar.com/software/enca/). |
| [syndfeed](https://github.com/zhengchun/syndfeed) | 7 | 1 | 2017/04/07 | 3 years ago | A syndication feed for Atom 1.0 and RSS 2.0. |
| [bbConvert](https://github.com/CalebQ42/bbConvert) | 6 | 1 | 2016/04/15 | 4 years ago | Converts bbCode to HTML that allows you to add support for custom bbCode tags. |
| [doi](https://github.com/hscells/doi) | 6 | 1 | 2017/08/02 | 3 years ago | Document object identifier (doi) parser in Go. |
| [ltsv](https://github.com/Wing924/ltsv) | 5 | 1 | 2019/05/12 | 2 years ago | High performance [LTSV (Labeled Tab Separated Value)](http://ltsv.org/) reader for Go. |
| [encoding](https://github.com/mickep76/encoding) | 4 | 1 | 2018/04/06 | 1 year ago | Package provides a generic interface to encoders and decodersa. |

### Utility
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [xurls](https://github.com/mvdan/xurls) | 798 | 19 | 2015/01/12 | 1 month ago | Extract urls from text. |
| [gotabulate](https://github.com/bndr/gotabulate) | 267 | 9 | 2014/08/21 | 5 months ago | Easily pretty-print your tabular data with Go. |
| [radix](https://github.com/yourbasic/radix) | 173 | 7 | 2017/06/09 | 3 years ago | fast string sorting algorithm. |
| [regroup](https://github.com/oriser/regroup) | 87 | 1 | 2020/09/08 | 3 months ago | Match regex expression named groups into go struct using struct tags and automatic parsing. |
| [parth](https://github.com/codemodus/parth) | 40 | 4 | 2015/04/06 | 2 years ago | URL path segmentation parsing. |
| [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) | 37 | 2 | 2018/09/09 | 2 weeks ago | A sanitization-based swear filter for Go. |
| [xj2go](https://github.com/wk30/xj2go) | 20 | 2 | 2017/09/19 | 11 months ago | Convert xml or json to go struct. |
| [xj2go](https://github.com/stackerzzq/xj2go) | 19 | 2 | 2017/09/19 | 1 year ago | Convert xml or json to go struct. |
| [tagify](https://github.com/zoomio/tagify) | 17 | 2 | 2018/03/20 | 2 weeks ago | Produces a set of tags from given source. |
| [kace](https://github.com/codemodus/kace) | 16 | 2 | 2015/06/04 | 2 years ago | Common case conversions covering common initialisms. |
| [TySug](https://github.com/Dynom/TySug) | 10 | 1 | 2018/06/05 | 11 months ago | Alternative suggestions with respect to keyboard layouts. |
| [parseargs-go](https://github.com/txgruppi/parseargs-go) | 8 | 0 | 2016/02/24 | 4 years ago | string argument parser that understands quotes and backslashes. |
| [textwrap](https://github.com/isbm/textwrap) | 2 | 2 | 2019/07/26 | 1 year ago | Implementation of `textwrap` module from Python. |

## Third-party APIs
        
*Libraries for accessing third party APIs.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-github](https://github.com/google/go-github) | 7600 | 214 | 2013/05/24 | 1 hour ago | Go library for accessing the GitHub REST API v3. |
| [aws-sdk-go](https://github.com/aws/aws-sdk-go) | 7002 | 269 | 2014/12/05 | 7 hours ago | The official AWS SDK for the Go programming language. |
| [google-api-go-client](https://github.com/googleapis/google-api-go-client) | 2701 | 163 | 2014/11/24 | 2 hours ago | Auto-generated Google APIs for Go. |
| [google-cloud-go](https://github.com/googleapis/google-cloud-go) | 2588 | 247 | 2014/05/09 | 26 minutes ago | Google Cloud APIs Go Client Library. |
| [discordgo](https://github.com/bwmarrin/discordgo) | 2160 | 57 | 2015/11/01 | 1 day ago | Go bindings for the Discord Chat API. |
| [stripe-go](https://github.com/stripe/stripe-go) | 1390 | 40 | 2014/06/05 | 47 minutes ago | Go client for the Stripe API. |
| [minio-go](https://github.com/minio/minio-go) | 1326 | 47 | 2015/05/02 | 6 days ago | Minio Go Library for Amazon S3 compatible cloud storage. |
| [go-twitter](https://github.com/dghubble/go-twitter) | 1275 | 30 | 2015/04/11 | 31 minutes ago | Go client library for the Twitter v1.1 APIs. |
| [anaconda](https://github.com/ChimeraCoder/anaconda) | 1100 | 21 | 2013/03/04 | 3 months ago | Go client library for the Twitter 1.1 API. |
| [facebook](https://github.com/huandu/facebook) | 976 | 119 | 2012/07/28 | 2 months ago | Go Library that supports the Facebook Graph API. |
| [githubv4](https://github.com/shurcooL/githubv4) | 787 | 21 | 2017/05/27 | 3 months ago | Go library for accessing the GitHub GraphQL API v4. |
| [webhooks](https://github.com/go-playground/webhooks) | 634 | 16 | 2015/10/25 | 1 month ago | Webhook receiver for GitHub and Bitbucket. |
| [paypal](https://github.com/plutov/paypal) | 426 | 25 | 2015/10/14 | 7 hours ago | Wrapper for PayPal payment API. |
| [geo-golang](https://github.com/codingsince1985/geo-golang) | 405 | 13 | 2014/12/04 | 2 weeks ago | Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](http://geocoder.opencagedata.com/api.html), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs. |
| [ethrpc](https://github.com/onrik/ethrpc) | 211 | 13 | 2017/01/24 | 10 months ago | Go bindings for Ethereum JSON RPC API. |
| [go-marathon](https://github.com/gambol99/go-marathon) | 196 | 13 | 2015/02/11 | 9 months ago | Go library for interacting with Mesosphere's Marathon PAAS. |
| [trello](https://github.com/adlio/trello) | 171 | 5 | 2016/09/24 | 3 weeks ago | Go wrapper for the Trello API. |
| [medium-sdk-go](https://github.com/Medium/medium-sdk-go) | 130 | 134 | 2015/09/26 | 2 years ago | Golang SDK for Medium's OAuth2 API. |
| [gostorm](https://github.com/jsgilmore/gostorm) | 127 | 11 | 2013/07/22 | 3 years ago | GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells. |
| [twitter-scraper](https://github.com/n0madic/twitter-scraper) | 126 | 3 | 2018/11/29 | 1 week ago | Scrape the Twitter Frontend API without authentication and limits. |
| [go-trending](https://github.com/andygrunwald/go-trending) | 116 | 7 | 2015/07/04 | 10 hours ago | Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github. |
| [hipchat](https://github.com/daneharrigan/hipchat) | 111 | 7 | 2013/04/28 | 4 years ago | A golang package to communicate with HipChat over XMPP. |
| [wit-go](https://github.com/wit-ai/wit-go) | 105 | 19 | 2018/08/20 | 4 weeks ago | Go client for wit.ai HTTP API. |
| [hipchat](https://github.com/andybons/hipchat) | 104 | 6 | 2012/10/20 | 5 years ago | This project implements a golang client library for the Hipchat API. |
| [pushover](https://github.com/gregdel/pushover) | 101 | 4 | 2015/02/19 | 1 month ago | Go wrapper for the Pushover API. |
| [cachet](https://github.com/andygrunwald/cachet) | 88 | 7 | 2015/10/31 | 2 weeks ago | Go client library for [Cachet (open source status page system)](https://cachethq.io/). |
| [igdb](https://github.com/Henry-Sarabia/igdb) | 68 | 2 | 2017/08/24 | 3 months ago | Go client for the [Internet Game Database API](https://api.igdb.com/). |
| [gosip](https://github.com/koltyakov/gosip) | 60 | 4 | 2019/01/26 | 1 week ago | Go client library SharePoint API. |
| [go-circleci](https://github.com/jszwedko/go-circleci) | 59 | 3 | 2015/08/14 | 1 year ago | Go client library for interacting with CircleCI's API. |
| [simples3](https://github.com/rhnvrm/simples3) | 58 | 2 | 2018/12/06 | 5 months ago | Simple no frills AWS S3 Library using REST with V4 Signing written in Go. |
| [gogtrends](https://github.com/groovili/gogtrends) | 56 | 2 | 2018/12/27 | 2 months ago | Google Trends Unofficial API. |
| [clarifai-go](https://github.com/Clarifai/clarifai-go) | 55 | 38 | 2015/09/28 | 3 years ago | Go client library for interfacing with the Clarifai API. |
| [go-unsplash](https://github.com/hbagdi/go-unsplash) | 55 | 1 | 2017/01/19 | 3 months ago | Go client library for the [Unsplash.com](https://unsplash.com) API. |
| [megos](https://github.com/andygrunwald/megos) | 55 | 5 | 2015/10/02 | 2 weeks ago | Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster. |
| [go-amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) | 49 | 1 | 2016/11/15 | 3 years ago | Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html). |
| [ynab.go](https://github.com/brunomvsouza/ynab.go) | 49 | 2 | 2018/07/13 | 1 month ago | Go wrapper for the YNAB API. |
| [gads](https://github.com/emiddleton/gads) | 48 | 7 | 2014/01/20 | 1 year ago | Google Adwords Unofficial API. |
| [uptimerobot](https://github.com/bitfield/uptimerobot) | 46 | 3 | 2018/05/29 | 6 months ago | Go wrapper and command-line client for the Uptime Robot v2 API. |
| [go-xkcd](https://github.com/nishanths/go-xkcd) | 45 | 3 | 2016/02/26 | 4 months ago | Go client for the xkcd API. |
| [gomusicbrainz](https://github.com/michiwend/gomusicbrainz) | 43 | 6 | 2014/09/10 | 5 months ago | Go MusicBrainz WS2 client library. |
| [golang-tmdb](https://github.com/cyruzin/golang-tmdb) | 42 | 1 | 2019/01/11 | 2 months ago | Golang wrapper for The Movie Database API v3. |
| [fcm](https://github.com/maddevsio/fcm) | 40 | 5 | 2017/01/06 | 1 year ago | Go library for Firebase Cloud Messaging. |
| [mixpanel](https://github.com/dukex/mixpanel) | 39 | 3 | 2014/05/20 | 1 year ago | Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications. |
| [go-spotify](https://github.com/rapito/go-spotify) | 38 | 2 | 2014/10/30 | 7 months ago | Go Library to access Spotify WEB API. |
| [golyrics](https://github.com/mamal72/golyrics) | 36 | 4 | 2016/11/18 | 3 years ago | Golyrics is a Go library to fetch music lyrics data from the Wikia website. |
| [translate](https://github.com/nuveo/translate) | 31 | 32 | 2015/07/13 | 5 years ago | Go online translation package. |
| [gami](https://github.com/bit4bit/gami) | 30 | 4 | 2014/05/14 | 3 years ago | Go library for Asterisk Manager Interface. |
| [gcm](https://github.com/TheOrioli/gcm) | 29 | 3 | 2015/11/09 | 5 years ago | Go library for Google Cloud Messaging. |
| [patreon-go](https://github.com/mxpv/patreon-go) | 26 | 5 | 2017/08/06 | 1 year ago | Go library for Patreon API. |
| [airtable](https://github.com/mehanizm/airtable) | 26 | 1 | 2020/04/12 | 3 months ago | Go client library for the [Airtable API](https://airtable.com/api). |
| [go-postman-collection](https://github.com/rbretecher/go-postman-collection) | 25 | 2 | 2019/11/16 | 22 hours ago | Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) (compatible with Insomnia). |
| [go-myanimelist](https://github.com/nstratos/go-myanimelist) | 24 | 1 | 2015/05/03 | 3 months ago | Go client library for accessing the [MyAnimeList API](http://myanimelist.net/modules.php?go=api). |
| [go-steam](https://github.com/sostronk/go-steam) | 24 | 11 | 2014/11/23 | 1 year ago | Go Library to interact with Steam game servers. |
| [lastpass-go](https://github.com/ansd/lastpass-go) | 22 | 3 | 2019/07/11 | 4 days ago | Go client library for the [LastPass](https://www.lastpass.com/) API. |
| [go-twitch](https://github.com/knspriggs/go-twitch) | 21 | 5 | 2016/06/28 | 3 years ago | Go client for interacting with the Twitch v3 API. |
| [go-shopify](https://github.com/rapito/go-shopify) | 21 | 1 | 2014/10/28 | 7 months ago | Go Library to make CRUD request to the Shopify API. |
| [brewerydb](https://github.com/naegelejd/brewerydb) | 17 | 3 | 2015/04/15 | 6 years ago | Go library for accessing the BreweryDB API. |
| [textbelt](https://github.com/farmergreg/textbelt) | 17 | 2 | 2015/09/01 | 5 years ago | Go client for the textbelt.com txt messaging API. |
| [codeship-go](https://github.com/codeship/codeship-go) | 16 | 20 | 2017/09/08 | 8 months ago | Go client library for interacting with Codeship's API v2. |
| [google-play-scraper](https://github.com/n0madic/google-play-scraper) | 15 | 1 | 2019/09/20 | 4 months ago | Get data from Google Play Store. |
| [go-hacknews](https://github.com/PaulRosset/go-hacknews) | 13 | 2 | 2017/08/10 | 3 years ago | Tiny Go client for HackerNews API. |
| [coinpaprika-api-go-client](https://github.com/coinpaprika/coinpaprika-api-go-client) | 12 | 8 | 2018/09/25 | 9 months ago | Go client library for interacting with Coinpaprika's API. |
| [go-google-analytics](https://github.com/chonthu/go-google-analytics) | 12 | 2 | 2015/06/01 | 6 years ago | Simple wrapper for easy google analytics reporting. |
| [go-aws-news](https://github.com/circa10a/go-aws-news) | 12 | 3 | 2020/01/08 | 4 months ago | Go application and library to fetch what's new from AWS. |
| [device-check-go](https://github.com/rinchsan/device-check-go) | 11 | 1 | 2019/04/11 | 1 month ago | Go client library for interacting with [iOS DeviceCheck API](https://developer.apple.com/documentation/devicecheck) v1. |
| [smitego](https://github.com/sergiotapia/smitego) | 10 | 0 | 2013/12/11 | 7 years ago | Go package to wraps access to the Smite game API. |
| [go-here](https://github.com/abdullahselek/go-here) | 9 | 0 | 2019/07/07 | 1 year ago | Go client library around the HERE location based APIs. |
| [gopaapi5](https://github.com/utekaravinash/gopaapi5) | 9 | 3 | 2020/02/15 | 1 year ago | Go Client Library for [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/). |
| [go-sophos](https://github.com/esurdam/go-sophos) | 8 | 2 | 2018/09/05 | 9 months ago | Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies. |
| [rrdaclient](https://github.com/Omie/rrdaclient) | 8 | 2 | 2014/09/15 | 6 years ago | Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP. |
| [slack](https://github.com/nlopes/slack) | 8 | 0 | 2015/01/24 | 1 month ago | Slack API in Go. |
| [go-google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) | 7 | 0 | 2016/10/24 | 4 years ago | Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/). |
| [go-sptrans](https://github.com/sergioaugrod/go-sptrans) | 6 | 3 | 2017/09/11 | 9 months ago | Go client library for the SPTrans Olho Vivo API. |
| [gumblr](https://github.com/mattcunningham/gumblr) | 6 | 1 | 2015/07/09 | 4 years ago | Go wrapper for the Tumblr v2 API. |
| [go-zooz](https://github.com/gojuno/go-zooz) | 6 | 14 | 2017/07/04 | 3 weeks ago | Go client for the Zooz API. |
| [go-chronos](https://github.com/axelspringer/go-chronos) | 4 | 9 | 2017/10/23 | 3 years ago | Go library for interacting with the [Chronos](https://mesos.github. |
| [libgoffi](https://github.com/clevabit/libgoffi) | 3 | 12 | 2019/08/03 | 10 months ago | Library adapter toolbox for native [libffi](http://sourceware. |
| [kanka](https://github.com/Henry-Sarabia/kanka) | 3 | 3 | 2019/12/26 | 11 months ago | Go client for the [Kanka API](https://kanka.io/en-US/docs/1.0). |
| [rawg-sdk-go](https://github.com/dimuska139/rawg-sdk-go) | 2 | 1 | 2020/10/16 | 5 days ago | Go library for the [RAWG Video Games Database](https://rawg. |
| [playlyfe-go-sdk](https://github.com/playlyfe/playlyfe-go-sdk) | 1 | 5 | 2015/05/25 | 5 years ago | The Playlyfe Rest API Go SDK. |
| [tripadvisor-golang](https://github.com/mrbenosborne/tripadvisor-golang) | 1 | 2 | 2019/04/15 | 1 year ago | Go wrapper for the TripAdvisor API. |
| [vl-go](https://github.com/verifid/vl-go) | 1 | 2 | 2019/02/09 | 1 month ago | Go client library around the VerifID identity verification layer API. |

## Utilities
        
*General utilities and tools to make your life easier.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [fzf](https://github.com/junegunn/fzf) | 37799 | 389 | 2013/10/23 | 4 days ago | Command-line fuzzy finder written in Go. |
| [hub](https://github.com/github/hub) | 21041 | 498 | 2009/12/05 | 1 week ago | wrap git commands with additional functionality to interact with github from the terminal. |
| [delve](https://github.com/go-delve/delve) | 13355 | 387 | 2014/05/20 | 1 year ago | Go debugger. |
| [ctop](https://github.com/bcicen/ctop) | 11757 | 163 | 2016/12/27 | 1 week ago | [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics. |
| [sqlx](https://github.com/jmoiron/sqlx) | 10456 | 193 | 2013/01/28 | 3 days ago | provides a set of extensions on top of the excellent built-in database/sql package. |
| [wuzz](https://github.com/asciimoo/wuzz) | 9691 | 169 | 2017/01/30 | 3 months ago | Interactive cli tool for HTTP inspection. |
| [goreleaser](https://github.com/goreleaser/goreleaser) | 8323 | 110 | 2016/12/21 | 5 hours ago | Deliver Go binaries as fast and easily as possible. |
| [usql](https://github.com/xo/usql) | 6587 | 116 | 2017/03/02 | 2 days ago | usql is a universal command-line interface for SQL databases. |
| [peco](https://github.com/peco/peco) | 6452 | 138 | 2014/06/06 | 1 month ago | Simplistic interactive filtering tool. |
| [godropbox](https://github.com/dropbox/godropbox) | 3949 | 246 | 2014/06/22 | 1 year ago | Common libraries for writing Go services/applications from Dropbox. |
| [hystrix-go](https://github.com/afex/hystrix-go) | 3225 | 90 | 2013/12/15 | 7 months ago | Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker. |
| [goreporter](https://github.com/360EntSecGroup-Skylar/goreporter) | 2882 | 101 | 2017/03/27 | 2 years ago | Golang tool that does static analysis, unit testing, code review and generate code quality report. |
| [go-funk](https://github.com/thoas/go-funk) | 2728 | 36 | 2016/12/30 | 5 days ago | Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...). |
| [minify](https://github.com/tdewolff/minify) | 2709 | 54 | 2014/05/21 | 4 days ago | Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats. |
| [panicparse](https://github.com/maruel/panicparse) | 2637 | 36 | 2015/02/02 | 1 day ago | Groups similar goroutines and colorizes stack dump. |
| [mc](https://github.com/minio/mc) | 1848 | 52 | 2015/01/16 | 1 day ago | Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems. |
| [storm](https://github.com/asdine/storm) | 1738 | 42 | 2016/01/10 | 1 month ago | Simple and powerful toolkit for BoltDB. |
| [mergo](https://github.com/imdario/mergo) | 1594 | 24 | 2013/03/11 | 1 week ago | Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements. |
| [spinner](https://github.com/briandowns/spinner) | 1541 | 16 | 2014/12/13 | 3 weeks ago | Go package to easily provide a terminal spinner with options. |
| [mole](https://github.com/davrodpin/mole) | 1479 | 29 | 2018/10/04 | 1 month ago | cli app to easily create ssh tunnels. |
| [boilr](https://github.com/tmrts/boilr) | 1336 | 29 | 2015/12/19 | 4 months ago | Blazingly fast CLI tool for creating projects from boilerplate templates. |
| [filetype](https://github.com/h2non/filetype) | 1323 | 29 | 2015/09/24 | 2 weeks ago | Small package to infer the file type checking the magic numbers signature. |
| [jump](https://github.com/gsamokovarov/jump) | 1110 | 18 | 2015/08/16 | 2 weeks ago | Jump helps you navigate faster by learning your habits. |
| [circuitbreaker](https://github.com/rubyist/circuitbreaker) | 947 | 20 | 2014/07/17 | 1 year ago | Circuit Breakers in Go. |
| [gtm](https://github.com/git-time-metric/gtm) | 869 | 29 | 2016/06/19 | 9 months ago | Simple, seamless, lightweight time tracking for Git. |
| [immortal](https://github.com/immortal/immortal) | 709 | 19 | 2016/06/30 | 1 year ago | \*nix cross-platform (OS agnostic) supervisor. |
| [hostctl](https://github.com/guumaster/hostctl) | 662 | 10 | 2020/03/14 | 3 months ago | A CLI tool to manage /etc/hosts with easy commands. |
| [circuit](https://github.com/cep21/circuit) | 578 | 14 | 2017/12/23 | 1 month ago | An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern. |
| [htcat](https://github.com/htcat/htcat) | 533 | 19 | 2013/08/05 | 2 years ago | Parallel and Pipelined HTTP GET Utility. |
| [mimetype](https://github.com/gabriel-vasile/mimetype) | 526 | 8 | 2018/07/02 | 3 hours ago | Package for MIME type detection based on magic numbers. |
| [cli](https://github.com/create-go-app/cli) | 485 | 9 | 2019/12/30 | 3 hours ago | A powerful CLI for create a new production-ready project with backend (Golang), frontend (JavaScript, TypeScript) & deploy automation (Ansible, Docker) by running one command. |
| [godaemon](https://github.com/VividCortex/godaemon) | 477 | 30 | 2013/08/01 | 1 week ago | Utility to write daemons. |
| [ergo](https://github.com/cristianoliveira/ergo) | 470 | 6 | 2017/08/19 | 5 days ago | The management of multiple local services running over different ports made easy. |
| [go-dry](https://github.com/ungerik/go-dry) | 465 | 15 | 2014/02/28 | 5 months ago | DRY (don't repeat yourself) package for Go. |
| [koazee](https://github.com/wesovilabs/koazee) | 464 | 12 | 2018/11/09 | 7 months ago | Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays. |
| [gopencils](https://github.com/bndr/gopencils) | 437 | 14 | 2014/06/23 | 2 years ago | Small and simple package to easily consume REST APIs. |
| [request](https://github.com/mozillazg/request) | 398 | 15 | 2014/12/21 | 1 year ago | Go HTTP Requests for Humans™. |
| [deepcopier](https://github.com/ulule/deepcopier) | 352 | 21 | 2015/07/24 | 1 year ago | Simple struct copying for Go. |
| [gubrak](https://github.com/novalagung/gubrak) | 351 | 7 | 2018/03/09 | 1 year ago | Golang utility library with syntactic sugar. It's like lodash, but for golang. |
| [clockwork](https://github.com/jonboulle/clockwork) | 340 | 6 | 2014/09/09 | 9 months ago | A simple fake clock for golang. |
| [go-rate](https://github.com/beefsack/go-rate) | 336 | 11 | 2014/08/25 | 10 months ago | Timed rate limiter for Go. |
| [delve](https://github.com/derekparker/delve) | 335 | 8 | 2020/02/18 | 2 days ago | Go debugger. |
| [scany](https://github.com/georgysavva/scany) | 307 | 5 | 2020/07/02 | 1 week ago | Library for scanning data from a database into Go structs and more. |
| [retry](https://github.com/kamilsk/retry) | 306 | 6 | 2016/11/02 | 4 months ago | The most advanced functional mechanism to perform actions repetitively until successful. |
| [gohper](https://github.com/cosiner/gohper) | 253 | 20 | 2015/03/23 | 3 years ago | Various tools/modules help for development. |
| [gohper](https://github.com/zhuah/gohper) | 252 | 20 | 2015/03/23 | 3 years ago | Various tools/modules help for development. |
| [serve](https://github.com/syntaqx/serve) | 245 | 7 | 2019/01/10 | 1 month ago | A static http server anywhere you need. |
| [go-trigger](https://github.com/sadlil/go-trigger) | 217 | 12 | 2015/10/19 | 4 years ago | Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project. |
| [scan](https://github.com/blockloop/scan) | 217 | 5 | 2017/11/27 | 2 weeks ago | Scan golang `sql.Rows` directly to structs, slices, or primitive types. |
| [util](https://github.com/shomali11/util) | 212 | 12 | 2017/05/24 | 1 year ago | Collection of useful utility functions. (strings, concurrency, manipulations, ...). |
| [gotenv](https://github.com/subosito/gotenv) | 199 | 3 | 2013/08/27 | 7 months ago | Load environment variables from `.env` or any `io.Reader` in Go. |
| [death](https://github.com/vrecan/death) | 172 | 3 | 2015/03/09 | 2 months ago | Managing go application shutdown with signals. |
| [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) | 169 | 4 | 2016/11/08 | 1 year ago | go:generate tool for wrapping symbols exported by golang plugins (1.8 only). |
| [rerun](https://github.com/ivpusic/rerun) | 162 | 7 | 2014/12/10 | 3 years ago | Recompiling and rerunning go apps when source changes. |
| [toolbox](https://github.com/viant/toolbox) | 162 | 16 | 2016/06/13 | 2 months ago | Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer. |
| [moldova](https://github.com/StabbyCutyou/moldova) | 161 | 5 | 2016/01/30 | 3 years ago | Utility for generating random data based on an input template. |
| [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) | 158 | 6 | 2015/10/12 | 4 months ago | XML Sitemap generator written in Go. |
| [robustly](https://github.com/VividCortex/robustly) | 150 | 17 | 2013/07/08 | 2 months ago | Runs functions resiliently, catching and restarting panics. |
| [apm](https://github.com/topfreegames/apm) | 149 | 19 | 2015/11/18 | 4 years ago | Process manager for Golang applications with an HTTP API. |
| [chyle](https://github.com/antham/chyle) | 138 | 6 | 2016/11/17 | 1 week ago | Changelog generator using a git repository with multiple configuration possibilities. |
| [onecache](https://github.com/adelowo/onecache) | 120 | 6 | 2017/04/14 | 1 year ago | Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc). |
| [lrserver](https://github.com/jaschaephraim/lrserver) | 119 | 5 | 2014/07/15 | 3 years ago | LiveReload server for Go. |
| [go-bsdiff](https://github.com/gabstv/go-bsdiff) | 117 | 2 | 2019/02/23 | 2 years ago | Pure Go bsdiff and bspatch libraries and CLI tools. |
| [countries](https://github.com/biter777/countries) | 100 | 4 | 2019/04/22 | 1 month ago | Full implementation of ISO-3166-1, ISO-4217, ITU-T E.164, Unicode CLDR and IANA ccTLD standarts. |
| [nostromo](https://github.com/pokanop/nostromo) | 89 | 5 | 2019/07/13 | 7 months ago | CLI for building powerful aliases. |
| [mssqlx](https://github.com/linxGnu/mssqlx) | 87 | 9 | 2016/12/26 | 6 days ago | Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind. |
| [xferspdy](https://github.com/monmohan/xferspdy) | 87 | 4 | 2015/05/22 | 3 months ago | Xferspdy provides binary diff and patch library in golang. |
| [go-pattern-match](https://github.com/alexpantyukhin/go-pattern-match) | 86 | 2 | 2018/12/11 | 1 year ago | Pattern matching libray. |
| [goseaweedfs](https://github.com/linxGnu/goseaweedfs) | 85 | 8 | 2017/07/20 | 1 month ago | SeaweedFS client library with almost full features. |
| [go-health](https://github.com/Talento90/go-health) | 81 | 3 | 2018/02/13 | 3 years ago | Health package simplifies the way you add health check to your services. |
| [sorty](https://github.com/jfcg/sorty) | 79 | 4 | 2019/02/18 | 2 months ago | Fast Concurrent / Parallel Sorting. |
| [pm](https://github.com/VividCortex/pm) | 78 | 19 | 2013/11/17 | 6 months ago | Process (i.e. goroutine) manager with an HTTP API. |
| [changie](https://github.com/miniscruff/changie) | 78 | 2 | 2020/12/05 | 15 hours ago | Automated changelog tool for preparing releases with lots of customization options. |
| [repeat](https://github.com/ssgreg/repeat) | 76 | 5 | 2017/11/22 | 11 months ago | Go implementation of different backoff strategies useful for retrying operations and heartbeating. |
| [netbug](https://github.com/e-dard/netbug) | 69 | 1 | 2015/03/05 | 5 years ago | Easy remote profiling of your services. |
| [mongo-go-pagination](https://github.com/gobeam/mongo-go-pagination) | 68 | 2 | 2020/02/04 | 1 week ago | Mongodb Pagination for official mongodb/mongo-go-driver package which supports  both normal queries and Aggregation pipelines. |
| [unis](https://github.com/esemplastic/unis) | 67 | 4 | 2017/05/06 | 4 years ago | Common Architecture™ for String Utilities in Go. |
| [multitick](https://github.com/VividCortex/multitick) | 65 | 17 | 2013/12/10 | 2 months ago | Multiplexor for aligned tickers. |
| [handy](https://github.com/miguelpragier/handy) | 64 | 8 | 2018/06/13 | 9 months ago | Many utilities and helpers like string handlers/formatters and validators. |
| [mimemagic](https://github.com/zRedShift/mimemagic) | 62 | 1 | 2018/10/11 | 3 months ago | Pure Go ultra performant MIME sniffing library/utility. |
| [cmd](https://github.com/commander-cli/cmd) | 61 | 5 | 2019/09/27 | 1 year ago | Library for executing shell commands on osx, windows and linux. |
| [go-astitodo](https://github.com/asticode/go-astitodo) | 58 | 2 | 2016/10/17 | 10 months ago | Parse TODOs in your GO code. |
| [goreadability](https://github.com/philipjkim/goreadability) | 58 | 6 | 2016/04/20 | 2 years ago | Webpage summary extractor using Facebook Open Graph and arc90's readability. |
| [minquery](https://github.com/icza/minquery) | 58 | 2 | 2016/11/16 | 1 year ago | MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off). |
| [golog](https://github.com/mlimaloureiro/golog) | 55 | 3 | 2016/01/09 | 2 years ago | Easy and lightweight CLI tool to time track your tasks. |
| [pgo](https://github.com/arthurkushman/pgo) | 52 | 6 | 2018/12/26 | 2 months ago | Convenient functions for PHP community. |
| [copy-pasta](https://github.com/jutkko/copy-pasta) | 49 | 5 | 2017/01/28 | 1 year ago | Universal multi-workstation clipboard that uses S3 like backend for the storage. |
| [filter](https://github.com/gookit/filter) | 48 | 6 | 2018/09/26 | 1 month ago | provide filtering, sanitizing, and conversion of Go data. |
| [retry](https://github.com/thedevsaddam/retry) | 48 | 1 | 2018/02/25 | 5 months ago | Simple and easy retry mechanism package for Go. |
| [beyond](https://github.com/wesovilabs/beyond) | 46 | 2 | 2019/10/18 | 1 month ago | The Go tool that will drive you to the AOP world! |
| [golarm](https://github.com/msempere/golarm) | 45 | 2 | 2015/08/14 | 5 years ago | Fire alarms with system events. |
| [goback](https://github.com/carlescere/goback) | 44 | 1 | 2015/03/13 | 4 months ago | Go simple exponential backoff package. |
| [slice](https://github.com/psampaz/slice) | 43 | 2 | 2019/11/26 | 1 year ago | Type-safe functions for common Go slice operations. |
| [go-lock](https://github.com/viney-shih/go-lock) | 43 | 0 | 2020/04/30 | 9 months ago | go-lock is a lock library implementing read-write mutex and read-write trylock without starvation. |
| [dbt](https://github.com/nikogura/dbt) | 42 | 1 | 2017/11/30 | 4 months ago | A framework for running self-updating signed binaries from a central, trusted repository. |
| [intrinsic](https://github.com/mengzhuo/intrinsic) | 42 | 4 | 2017/06/13 | 4 years ago | Use x86 SIMD without writing any assembly code. |
| [gpath](https://github.com/tenntenn/gpath) | 40 | 3 | 2017/05/24 | 4 years ago | Library to simplify access struct fields with Go's expression in reflection. |
| [retry-go](https://github.com/rafaeljesus/retry-go) | 40 | 2 | 2017/06/09 | 2 years ago | Retrying made simple and easy for golang. |
| [go-httpheader](https://github.com/mozillazg/go-httpheader) | 34 | 3 | 2017/06/24 | 5 months ago | Go library for encoding structs into Header fields. |
| [myhttp](https://github.com/inancgumus/myhttp) | 33 | 1 | 2017/09/13 | 3 years ago | Simple API to make HTTP GET requests with timeout support. |
| [gostrutils](https://github.com/ik5/gostrutils) | 32 | 3 | 2018/09/19 | 3 weeks ago | Collections of string manipulation and conversion functions. |
| [limiters](https://github.com/mennanov/limiters) | 32 | 3 | 2019/08/28 | 10 months ago | Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks. |
| [rclient](https://github.com/zpatrick/rclient) | 32 | 3 | 2017/02/28 | 1 year ago | Readable, flexible, simple-to-use client for REST APIs. |
| [evaluator](https://github.com/nullne/evaluator) | 31 | 2 | 2017/04/27 | 1 year ago | Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend. |
| [equalizer](https://github.com/reugn/equalizer) | 31 | 1 | 2019/06/14 | 4 months ago | Quota manager and rate limiter collection for Go. |
| [tome](https://github.com/cyruzin/tome) | 28 | 1 | 2019/04/12 | 1 year ago | Tome was designed to paginate simple RESTful APIs. |
| [cmd](https://github.com/SimonBaeumer/cmd) | 25 | 2 | 2019/09/27 | 1 year ago | Library for executing shell commands on osx, windows and linux. |
| [ugo](https://github.com/alxrm/ugo) | 25 | 1 | 2016/02/17 | 5 years ago | ugo is slice toolbox with concise syntax for Go. |
| [generate](https://github.com/go-playground/generate) | 24 | 3 | 2015/11/15 | 4 years ago | runs go generate recursively on a specified path or environment variable and can filter by regex. |
| [slicer](https://github.com/leaanthony/slicer) | 24 | 2 | 2019/01/10 | 8 months ago | Makes working with slices easier. |
| [goplaceholder](https://github.com/michiwend/goplaceholder) | 22 | 2 | 2014/10/12 | 5 years ago | a small golang lib to generate placeholder images. |
| [rerate](https://github.com/abo/rerate) | 20 | 4 | 2016/05/24 | 4 years ago | Redis-based rate counter and rate limiter for Go. |
| [shutdown](https://github.com/ztrue/shutdown) | 19 | 1 | 2018/11/17 | 2 years ago | App shutdown hooks for `os.Signal` handling. |
| [ctxutil](https://github.com/posener/ctxutil) | 18 | 1 | 2018/07/30 | 1 year ago | A collection of utility functions for contexts. |
| [ghokin](https://github.com/antham/ghokin) | 18 | 2 | 2018/08/03 | 1 week ago | Parallelized formatter with no external dependencies for gherkin (cucumber, behat...). |
| [r](https://github.com/is5/r) | 18 | 3 | 2020/02/20 | 1 year ago | Python-like `range()` experience for Go. |
| [backscanner](https://github.com/icza/backscanner) | 17 | 4 | 2017/10/18 | 1 year ago | A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward. |
| [dlog](https://github.com/kirillDanshin/dlog) | 16 | 2 | 2016/07/04 | 4 years ago | Compile-time controlled logger to make your release smaller without removing debug calls. |
| [filler](https://github.com/yaronsumel/filler) | 16 | 1 | 2017/04/05 | 4 years ago | small utility to fill structs using "fill" tag. |
| [structs](https://github.com/PumpkinSeed/structs) | 16 | 3 | 2017/08/26 | 3 years ago | Implement simple functions to manipulate structs. |
| [mimesniffer](https://github.com/aofei/mimesniffer) | 15 | 1 | 2018/12/20 | 4 months ago | A MIME type sniffer for Go. |
| [okrun](https://github.com/xta/okrun) | 15 | 3 | 2014/10/01 | 6 years ago | go run error steamroller. |
| [command](https://github.com/txgruppi/command) | 14 | 1 | 2015/08/24 | 5 years ago | Command pattern for Go with thread safe serial and parallel dispatcher. |
| [jsend](https://github.com/clevergo/jsend) | 14 | 4 | 2020/01/14 | 1 week ago | JSend's implementation writen in Go. |
| [rest-go](https://github.com/edermanoel94/rest-go) | 13 | 3 | 2019/07/29 | 11 months ago | A package that provide many helpful methods for working with rest api. |
| [go-convert](https://github.com/Eun/go-convert) | 13 | 1 | 2019/06/07 | 2 months ago | Package go-convert enbles you to convert a value into another type. |
| [retry](https://github.com/shafreeck/retry) | 11 | 0 | 2018/07/18 | 1 year ago | A pretty simple library to ensure your work to be done. |
| [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) | 10 | 1 | 2019/05/16 | 1 year ago | Go package for working with Problem Details. |
| [ptr](https://github.com/gotidy/ptr) | 10 | 2 | 2019/12/25 | 8 months ago | Package that provide functions for simplified creation of pointers from constants of basic types. |
| [silk](https://github.com/chrispassas/silk) | 9 | 1 | 2018/12/18 | 8 months ago | Read silk netflow files. |
| [go-countries](https://github.com/mikekonan/go-countries) | 9 | 3 | 2020/10/27 | 6 months ago | Lightweight lookup over ISO-3166 codes. |
| [copy](https://github.com/gotidy/copy) | 8 | 3 | 2020/10/09 | 6 months ago | Package for fast copying structs of different types. |
| [retry](https://github.com/percolate/retry) | 7 | 37 | 2018/06/15 | 1 year ago | A simple but highly configurable retry package for Go. |
| [sliceconv](https://github.com/Henry-Sarabia/sliceconv) | 7 | 1 | 2019/02/15 | 1 year ago | Slice conversion between primitive types. |
| [nfdump](https://github.com/chrispassas/nfdump) | 7 | 1 | 2020/04/08 | 1 year ago | Read nfdump netflow files. |
| [statiks](https://github.com/janiltonmaciel/statiks) | 7 | 0 | 2018/06/26 | 9 months ago | Fast, zero-configuration, static HTTP filer server. |
| [blank](https://github.com/Henry-Sarabia/blank) | 6 | 2 | 2019/02/13 | 1 year ago | Verify or remove blanks and whitespace from strings. |
| [go-safe](https://github.com/kenkyu392/go-safe) | 4 | 0 | 2019/10/29 | 1 month ago | Panic-safe sandbox. |
| [lets-go](https://github.com/aplescia-chwy/lets-go) | 3 | 1 | 2020/02/19 | 9 months ago | Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities. |
| [lets-go](https://github.com/aplescia/lets-go) | 3 | 1 | 2020/02/19 | 2 months ago | Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities. |
| [olaf](https://github.com/btnguyen2k/olaf) | 2 | 1 | 2019/01/03 | 2 years ago | Twitter Snowflake implemented in Go. |
| [tik](https://github.com/andy2046/tik) | 2 | 1 | 2020/07/04 | 8 months ago | Simple and easy timing wheel package for Go. |
| [goctx](https://github.com/zerosnake0/goctx) | 2 | 1 | 2020/11/14 | 7 months ago | Get your context value with high performance. |
| [compare](https://github.com/posener/compare) | 1 | 1 | 2020/03/13 | 1 year ago | Enables more readable and easier comparison tasks. |
| [bleep](https://github.com/sinhashubham95/bleep) | 1 | 1 | 2021/01/02 | 6 months ago | Perform any number of actions on any set of OS signals in Go. |

## UUID
        
*Libraries for working with UUIDs.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [uuid](https://github.com/google/uuid) | 2782 | 47 | 2016/02/12 | 13 hours ago | Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services. |
| [ulid](https://github.com/oklog/ulid) | 2302 | 44 | 2016/12/06 | 6 days ago | Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier). |
| [uuid](https://github.com/gofrs/uuid) | 947 | 18 | 2018/07/13 | 3 months ago | Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid. |
| [wuid](https://github.com/edwingeng/wuid) | 417 | 16 | 2018/01/27 | 2 months ago | An extremely fast unique number generator, 10-135 times faster than UUID. |
| [sno](https://github.com/muyo/sno) | 49 | 3 | 2019/05/26 | 2 months ago | Compact, sortable and fast unique IDs with embedded metadata. |
| [nanoid](https://github.com/aidarkhanov/nanoid) | 32 | 1 | 2019/07/02 | 1 year ago | A tiny and efficient Go unique string ID generator. |
| [Goid](https://github.com/JakeHL/Goid) | 30 | 4 | 2017/05/19 | 2 years ago | Generate and Parse RFC4122 compliant V4 UUIDs. |
| [uuid](https://github.com/agext/uuid) | 13 | 3 | 2016/02/03 | 1 year ago | Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier. |
| [gouid](https://github.com/twharmon/gouid) | 8 | 1 | 2020/10/08 | 1 month ago | Generate cryptographically secure random string IDs with just one allocation. |

## Validation
        
*Libraries for validation.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [validator](https://github.com/go-playground/validator) | 8168 | 101 | 2015/02/12 | 2 days ago | Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving. |
| [govalidator](https://github.com/asaskevich/govalidator) | 4831 | 104 | 2014/06/20 | 1 week ago | Validators and sanitizers for strings, numerics, slices and structs. |
| [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) | 2214 | 33 | 2016/06/22 | 2 weeks ago | Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags. |
| [govalidator](https://github.com/thedevsaddam/govalidator) | 999 | 22 | 2017/09/13 | 5 months ago | Validate Golang request data with simple rules. Highly inspired by Laravel's request validation. |
| [validate](https://github.com/gookit/validate) | 443 | 16 | 2018/07/16 | 4 days ago | Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features. |
| [checkdigit](https://github.com/osamingo/checkdigit) | 78 | 0 | 2019/04/05 | 6 months ago | Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.). |
| [validate](https://github.com/gobuffalo/validate) | 59 | 8 | 2018/02/10 | 7 months ago | This package provides a framework for writing validations for Go applications. |
| [jio](https://github.com/faceair/jio) | 58 | 2 | 2018/10/28 | 1 year ago | jio is a json schema validator similar to [joi](https://github.com/hapijs/joi). |
| [terraform-validator](https://github.com/thazelart/terraform-validator) | 58 | 2 | 2019/05/29 | 9 months ago | A norms and conventions validator for Terraform. |
| [gody](https://github.com/guiferpa/gody) | 49 | 0 | 2018/11/01 | 5 months ago | :balloon: A lightweight struct validator for Go. |
| [govalid](https://github.com/twharmon/govalid) | 22 | 1 | 2019/02/17 | 8 months ago | Fast, tag-based validation for structs. |

## Version Control
        
*Libraries for version control.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-git](https://github.com/src-d/go-git) | 5013 | 100 | 2015/10/22 | 1 year ago | highly extensible Git implementation in pure Go. |
| [go-git](https://github.com/go-git/go-git) | 2457 | 39 | 2019/12/19 | 6 days ago | highly extensible Git implementation in pure Go. |
| [git2go](https://github.com/libgit2/git2go) | 1633 | 53 | 2013/03/05 | 3 months ago | Go bindings for libgit2. |
| [hercules](https://github.com/src-d/hercules) | 1381 | 18 | 2016/12/12 | 1 month ago | gaining advanced insights from Git repository history. |
| [gh](https://github.com/rjeczalik/gh) | 75 | 6 | 2015/03/08 | 2 years ago | Scriptable server and net/http middleware for GitHub Webhooks. |
| [go-vcs](https://github.com/sourcegraph/go-vcs) | 75 | 62 | 2013/06/02 | 3 months ago | manipulate and inspect VCS repositories in Go. |
| [hgo](https://github.com/beyang/hgo) | 13 | 3 | 2014/06/18 | 5 years ago | Hgo is a collection of Go packages providing read-access to local Mercurial repositories. |

## Video
        
*Libraries for manipulating video.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [goav](https://github.com/giorgisio/goav) | 1648 | 50 | 2015/05/21 | 1 month ago | Comprehensive Go bindings for FFmpeg. |
| [m3u8](https://github.com/grafov/m3u8) | 840 | 38 | 2013/02/05 | 2 months ago | Parser and generator library of M3U8 playlists for Apple HLS. |
| [gmf](https://github.com/3d0c/gmf) | 693 | 32 | 2013/04/03 | 1 month ago | Go bindings for FFmpeg av\* libraries. |
| [go-astits](https://github.com/asticode/go-astits) | 369 | 15 | 2017/07/04 | 1 week ago | Parse and demux MPEG Transport Streams (.ts) natively in GO. |
| [go-astisub](https://github.com/asticode/go-astisub) | 321 | 8 | 2016/12/16 | 3 days ago | Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.). |
| [libvlc-go](https://github.com/adrg/libvlc-go) | 222 | 11 | 2015/01/06 | 3 months ago | Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player). |
| [gst](https://github.com/ziutek/gst) | 159 | 10 | 2011/07/26 | 6 months ago | Go bindings for GStreamer. |
| [go-m3u8](https://github.com/quangngotan95/go-m3u8) | 75 | 2 | 2018/11/06 | 1 year ago | Parser and generator library for Apple m3u8 playlists. |
| [v4l](https://github.com/korandiz/v4l) | 58 | 5 | 2016/10/25 | 7 months ago | Video capture library for Linux, written in Go. |
| [libgosubs](https://github.com/wargarblgarbl/libgosubs) | 14 | 2 | 2017/05/03 | 1 year ago | Subtitle format support for go. Supports .srt, .ttml, and .ass. |
| [go-mpd](https://github.com/unki2aut/go-mpd) | 9 | 1 | 2018/11/02 | 10 months ago | Parser and generator library for MPEG-DASH manifest files. |

## Web Frameworks
        
*Full stack web frameworks.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gin](https://github.com/gin-gonic/gin) | 49461 | 1355 | 2014/06/16 | 12 hours ago | Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity. |
| [echo](https://github.com/labstack/echo) | 20224 | 543 | 2015/03/01 | 8 hours ago | High performance, minimalist Go web framework. |
| [fiber](https://github.com/gofiber/fiber) | 14149 | 227 | 2020/01/16 | 1 day ago | An Express.js inspired web framework build on Fasthttp. |
| [revel](https://github.com/revel/revel) | 12300 | 545 | 2011/12/09 | 4 months ago | High-productivity web framework for the Go language. |
| [goa](https://github.com/goadesign/goa) | 4302 | 166 | 2014/12/05 | 6 days ago | Goa provides a holistic approach for developing remote APIs and microservices in Go. |
| [go-json-rest](https://github.com/ant0ine/go-json-rest) | 3473 | 160 | 2013/02/19 | 5 months ago | Quick and easy way to setup a RESTful JSON API. |
| [gizmo](https://github.com/nytimes/gizmo) | 3445 | 119 | 2015/12/15 | 6 hours ago | Microservice toolkit used by the New York Times. |
| [macaron](https://github.com/go-macaron/macaron) | 3174 | 146 | 2014/07/10 | 8 months ago | Macaron is a high productive and modular design web framework in Go. |
| [utron](https://github.com/gernest/utron) | 2198 | 69 | 2015/09/16 | 2 years ago | Lightweight MVC framework for Go(Golang). |
| [go-tigertonic](https://github.com/rcrowley/go-tigertonic) | 995 | 46 | 2013/02/09 | 3 years ago | Go framework for building JSON web services inspired by Dropwizard. |
| [goyave](https://github.com/go-goyave/goyave) | 863 | 26 | 2019/10/21 | 1 week ago | Feature-complete web framework aimed at clean code and fast development, with powerful built-in functionalities. |
| [tango](https://github.com/lunny/tango) | 834 | 76 | 2014/12/17 | 2 years ago | Micro & pluggable web framework for Go. |
| [goyave](https://github.com/System-Glitch/goyave) | 807 | 24 | 2019/10/21 | 4 months ago | Feature-complete web framework aimed at clean code and fast development, with powerful built-in functionalities. |
| [gearbox](https://github.com/gogearbox/gearbox) | 520 | 16 | 2020/04/25 | 1 week ago | A web framework written in Go with a focus on high performance and memory optimization. |
| [gongular](https://github.com/mustafaakin/gongular) | 442 | 21 | 2016/06/22 | 1 year ago | Fast Go web framework with input mapping/validation and (DI) Dependency Injection. |
| [neo](https://github.com/ivpusic/neo) | 410 | 34 | 2015/02/04 | 3 years ago | Neo is minimal and fast Go Web Framework with extremely simple API. |
| [air](https://github.com/aofei/air) | 405 | 19 | 2016/07/20 | 2 months ago | An ideally refined web framework for Go. |
| [aero](https://github.com/aerogo/aero) | 384 | 19 | 2016/11/09 | 1 year ago | High-performance web framework for Go, reaches top scores in Lighthouse. |
| [mango](https://github.com/paulbellamy/mango) | 357 | 22 | 2011/05/25 | 3 years ago | Mango is a modular web-application framework for Go, inspired by Rack, and PEP333. |
| [gondola](https://github.com/rainycape/gondola) | 308 | 15 | 2014/07/25 | 2 years ago | The web framework for writing faster sites, faster. |
| [golf](https://github.com/dinever/golf) | 249 | 17 | 2015/11/18 | 4 years ago | Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library. |
| [flamingo](https://github.com/i-love-flamingo/flamingo) | 216 | 24 | 2019/04/02 | 1 hour ago | Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc. |
| [beego](https://github.com/astaxie/beego) | 195 | 8 | 2012/02/29 | 2 months ago | beego is an open-source, high-performance web framework for the Go programming language. |
| [flamingo-commerce](https://github.com/i-love-flamingo/flamingo-commerce) | 191 | 22 | 2019/04/02 | 7 hours ago | Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications. |
| [ginrpc](https://github.com/xxjwxc/ginrpc) | 178 | 7 | 2019/06/22 | 1 week ago | Gin parameter automatic binding tool,gin rpc tools. |
| [gearbox](https://github.com/abahmed/gearbox) | 176 | 4 | 2020/04/25 | 1 year ago | A web framework written in Go with a focus on high performance and memory optimization. |
| [webgo](https://github.com/bnkamalesh/webgo) | 174 | 9 | 2015/12/16 | 1 week ago | A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc). |
| [hiboot](https://github.com/hidevopsio/hiboot) | 162 | 14 | 2018/03/16 | 1 week ago | hiboot is a high performance web application framework with auto configuration and dependency injection support. |
| [uadmin](https://github.com/uadmin/uadmin) | 138 | 11 | 2018/10/05 | 1 day ago | Fully featured web framework for Golang, inspired by Django. |
| [go-rest](https://github.com/ungerik/go-rest) | 125 | 10 | 2012/07/13 | 4 years ago | Small and evil REST framework for Go. |
| [appy](https://github.com/appist/appy) | 96 | 3 | 2019/05/27 | 6 days ago | An opinionated productive web framework that helps scaling business easier. |
| [patron](https://github.com/beatlabs/patron) | 76 | 15 | 2019/01/30 | 10 hours ago | Patron is a microservice framework following best cloud practices with a focus on productivity. |
| [microservice](https://github.com/claygod/microservice) | 74 | 9 | 2016/12/15 | 2 years ago | The framework for the creation of microservices, written in Golang. |
| [vox](https://github.com/aisk/vox) | 74 | 2 | 2014/12/24 | 1 month ago | A golang web framework for humans, inspired by Koa heavily. |
| [golax](https://github.com/fulldump/golax) | 73 | 7 | 2016/01/30 | 3 years ago | A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more. |
| [rux](https://github.com/gookit/rux) | 63 | 4 | 2018/08/05 | 2 weeks ago | Simple and fast web framework for build golang HTTP applications. |
| [yarf](https://github.com/yarf-framework/yarf) | 62 | 4 | 2015/09/02 | 2 years ago | Fast micro-framework designed to build REST APIs and web services in a fast and simple way. |
| [fireball](https://github.com/zpatrick/fireball) | 56 | 4 | 2016/07/20 | 2 years ago | More "natural" feeling web framework. |
| [goa](https://github.com/goa-go/goa) | 45 | 4 | 2019/07/26 | 1 year ago | goa is just like koajs for golang, it is a flexible, light, high-performance and extensible web framework based on middleware. |
| [api](https://github.com/resoursea/api) | 31 | 6 | 2015/01/24 | 6 years ago | REST framework for quickly writing resource based services. |
| [rex](https://github.com/goanywhere/rex) | 31 | 2 | 2014/10/16 | 3 years ago | Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`. |
| [goweb](https://github.com/twharmon/goweb) | 24 | 1 | 2019/05/07 | 5 months ago | Web framework with routing, websockets, logging, middleware, static file server (optional gzip), and automatic TLS. |
| [banjo](https://github.com/n4Zz2/banjo) | 18 | 1 | 2017/12/09 | 3 years ago | Very simple and fast web framework for Go. |
| [banjo](https://github.com/nsheremet/banjo) | 17 | 1 | 2017/12/09 | 3 years ago | Very simple and fast web framework for Go. |

### Middlewares
        

#### Actual middlewares
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [tollbooth](https://github.com/didip/tollbooth) | 1971 | 51 | 2015/05/17 | 6 days ago | Rate limit HTTP request handler. |
| [cors](https://github.com/rs/cors) | 1861 | 32 | 2014/10/25 | 1 week ago | Easily add CORS capabilities to your API. |
| [limiter](https://github.com/ulule/limiter) | 1297 | 28 | 2015/10/02 | 1 week ago | Dead simple rate limit middleware for Go. |
| [go-server-timing](https://github.com/mitchellh/go-server-timing) | 819 | 18 | 2018/02/12 | 8 months ago | Add/parse Server-Timing header. |
| [go-fault](https://github.com/github/go-fault) | 398 | 115 | 2020/05/14 | 2 months ago | Fault injection middleware for Go. |
| [ln-paywall](https://github.com/philippgille/ln-paywall) | 111 | 5 | 2018/06/29 | 2 years ago | Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin). |
| [xff](https://github.com/sebest/xff) | 81 | 2 | 2014/12/22 | 6 months ago | Handle `X-Forwarded-For` header and friends. |
| [formjson](https://github.com/rs/formjson) | 36 | 2 | 2015/03/19 | 5 years ago | Transparently handle JSON input as a standard form POST. |
| [client-timing](https://github.com/posener/client-timing) | 19 | 1 | 2018/02/23 | 1 year ago | An HTTP client for Server-Timing header. |

#### Libraries for creating HTTP middlewares
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [negroni](https://github.com/urfave/negroni) | 7028 | 239 | 2014/05/18 | 5 months ago | Idiomatic HTTP middleware for Golang. |
| [alice](https://github.com/justinas/alice) | 2308 | 48 | 2014/05/25 | 5 months ago | Painless middleware chaining for Go. |
| [render](https://github.com/unrolled/render) | 1520 | 35 | 2014/06/10 | 1 month ago | Go package for easily rendering JSON, XML, and HTML template responses. |
| [stats](https://github.com/thoas/stats) | 579 | 16 | 2015/03/05 | 2 years ago | Go middleware that stores various information about your web application. |
| [interpose](https://github.com/carbocation/interpose) | 290 | 12 | 2014/07/20 | 4 years ago | Minimalist net/http middleware for golang. |
| [renderer](https://github.com/thedevsaddam/renderer) | 223 | 7 | 2017/11/07 | 5 months ago | Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go. |
| [muxchain](https://github.com/stephens2424/muxchain) | 209 | 5 | 2014/05/03 | 2 years ago | Lightweight middleware for net/http. |
| [rye](https://github.com/InVisionApp/rye) | 97 | 198 | 2016/10/06 | 2 years ago | Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context. |
| [gores](https://github.com/alioygur/gores) | 96 | 5 | 2015/12/25 | 6 months ago | Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs. |
| [mediary](https://github.com/HereMobilityDevelopers/mediary) | 72 | 4 | 2020/03/23 | 1 year ago | add interceptors to `http.Client` to allow dumping/shaping/tracing/... of requests/responses. |
| [chain](https://github.com/codemodus/chain) | 63 | 7 | 2015/05/14 | 2 years ago | Handler wrapper chaining with scoped data (net/context-based "middleware"). |
| [wrap](https://github.com/go-on/wrap) | 59 | 3 | 2014/02/16 | 2 years ago | Small middlewares package for net/http. |
| [catena](https://github.com/codemodus/catena) | 7 | 2 | 2015/07/30 | 2 years ago | http.Handler wrapper catenation (same API as "chain"). |

### Routers
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [mux](https://github.com/gorilla/mux) | 14683 | 310 | 2012/10/02 | 1 month ago | Powerful URL router and dispatcher for golang. |
| [httprouter](https://github.com/julienschmidt/httprouter) | 12892 | 320 | 2013/12/05 | 1 month ago | High performance router. Use this and the standard http handlers to form a very high performance web framework. |
| [chi](https://github.com/go-chi/chi) | 9687 | 185 | 2015/10/15 | 1 week ago | Small, fast and expressive HTTP router built on net/context. |
| [web](https://github.com/gocraft/web) | 1444 | 60 | 2013/11/16 | 9 months ago | Mux and middleware package in Go. |
| [bone](https://github.com/go-zoo/bone) | 1273 | 37 | 2014/11/19 | 2 years ago | Lightning Fast HTTP Multiplexer. |
| [fasthttprouter](https://github.com/buaazp/fasthttprouter) | 874 | 34 | 2015/12/13 | 2 years ago | High performance router forked from `httprouter`. The first router fit for `fasthttp`. |
| [goji](https://github.com/goji/goji) | 866 | 42 | 2015/11/16 | 1 year ago | Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`. |
| [gorouter](https://github.com/xujiajun/gorouter) | 499 | 16 | 2018/01/29 | 1 year ago | A simple and fast HTTP router for Go. |
| [httptreemux](https://github.com/dimfeld/httptreemux) | 492 | 24 | 2014/05/14 | 3 months ago | High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter. |
| [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) | 407 | 29 | 2015/10/27 | 6 months ago | An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs. |
| [lars](https://github.com/go-playground/lars) | 383 | 16 | 2015/12/24 | 2 years ago | Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks. |
| [siesta](https://github.com/VividCortex/siesta) | 349 | 29 | 2014/09/23 | 2 months ago | Composable framework to write middleware and handlers. |
| [vestigo](https://github.com/husobee/vestigo) | 262 | 15 | 2015/09/22 | 9 months ago | Performant, stand-alone, HTTP compliant URL Router for go web applications. |
| [router](https://github.com/gowww/router) | 160 | 7 | 2017/05/25 | 1 year ago | Lightning fast HTTP router fully compatible with the net/http.Handler interface. |
| [alien](https://github.com/gernest/alien) | 118 | 4 | 2016/01/30 | 2 years ago | Lightweight and fast http router from outer space. |
| [pure](https://github.com/go-playground/pure) | 114 | 6 | 2016/09/23 | 7 months ago | Is a lightweight HTTP router that sticks to the std "net/http" implementation. |
| [violetear](https://github.com/nbari/violetear) | 103 | 4 | 2015/06/19 | 1 month ago | Go HTTP router. |
| [Bxog](https://github.com/claygod/Bxog) | 102 | 8 | 2016/05/19 | 1 year ago | Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters. |
| [gorouter](https://github.com/vardius/gorouter) | 95 | 6 | 2016/07/14 | 1 week ago | GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`. |
| [xmux](https://github.com/rs/xmux) | 90 | 6 | 2015/12/14 | 4 years ago | High performance muxer based on `httprouter` with `net/context` support. |
| [bellt](https://github.com/GuilhermeCaruso/bellt) | 49 | 6 | 2019/02/21 | 1 year ago | A simple Go HTTP router. |
| [fastrouter](https://github.com/razonyang/fastrouter) | 19 | 2 | 2017/11/01 | 3 years ago | a fast, flexible HTTP router written in Go. |
| [route](https://github.com/goroute/route) | 7 | 4 | 2019/07/06 | 1 year ago | Simple yet powerful HTTP request multiplexer. |

## Windows
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-ole](https://github.com/go-ole/go-ole) | 767 | 40 | 2011/01/21 | 1 week ago | Win32 OLE implementation for golang. |
| [d3d9](https://github.com/gonutz/d3d9) | 124 | 7 | 2015/12/12 | 1 month ago | Go bindings for Direct3D9. |
| [gosddl](https://github.com/MonaxGT/gosddl) | 5 | 2 | 2018/12/04 | 2 years ago | Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL. |

## XML
        
*Libraries and tools for manipulating XML.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [zek](https://github.com/miku/zek) | 473 | 21 | 2017/11/23 | 8 months ago | Generate a Go struct from XML. |
| [xpath](https://github.com/antchfx/xpath) | 400 | 10 | 2016/10/09 | 1 month ago | XPath package for Go. |
| [xquery](https://github.com/antchfx/xquery) | 154 | 12 | 2016/10/09 | 3 years ago | XQuery lets you extract data from HTML/XML documents using XPath expression. |
| [xml2map](https://github.com/sbabiv/xml2map) | 32 | 1 | 2018/08/06 | 4 months ago | XML to MAP converter written Golang. |
| [xmlwriter](https://github.com/shabbyrobe/xmlwriter) | 19 | 2 | 2017/04/11 | 3 months ago | Procedural XML generation API based on libxml2's xmlwriter module. |
| [XML-Comp](https://github.com/XML-Comp/XML-Comp) | 15 | 2 | 2016/10/25 | 3 years ago | Simple command line XML comparer that generates diffs of folders, files and tags. |

## WebAssembly
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [tinygo](https://github.com/tinygo-org/tinygo) | 8251 | 157 | 2018/06/07 | 4 hours ago | Go compiler for small places. Microcontrollers, WebAssembly, and command-line tools. Based on LLVM. |
| [dom](https://github.com/dennwc/dom) | 431 | 18 | 2018/06/30 | 1 year ago | DOM library. |
| [go-canvas](https://github.com/markfarnan/go-canvas) | 137 | 5 | 2019/05/05 | 7 months ago | Library to use HTML5 Canvas, with all drawing within go code. |
| [webapi](https://github.com/gowebapi/webapi) | 84 | 7 | 2019/02/08 | 5 months ago | Bindings for DOM and HTML generated from WebIDL. |
| [wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) | 81 | 3 | 2018/07/14 | 4 months ago | Run Go WASM tests in your browser. |
| [vert](https://github.com/norunners/vert) | 49 | 5 | 2018/03/25 | 3 months ago | Interop between Go and JS values. |

## Files
        

## File Handling
        
*Libraries for handling files and file systems.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [afero](https://github.com/spf13/afero) | 3856 | 92 | 2014/10/28 | 21 hours ago | FileSystem Abstraction System for Go. |
| [pdfcpu](https://github.com/pdfcpu/pdfcpu) | 2459 | 61 | 2017/06/18 | 16 hours ago | PDF processor. |
| [notify](https://github.com/rjeczalik/notify) | 670 | 30 | 2014/09/08 | 3 weeks ago | File system event notification library with simple API, similar to os/signal. |
| [copy](https://github.com/otiai10/copy) | 322 | 7 | 2017/09/01 | 3 weeks ago | Copy directory recursively. |
| [bigfile](https://github.com/bigfile/bigfile) | 200 | 15 | 2019/07/15 | 1 year ago | A file transfer system, support to manage files with http api, rpc call and ftp client. |
| [afs](https://github.com/viant/afs) | 148 | 12 | 2019/08/19 | 2 months ago | Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go. |
| [vfs](https://github.com/C2FO/vfs) | 113 | 23 | 2017/08/01 | 2 days ago | A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS. |
| [go-csv-tag](https://github.com/artonge/go-csv-tag) | 86 | 0 | 2017/06/18 | 9 months ago | Load csv file using tag. |
| [go-exiftool](https://github.com/barasher/go-exiftool) | 68 | 5 | 2019/05/12 | 1 week ago | Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...). |
| [opc](https://github.com/qmuntal/opc) | 67 | 3 | 2018/11/06 | 4 months ago | Load Open Packaging Conventions (OPC) files for Go. |
| [skywalker](https://github.com/dixonwille/skywalker) | 64 | 4 | 2017/08/01 | 3 years ago | Package to allow one to concurrently go through a filesystem with ease. |
| [tarfs](https://github.com/posener/tarfs) | 47 | 2 | 2017/03/10 | 1 year ago | Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files. |
| [checksum](https://github.com/codingsince1985/checksum) | 34 | 2 | 2014/11/05 | 10 months ago | Compute message digest, like MD5 and SHA256, for large files. |
| [baraka](https://github.com/xis/baraka) | 30 | 2 | 2020/07/12 | 2 months ago | A library to process http file uploads easily. |
| [go-gtfs](https://github.com/artonge/go-gtfs) | 27 | 2 | 2017/07/09 | 9 months ago | Load gtfs files in go. |
| [parquet](https://github.com/parsyl/parquet) | 26 | 7 | 2019/01/29 | 3 weeks ago | Read and write [parquet](https://parquet.apache.org) files. |
| [flop](https://github.com/homedepot/flop) | 24 | 18 | 2019/03/01 | 5 months ago | File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html). |
| [gut](https://github.com/1set/gut) | 17 | 3 | 2019/10/05 | 7 months ago | Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links. |
| [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) | 14 | 3 | 2018/10/16 | 1 year ago | Copy files for humans. |
| [todotxt](https://github.com/1set/todotxt) | 8 | 2 | 2020/11/06 | 7 months ago | Go library for Gina Trapani's [*todo.txt*](http://todotxt.org/) files, supports parsing and manipulating of task lists in the [*todo.txt* format](https://github.com/todotxt/todo.txt). |

## Build Automation
        
*Libraries and tools helping with build automation.*

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [realize](https://github.com/oxequa/realize) | 4055 | 74 | 2016/07/12 | 1 month ago | Go build system with file watchers and live reload. Run, build and watch file changes with custom paths. |
| [task](https://github.com/go-task/task) | 3625 | 62 | 2017/02/27 | 1 day ago | simple "Make" alternative. |
| [mmake](https://github.com/tj/mmake) | 1577 | 28 | 2017/02/15 | 1 year ago | Modern Make. |
| [goyek](https://github.com/goyek/goyek) | 235 | 4 | 2020/10/11 | 3 days ago | Create build pipelines in Go. |
| [taskctl](https://github.com/taskctl/taskctl) | 114 | 6 | 2019/11/12 | 1 month ago | Concurrent task runner. |
| [1build](https://github.com/gopinath-langote/1build) | 97 | 7 | 2019/04/23 | 2 weeks ago | Command line tool to frictionlessly manage project-specific commands. |
| [taskflow](https://github.com/pellared/taskflow) | 63 | 2 | 2020/10/11 | 2 months ago | Create build pipelines in Go. |
| [gaper](https://github.com/maxcnunes/gaper) | 49 | 0 | 2018/06/16 | 1 year ago | Builds and restarts a Go project when it crashes or some watched file changes. |

# Tools
        
*Go software and plugins.*

## Code Analysis
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [lint](https://github.com/golang/lint) | 3897 | 104 | 2013/06/02 | 2 months ago | Golint is a linter for Go source code. |
| [errcheck](https://github.com/kisielk/errcheck) | 1705 | 25 | 2013/02/24 | 2 weeks ago | Errcheck is a program for checking for unchecked errors in Go programs. |
| [gcvis](https://github.com/davecheney/gcvis) | 1021 | 36 | 2014/07/10 | 2 years ago | Visualise Go program GC trace data in real time. |
| [go-critic](https://github.com/go-critic/go-critic) | 956 | 21 | 2018/05/05 | 1 week ago | source code linter that brings checks that are currently not implemented in other linters. |
| [php-parser](https://github.com/z7zmey/php-parser) | 809 | 28 | 2017/11/07 | 2 months ago | A Parser for PHP written in Go. |
| [goast-viewer](https://github.com/yuroyoro/goast-viewer) | 523 | 17 | 2014/06/30 | 2 years ago | Web based Golang AST visualizer. |
| [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) | 519 | 6 | 2019/04/19 | 7 minutes ago | An easy way to find outdated dependencies of your Go projects. |
| [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) | 472 | 12 | 2017/04/12 | 4 months ago | go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects. |
| [goplantuml](https://github.com/jfeliu007/goplantuml) | 443 | 13 | 2019/05/26 | 2 months ago | Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them. |
| [unconvert](https://github.com/mdempsky/unconvert) | 309 | 8 | 2016/02/19 | 1 year ago | Remove unnecessary type conversions from Go source. |
| [tickgit](https://github.com/augmentable-dev/tickgit) | 257 | 9 | 2019/10/12 | 1 year ago | CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author. |
| [dupl](https://github.com/mibk/dupl) | 248 | 8 | 2015/05/20 | 6 months ago | Tool for code clone detection. |
| [gostatus](https://github.com/shurcooL/gostatus) | 246 | 7 | 2013/11/27 | 2 years ago | Command line tool, shows the status of repositories that contain Go packages. |
| [golines](https://github.com/segmentio/golines) | 199 | 14 | 2019/10/01 | 17 hours ago | Formatter that automatically shortens long lines in Go code. |
| [apicompat](https://github.com/bradleyfalzon/apicompat) | 172 | 8 | 2016/07/10 | 4 years ago | Checks recent changes to a Go project for backwards incompatible changes. |
| [checkstyle](https://github.com/qiniu/checkstyle) | 115 | 13 | 2014/01/01 | 4 months ago | checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments. |
| [lint](https://github.com/surullabs/lint) | 66 | 5 | 2016/07/09 | 2 years ago | Run linters as part of go test. |
| [validate](https://github.com/mccoyst/validate) | 60 | 6 | 2013/11/22 | 5 years ago | Automatically validates struct fields with tags. |
| [go-outdated](https://github.com/firstrow/go-outdated) | 45 | 1 | 2015/06/29 | 2 years ago | Console application that displays outdated packages. |
| [blanket](https://github.com/verygoodsoftwarenotvirus/blanket) | 14 | 2 | 2017/09/04 | 3 years ago | tarp finds functions and methods without direct unit tests in Go source code. |

## Editor Plugins
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [vim-go](https://github.com/fatih/vim-go) | 13569 | 281 | 2014/03/24 | 2 weeks ago | Go development plugin for Vim. |
| [vscode-go](https://github.com/microsoft/vscode-go) | 5978 | 226 | 2015/10/14 | 1 year ago | Extension for Visual Studio Code (VS Code) which provides support for the Go language. |
| [gocode](https://github.com/nsf/gocode) | 4923 | 192 | 2010/07/05 | 4 months ago | Autocompletion daemon for the Go programming language. |
| [GoSublime](https://github.com/DisposaBoy/GoSublime) | 3406 | 118 | 2011/08/27 | 11 months ago | Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features. |
| [vscode-go](https://github.com/golang/vscode-go) | 1849 | 49 | 2020/03/06 | 2 days ago | Extension for Visual Studio Code (VS Code) which provides support for the Go language. |
| [go-plus](https://github.com/joefitzgerald/go-plus) | 1518 | 44 | 2014/03/13 | 2 months ago | Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting. |
| [go-mode.el](https://github.com/dominikh/go-mode.el) | 1171 | 54 | 2013/01/30 | 1 week ago | Go mode for GNU/Emacs. |
| [Watch](https://github.com/eaburns/Watch) | 186 | 14 | 2013/08/08 | 3 years ago | Runs a command in an acme win on file changes. |
| [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) | 88 | 5 | 2012/11/25 | 5 years ago | Vim plugin to highlight syntax errors on save. |
| [goimports-reviser](https://github.com/incu6us/goimports-reviser) | 59 | 2 | 2020/04/08 | 2 months ago | Formatting tool for imports. |
| [go-language-server](https://github.com/theia-ide/go-language-server) | 33 | 5 | 2017/11/21 | 2 years ago | A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol. |
| [gounit-vim](https://github.com/hexdigest/gounit-vim) | 22 | 2 | 2018/02/21 | 2 years ago | Vim plugin for generating Go tests based on the function's or method's signature. |
| [theia-go-extension](https://github.com/theia-ide/theia-go-extension) | 15 | 5 | 2017/11/30 | 2 years ago | Go language support for the Theia IDE. |

## Go Generate Tools
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gotests](https://github.com/cweill/gotests) | 3321 | 75 | 2016/01/19 | 1 month ago | Generate Go tests from your source code. |
| [genny](https://github.com/cheekybits/genny) | 1537 | 27 | 2014/10/27 | 1 month ago | Elegant generics for Go. |
| [re2dfa](https://github.com/opennota/re2dfa) | 185 | 9 | 2015/06/20 | 2 years ago | Transform regular expressions into finite state machines and output Go source code. |
| [xgen](https://github.com/xuri/xgen) | 101 | 10 | 2019/06/22 | 4 months ago | XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator. |
| [hasgo](https://github.com/DylanMeeus/hasgo) | 94 | 6 | 2019/05/16 | 2 months ago | Generate Haskell inspired functions for your slices. |
| [gocontracts](https://github.com/Parquery/gocontracts) | 72 | 8 | 2018/08/13 | 2 years ago | brings design-by-contract to Go by synchronizing the code with the documentation. |
| [gounit](https://github.com/hexdigest/gounit) | 52 | 5 | 2018/02/05 | 2 years ago | Generate Go tests using your own templates. |
| [generic](https://github.com/usk81/generic) | 39 | 2 | 2016/06/15 | 5 months ago | flexible data type for Go. |

## Go Tools
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-swagger](https://github.com/go-swagger/go-swagger) | 6551 | 124 | 2014/11/16 | 12 hours ago | Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API. |
| [OctoLinker](https://github.com/OctoLinker/OctoLinker) | 4758 | 89 | 2013/12/27 | 4 hours ago | Navigate through go files efficiently with the OctoLinker browser extension for GitHub. |
| [go-callvis](https://github.com/ofabry/go-callvis) | 3404 | 73 | 2016/09/03 | 1 month ago | Visualize call graph of your Go program using dot format. |
| [go-callvis](https://github.com/TrueFurby/go-callvis) | 2408 | 70 | 2016/09/03 | 1 year ago | Visualize call graph of your Go program using dot format. |
| [depth](https://github.com/KyleBanks/depth) | 613 | 13 | 2017/03/04 | 1 year ago | Visualize dependency trees of any package by analyzing imports. |
| [richgo](https://github.com/kyoh86/richgo) | 584 | 4 | 2017/01/04 | 1 month ago | Enrich `go test` outputs with text decorations. |
| [rts](https://github.com/galeone/rts) | 214 | 3 | 2016/04/04 | 1 year ago | RTS: response to struct. Generates Go structs from server responses. |
| [godbg](https://github.com/tylerwince/godbg) | 177 | 4 | 2019/01/23 | 2 years ago | Implementation of Rusts `dbg!` macro for quick and easy debugging during development. |
| [typex](https://github.com/dtgorski/typex) | 132 | 3 | 2020/03/24 | 5 months ago | Examine Go types and their transitive dependencies, alternatively export results as TypeScript value objects (or types) declaration. |
| [colorgo](https://github.com/songgao/colorgo) | 108 | 5 | 2013/02/14 | 11 months ago | Wrapper around `go` command for colorized `go build` output. |
| [gothanks](https://github.com/psampaz/gothanks) | 101 | 3 | 2019/11/10 | 4 months ago | GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers. |
| [igo](https://github.com/rocketlaunchr/igo) | 44 | 3 | 2018/11/17 | 1 year ago | Improved Go Syntax (transpiler) |
| [go-james](https://github.com/pieterclaerhout/go-james) | 43 | 2 | 2019/10/14 | 4 months ago | Go project skeleton creator, builds and tests your projects without the manual setup. |
| [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) | 38 | 2 | 2015/05/22 | 3 years ago | Bash completion for go and wgo. |
| [generator-go-lang](https://github.com/axelspringer/generator-go-lang) | 23 | 13 | 2017/09/13 | 1 year ago | A [Yeoman](http://yeoman.io) generator to get new Go projects started. |

## Software Packages
        
*Software written in Go.*

### DevOps Tools
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [kubernetes](https://github.com/kubernetes/kubernetes) | 78935 | 3274 | 2014/06/06 | 7 minutes ago | Container Cluster Manager from Google. |
| [moby](https://github.com/moby/moby) | 60623 | 3084 | 2013/01/18 | 4 minutes ago | Collaborative project for the container ecosystem to assemble container-based systems. |
| [traefik](https://github.com/traefik/traefik) | 34313 | 706 | 2015/09/13 | 12 minutes ago | Reverse proxy and load balancer with support for multiple backends. |
| [traefik](https://github.com/containous/traefik) | 30724 | 719 | 2015/09/13 | 10 months ago | Reverse proxy and load balancer with support for multiple backends. |
| [gitea](https://github.com/go-gitea/gitea) | 25388 | 483 | 2016/11/01 | 1 hour ago | Fork of Gogs, entirely community driven. |
| [vegeta](https://github.com/tsenart/vegeta) | 17672 | 322 | 2013/08/13 | 23 hours ago | HTTP load testing tool and library. It's over 9000! |
| [packer](https://github.com/hashicorp/packer) | 12978 | 494 | 2013/03/23 | 2 days ago | Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. |
| [hey](https://github.com/rakyll/hey) | 11524 | 178 | 2016/09/02 | 2 weeks ago | Hey is a tiny program that sends some load to a web application. |
| [webhook](https://github.com/adnanh/webhook) | 6697 | 149 | 2015/01/12 | 3 weeks ago | Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server. |
| [gvm](https://github.com/moovweb/gvm) | 6407 | 157 | 2011/12/03 | 2 weeks ago | GVM provides an interface to manage Go versions. |
| [gaia](https://github.com/gaia-pipeline/gaia) | 4399 | 104 | 2017/12/28 | 2 months ago | Build powerful pipelines in any programming language. |
| [gox](https://github.com/mitchellh/gox) | 4052 | 75 | 2013/11/17 | 4 months ago | Dead simple, no frills Go cross compile tool. |
| [bosun](https://github.com/bosun-monitor/bosun) | 3165 | 150 | 2013/11/15 | 2 weeks ago | Time Series Alerting Framework. |
| [bombardier](https://github.com/codesenberg/bombardier) | 2710 | 63 | 2016/05/29 | 19 hours ago | Fast cross-platform HTTP benchmarking tool. |
| [pomerium](https://github.com/pomerium/pomerium) | 2594 | 31 | 2019/01/01 | 35 minutes ago | Pomerium is an identity-aware access proxy. |
| [script](https://github.com/bitfield/script) | 1829 | 34 | 2019/04/20 | 4 months ago | Making it easy to write shell-like scripts in Go for DevOps and system administration tasks. |
| [fac](https://github.com/mkchoi212/fac) | 1722 | 32 | 2017/12/29 | 1 year ago | Command-line user interface to fix git merge conflicts. |
| [kala](https://github.com/ajvb/kala) | 1696 | 66 | 2015/03/19 | 1 month ago | Simplistic, modern, and performant job scheduler. |
| [goxc](https://github.com/laher/goxc) | 1669 | 51 | 2013/02/11 | 1 year ago | build tool for Go, with a focus on cross-compiling and packaging. |
| [statusok](https://github.com/sanathp/statusok) | 1498 | 51 | 2015/08/26 | 5 months ago | Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected. |
| [s3gof3r](https://github.com/rlmcpherson/s3gof3r) | 1100 | 32 | 2013/08/02 | 2 months ago | Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3. |
| [go-selfupdate](https://github.com/sanbornm/go-selfupdate) | 845 | 28 | 2013/11/13 | 5 months ago | Enable your Go applications to self update. |
| [s5cmd](https://github.com/peak/s5cmd) | 742 | 23 | 2016/11/16 | 9 hours ago | Blazing fast S3 and local filesystem execution tool. |
| [skm](https://github.com/TimothyYe/skm) | 694 | 20 | 2017/10/11 | 2 weeks ago | SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily! |
| [scaleway-cli](https://github.com/scaleway/scaleway-cli) | 677 | 34 | 2015/03/20 | 5 days ago | Manage BareMetal Servers from Command Line (as easily as with Docker). |
| [aurora](https://github.com/xuri/aurora) | 526 | 31 | 2016/10/09 | 1 month ago | Cross-platform web-based Beanstalkd queue server console. |
| [cassowary](https://github.com/rogerwelin/cassowary) | 520 | 5 | 2019/08/25 | 4 months ago | Modern cross-platform HTTP load-testing tool written in Go. |
| [govvv](https://github.com/ahmetb/govvv) | 489 | 10 | 2016/08/02 | 1 year ago | “go build” wrapper to easily add version information into Go binaries. |
| [utask](https://github.com/ovh/utask) | 459 | 29 | 2019/11/05 | 5 days ago | Automation engine that models and executes business processes declared in yaml. |
| [gonative](https://github.com/inconshreveable/gonative) | 328 | 8 | 2014/05/01 | 5 years ago | Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages. |
| [trubka](https://github.com/xitonix/trubka) | 300 | 14 | 2019/07/05 | 7 months ago | A CLI tool to manage and troubleshoot Apache Kafka clusters with the ability of generically publishing/consuming protocol buffer and plain text events to/from Kafka. |
| [mora](https://github.com/emicklei/mora) | 288 | 25 | 2013/07/12 | 3 months ago | REST server for accessing MongoDB documents and meta data. |
| [pewpew](https://github.com/bengadbois/pewpew) | 283 | 10 | 2016/10/12 | 3 days ago | Flexible HTTP command line stress tester. |
| [lstags](https://github.com/ivanilves/lstags) | 281 | 12 | 2017/08/15 | 8 months ago | Tool and API to sync Docker images across different registries. |
| [jenkins-cli](https://github.com/jenkins-zh/jenkins-cli) | 267 | 13 | 2019/06/21 | 4 days ago | Jenkins CLI allows you manage your Jenkins as an easy way. |
| [dogo](https://github.com/liudng/dogo) | 240 | 18 | 2014/11/19 | 2 years ago | Monitoring changes in the source file and automatically compile and run (restart). |
| [manssh](https://github.com/xwjdsh/manssh) | 227 | 4 | 2017/10/08 | 3 years ago | manssh is a command line tool for managing your ssh alias config easily. |
| [godbg](https://github.com/sirnewton01/godbg) | 224 | 18 | 2013/08/09 | 3 years ago | Web-based gdb front-end application. |
| [blast](https://github.com/dave/blast) | 199 | 5 | 2017/10/21 | 3 years ago | A simple tool for API load testing and batch jobs. |
| [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) | 192 | 8 | 2017/03/03 | 3 weeks ago | Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`. |
| [gobrew](https://github.com/cryptojuice/gobrew) | 182 | 5 | 2013/11/13 | 1 year ago | gobrew lets you easily switch between multiple versions of go. |
| [ostent](https://github.com/ostrost/ostent) | 172 | 7 | 2014/03/31 | 3 years ago | collects and displays system metrics and optionally relays to Graphite and/or InfluxDB. |
| [abbreviate](https://github.com/dnnrly/abbreviate) | 166 | 6 | 2018/11/23 | 1 week ago | abbreviate is a tool turning long strings in to shorter ones with configurable seperaters, for example to embed branch names in to deployment stack IDs. |
| [terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) | 157 | 9 | 2017/10/17 | 2 weeks ago | Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed. |
| [kcli](https://github.com/cswank/kcli) | 155 | 5 | 2017/03/25 | 1 year ago | Command line tool for inspecting kafka topics/partitions/messages. |
| [grapes](https://github.com/yaronsumel/grapes) | 152 | 6 | 2016/09/01 | 6 months ago | Lightweight tool designed to distribute commands over ssh with ease. |
| [winrm-cli](https://github.com/masterzen/winrm-cli) | 118 | 5 | 2016/05/23 | 1 year ago | Cli tool to remotely execute commands on Windows machines. |
| [dockerfile-generator](https://github.com/ozankasikci/dockerfile-generator) | 99 | 5 | 2019/08/14 | 1 year ago | A go library and an executable that produces valid Dockerfiles using various input channels. |
| [drone-scp](https://github.com/appleboy/drone-scp) | 83 | 3 | 2016/10/16 | 3 weeks ago | Copy files and artifacts via SSH using a binary, docker or Drone CI. |
| [go-furnace](https://github.com/go-furnace/go-furnace) | 82 | 2 | 2016/10/09 | 1 year ago | Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean. |
| [dropship](https://github.com/ChrisMcKenzie/dropship) | 54 | 3 | 2015/09/03 | 3 years ago | Tool for deploying code via cdn. |
| [s3-proxy](https://github.com/oxyno-zeta/s3-proxy) | 48 | 2 | 2019/09/22 | 3 days ago | S3 Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth). |
| [drone-jenkins](https://github.com/appleboy/drone-jenkins) | 31 | 3 | 2016/10/15 | 9 months ago | Trigger downstream Jenkins jobs using a binary, docker or Drone CI. |
| [rodent](https://github.com/alouche/rodent) | 31 | 2 | 2014/06/01 | 4 years ago | Rodent helps you manage Go versions, projects and track dependencies. |
| [awsenv](https://github.com/soniah/awsenv) | 27 | 2 | 2015/08/05 | 3 years ago | Small binary that loads Amazon (AWS) environment variables for a profile. |
| [lwc](https://github.com/timdp/lwc) | 25 | 3 | 2018/04/22 | 1 year ago | A live-updating version of the UNIX wc command. |
| [depcharge](https://github.com/centerorbit/depcharge) | 18 | 3 | 2018/07/25 | 1 year ago | Helps orchestrating the execution of commands across the many dependencies in larger projects. |
| [httpref](https://github.com/dnnrly/httpref) | 14 | 2 | 2020/01/10 | 1 week ago | httpref is a handy CLI reference for HTTP methods, status codes, headers, and TCP and UDP ports. |
| [sg](https://github.com/ChristopherRabotin/sg) | 6 | 1 | 2015/08/19 | 4 years ago | Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response. |
| [aptly-fork](https://github.com/smira/aptly-fork) | 4 | 0 | 2019/07/04 | 1 year ago | aptly is a Debian repository management tool. |

### Other Software
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [goreplay](https://github.com/buger/goreplay) | 14344 | 467 | 2013/05/30 | 13 hours ago | Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time. |
| [croc](https://github.com/schollz/croc) | 14158 | 219 | 2017/10/17 | 4 days ago | Easily and securely send files or folders from one computer to another. |
| [restic](https://github.com/restic/restic) | 13127 | 228 | 2014/04/27 | 1 day ago | De-duplicating backup program. |
| [seaweedfs](https://github.com/chrislusf/seaweedfs) | 12294 | 532 | 2014/07/14 | 8 hours ago | Fast, Simple and Scalable Distributed File System with O(1) disk seek. |
| [confd](https://github.com/kelseyhightower/confd) | 7524 | 255 | 2013/10/01 | 7 months ago | Manage local application configuration files using templates and data from etcd or consul. |
| [comcast](https://github.com/tylertreat/comcast) | 7001 | 152 | 2014/11/12 | 1 month ago | Simulate bad network connections. |
| [liteide](https://github.com/visualfc/liteide) | 6499 | 366 | 2012/11/19 | 2 weeks ago | LiteIDE is a simple, open source, cross-platform Go IDE. |
| [drive](https://github.com/odeke-em/drive) | 6062 | 191 | 2014/11/03 | 5 months ago | Google Drive client for the commandline. |
| [toxiproxy](https://github.com/Shopify/toxiproxy) | 5545 | 305 | 2014/09/04 | 1 week ago | Proxy to simulate network and system conditions for automated tests. |
| [nes](https://github.com/fogleman/nes) | 4792 | 146 | 2015/03/02 | 1 month ago | Nintendo Entertainment System (NES) emulator written in Go. |
| [duplicacy](https://github.com/gilbertchen/duplicacy) | 3743 | 92 | 2016/02/23 | 1 month ago | A cross-platform network and cloud backup tool based on the idea of lock-free deduplication. |
| [scc](https://github.com/boyter/scc) | 2609 | 24 | 2018/03/01 | 1 month ago | Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates. |
| [mylg](https://github.com/mehrdadrad/mylg) | 2495 | 113 | 2016/06/21 | 1 year ago | Command Line Network Diagnostic tool written in Go. |
| [goboy](https://github.com/Humpheh/goboy) | 2364 | 46 | 2017/08/20 | 11 months ago | Nintendo Game Boy Color emulator written in Go. |
| [sup](https://github.com/pressly/sup) | 2263 | 72 | 2015/02/23 | 1 month ago | Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers. |
| [lgo](https://github.com/yunabe/lgo) | 2184 | 49 | 2017/10/05 | 7 months ago | Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility. |
| [circuit](https://github.com/gocircuit/circuit) | 1902 | 138 | 2014/04/10 | 1 year ago | Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications. |
| [snap](https://github.com/intelsdi-x/snap) | 1793 | 145 | 2014/08/13 | 2 years ago | Powerful telemetry framework. |
| [borg](https://github.com/ok-borg/borg) | 1513 | 41 | 2016/09/10 | 3 years ago | Terminal based search engine for bash snippets. |
| [community](https://github.com/documize/community) | 1351 | 52 | 2016/04/29 | 3 months ago | Modern wiki software that integrates data from SaaS tools. |
| [Go-Package-Store](https://github.com/shurcooL/Go-Package-Store) | 886 | 21 | 2014/01/24 | 1 year ago | App that displays updates for the Go packages in your GOPATH. |
| [vflow](https://github.com/VerizonDigital/vflow) | 813 | 84 | 2017/02/24 | 3 months ago | High-performance, scalable and reliable IPFIX, sFlow and Netflow collector. |
| [peg](https://github.com/pointlander/peg) | 799 | 29 | 2010/04/25 | 2 weeks ago | Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. |
| [shell2http](https://github.com/msoap/shell2http) | 785 | 25 | 2015/03/11 | 1 week ago | Executing shell commands via http server (for prototyping or remote control). |
| [leaps](https://github.com/Jeffail/leaps) | 705 | 28 | 2014/06/19 | 4 months ago | Pair programming service using Operational Transforms. |
| [gfile](https://github.com/Antonito/gfile) | 620 | 12 | 2019/03/08 | 4 months ago | Securely transfer files between two computers, without any third party, over WebRTC. |
| [gebug](https://github.com/moshebe/gebug) | 547 | 5 | 2020/07/20 | 3 days ago | A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly. |
| [guora](https://github.com/meloalright/guora) | 537 | 15 | 2020/08/13 | 7 months ago | A self-hosted Quora like web application written in Go. |
| [gocc](https://github.com/goccmack/gocc) | 492 | 21 | 2015/06/05 | 2 months ago | Gocc is a compiler kit for Go written in Go. |
| [mockingjay-server](https://github.com/quii/mockingjay-server) | 492 | 9 | 2015/04/04 | 5 months ago | Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests. |
| [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) | 431 | 19 | 2015/10/08 | 1 year ago | Video streaming torrent client. |
| [ipe](https://github.com/dimiro1/ipe) | 325 | 18 | 2015/01/13 | 3 months ago | Open source Pusher server implementation compatible with Pusher client libraries written in GO. |
| [IDE](https://github.com/thestrukture/IDE) | 315 | 18 | 2017/09/09 | 3 months ago | Browser accessible IDE. Designed for Go with Go. |
| [wellington](https://github.com/wellington/wellington) | 297 | 13 | 2014/12/08 | 8 months ago | Sass project management tool, extends the language with sprite functions (like Compass). |
| [tcpprobe](https://github.com/mehrdadrad/tcpprobe) | 295 | 8 | 2020/10/26 | 4 months ago | TCP tool for network performance and path monitoring, including socket statistics. |
| [cherry](https://github.com/rafael-santiago/cherry) | 244 | 12 | 2015/10/24 | 4 years ago | Tiny webchat server in Go. |
| [woke](https://github.com/get-woke/woke) | 235 | 7 | 2020/08/31 | 1 day ago | Detect non-inclusive language in your source code. |
| [orange-cat](https://github.com/utatti/orange-cat) | 182 | 5 | 2014/11/01 | 2 years ago | Markdown previewer written in Go. |
| [orange-cat](https://github.com/hatashiro/orange-cat) | 182 | 5 | 2014/11/01 | 2 years ago | Markdown previewer written in Go. |
| [joincap](https://github.com/assafmo/joincap) | 164 | 7 | 2018/05/31 | 3 months ago | Command-line utility for merging multiple pcap files together. |
| [orbit](https://github.com/gulien/orbit) | 154 | 9 | 2017/05/13 | 5 months ago | A simple tool for running commands and generating files from templates. |
| [vaku](https://github.com/lingrino/vaku) | 118 | 3 | 2018/04/24 | 3 days ago | CLI & API for folder-based functions in Vault like copy, move, and search. |
| [dp](https://github.com/scryinfo/dp) | 83 | 10 | 2018/12/12 | 2 weeks ago | Through SDK for data exchange with blockchain, developers can get easy access to DAPP development. |
| [boxed](https://github.com/tejo/boxed) | 75 | 3 | 2015/04/18 | 2 years ago | Dropbox based blog engine. |
| [naclpipe](https://github.com/unix4fun/naclpipe) | 21 | 6 | 2015/05/05 | 2 years ago | Simple NaCL EC25519 based crypto pipe tool written in Go. |
| [term-quiz](https://github.com/crazcalm/term-quiz) | 18 | 1 | 2017/12/26 | 2 years ago | Quizzes for your terminal. |
| [snitch](https://github.com/lucasgomide/snitch) | 15 | 1 | 2017/04/06 | 3 years ago | Simple way to notify your team and many tools when someone has deployed any application via Tsuru. |
| [GoDocTooltip](https://github.com/diankong/GoDocTooltip) | 14 | 3 | 2016/01/21 | 5 months ago | Chrome extension for Go Doc sites, which shows function description as tooltip at function list. |

# Resources
        
*Where to discover new Go libraries.*

## Benchmarks
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) | 1504 | 59 | 2013/12/16 | 1 month ago | Go HTTP request router benchmark and comparison. |
| [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) | 1504 | 84 | 2016/04/06 | 2 weeks ago | Go web framework benchmark. |
| [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) | 1174 | 37 | 2013/01/18 | 3 weeks ago | Benchmarks of Go serialization methods. |
| [skynet](https://github.com/atemerev/skynet) | 989 | 49 | 2016/02/14 | 1 month ago | Skynet 1M threads microbenchmark. |
| [speedtest-resize](https://github.com/fawick/speedtest-resize) | 210 | 7 | 2013/09/16 | 8 months ago | Compare various Image resize algorithms for the Go language. |
| [go-benchmarks](https://github.com/tylertreat/go-benchmarks) | 139 | 11 | 2016/02/25 | 5 years ago | Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches. |
| [gospeed](https://github.com/feyeleanor/gospeed) | 106 | 7 | 2011/05/23 | 4 months ago | Go micro-benchmarks for calculating the speed of language constructs. |
| [autobench](https://github.com/davecheney/autobench) | 90 | 9 | 2013/03/28 | 7 years ago | Framework to compare the performance between different Go versions. |
| [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) | 59 | 5 | 2014/09/24 | 3 years ago | Collection of benchmarks for popular Go database/SQL utilities. |
| [gocostmodel](https://github.com/mna/gocostmodel) | 58 | 6 | 2014/12/19 | 1 month ago | Benchmarks of common basic operations for the Go language. |
| [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) | 21 | 1 | 2017/01/24 | 4 years ago | Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results. |
| [kvbench](https://github.com/jimrobinson/kvbench) | 20 | 1 | 2014/04/15 | 1 year ago | Key/Value database benchmark. |
| [go-json-benchmark](https://github.com/zerosnake0/go-json-benchmark) | 4 | 2 | 2019/11/10 | 9 months ago | Go JSON benchmark. |

## Conferences
        

## E-Books
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [GoBooks](https://github.com/dariubs/GoBooks) | 9629 | 574 | 2015/05/05 | 9 hours ago | A curated list of Go books. |
| [The-Golang-Standard-Library-by-Example](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example) | 7908 | 593 | 2013/04/14 | 1 month ago | Golang标准库。对于程序员而言，标准库与语言本身同样重要，它好比一个百宝箱，能为各种常见的任务提供完美的解决方案。以示例驱动的方式讲解Golang的标准库。 |
| [gosuccinctly](https://github.com/thedevsir/gosuccinctly) | 18 | 4 | 2018/09/02 | 2 years ago | in Persian. |

## Gophers
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [gophers](https://github.com/ashleymcnamara/gophers) | 2463 | 95 | 2017/02/15 | 2 years ago | Gopher artworks by Ashley McNamara. |
| [gophers](https://github.com/egonelbre/gophers) | 2399 | 57 | 2015/06/03 | 1 year ago | Free gophers. |
| [free-gophers-pack](https://github.com/MariaLetta/free-gophers-pack) | 2257 | 60 | 2019/04/02 | 1 year ago | Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster. |
| [gophericons](https://github.com/shalakhin/gophericons) | 589 | 20 | 2015/08/22 | 3 years ago | 34 gopher images for Go developers community |
| [gopherize.me](https://github.com/matryer/gopherize.me) | 507 | 8 | 2017/01/25 | 10 months ago | Gopherize yourself. |
| [gopher-stickers](https://github.com/tenntenn/gopher-stickers) | 505 | 14 | 2014/11/09 | 1 year ago | gopher stickers |
| [gopher-vector](https://github.com/golang-samples/gopher-vector) | 382 | 13 | 2013/03/31 | 5 years ago | Vector data of gopher |
| [go-gopher](https://github.com/sillecelik/go-gopher) | 96 | 0 | 2018/03/28 | 2 months ago | Gopher amigurumi toy pattern. |
| [gopher-logos](https://github.com/GolangUA/gopher-logos) | 92 | 9 | 2017/07/27 | 2 weeks ago | adorable gopher logos. |
| [gophers](https://github.com/rogeralsing/gophers) | 54 | 2 | 2017/01/28 | 11 months ago | random gopher graphics. |
| [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) | 40 | 1 | 2014/09/03 | 3 years ago | Go gopher Vector Data [.ai, .svg]. |

## Meetups
        
*Add the group of your city/country here (send **PR**)*

## Twitter
        

## Websites
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) | 27799 | 1735 | 2014/07/08 | 2 weeks ago | List of other amazingly awesome lists. |
| [awesome-remote-job](https://github.com/lukasz-madon/awesome-remote-job) | 20660 | 1002 | 2015/01/02 | 1 day ago | Curated list of awesome remote jobs. A lot of them are looking for Go hackers. |
| [golang-graphics](https://github.com/mholt/golang-graphics) | 140 | 8 | 2014/03/24 | 5 years ago | Collection of Go images, graphics, and art. |
| [gocryforhelp](https://github.com/ninedraft/gocryforhelp) | 38 | 11 | 2016/05/09 | 3 years ago | Collection of Go projects that needs help. Good place to start your open-source way in Go. |

### Tutorials
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [build-web-application-with-golang](https://github.com/astaxie/build-web-application-with-golang) | 38106 | 2470 | 2012/08/02 | 1 week ago | Golang ebook intro how to build a web app with golang. |
| [go-patterns](https://github.com/tmrts/go-patterns) | 15525 | 601 | 2015/12/14 | 1 month ago | Curated list of Go design patterns, recipes and idioms. |
| [learn-go-with-tests](https://github.com/quii/learn-go-with-tests) | 14652 | 309 | 2018/03/02 | 1 day ago | Learn Go with test-driven development. |
| [golang-cheat-sheet](https://github.com/a8m/golang-cheat-sheet) | 5602 | 191 | 2014/02/13 | 2 months ago | Go's reference card. |
| [golang-for-nodejs-developers](https://github.com/miguelmota/golang-for-nodejs-developers) | 2453 | 40 | 2019/01/03 | 2 months ago | Examples of Golang compared to Node.js for learning. |
| [working-with-go](https://github.com/mkaz/working-with-go) | 1161 | 49 | 2014/05/04 | 1 year ago | Intro to go for experienced programmers. |
| [ethereum-development-with-go-book](https://github.com/miguelmota/ethereum-development-with-go-book) | 864 | 46 | 2018/05/16 | 2 weeks ago | A little e-book on Ethereum Development with Go. |
| [goapp](https://github.com/bnkamalesh/goapp) | 261 | 9 | 2020/07/04 | 6 months ago | An opinionated guideline to structure & develop a Go web application/service. |
| [design-patterns](https://github.com/shubhamzanwar/design-patterns) | 56 | 4 | 2020/09/24 | 8 months ago | Collection of programming design patterns implemented in Go. |

## Style Guides
        

| Go_repository    | Stars      | Watchers   | Created_at | Latest_push | Description |
| :--------- | ---------:| ---------:|:---------:|:---------:|:--------- |
| [go-styleguide](https://github.com/bahlo/go-styleguide) | 1094 | 29 | 2017/07/29 | 1 month ago | 🏆 Opinionated Styleguide for the Go language |

> 该项目源码[Awesome Go Analysis](https://github.com/plholx/awesome-go-analysis)
> 更专业的go开源项目分析请移步 [Awesome Go](https://go.libhunt.com/)
