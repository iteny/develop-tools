Awesome Go Build Status Awesome Join the chat at https://gitter.im/avelino/awesome-go
A curated list of awesome Go frameworks, libraries and software. Inspired by awesome-python.

Contributing

Please take a quick gander at the contribution guidelines first. Thanks to all contributors; you rock!

If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!

Contents

Awesome Go

Audio & Music
Authentication & OAuth
Command Line
Configuration
Continuous Integration
CSS Preprocessors
Data Structures
Database
Database Drivers
Date & Time
Distributed Systems
Email
Embeddable Scripting Languages
Financial
Forms
Game Development
Generation & Generics
Go Compilers
Goroutines
GUI
Hardware
Images
Logging
Machine Learning
Messaging
Miscellaneous
Natural Language Processing
Networking
OpenGL
ORM
Package Management
Query Language
Resource Embedding
Science and Data Analysis
Security
Serialization
Template Engines
Testing
Text Processing
Third-party APIs
Utilities
Validation
Version Control
Video
Web Frameworks
Middlewares
Actual middlewares
Libraries for creating HTTP middlewares
Windows
Tools

Code Analysis
Editor Plugins
Go Tools
Software Packages
DevOps Tools
Other Software
Server Applications

Resources

Benchmarks
Conferences
E-Books
Twitter
Websites
Tutorials
Audio/Music

Libraries for manipulating audio.

flac - A native Go FLAC decoder.
flac - A native Go FLAC decoder.
go-sox - libsox bindings for go.
go_mediainfo - libmediainfo bindings for go.
mix - Sequence-based Go-native audio mixer for music apps.
mp3 - A native Go MP# decoder.
music-theory - Music theory models in Go.
PortAudio - Go bindings for the PortAudio audio I/O library.
portmidi - Go bindings for PortMidi.
taglib - Go bindings for taglib.
vorbis - A "native" Go Vorbis decoder (uses CGO, but has no dependencies).
waveform - Go package capable of generating waveform images from audio streams.
Authentication & OAuth

Libraries for implementing authentications schemes.

authboss - A modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time.
Go-AWS-Auth - AWS (Amazon Web Services) request signing library.
go-jose - A fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.
go.auth - Authentication API for Go web applications.
gologin - chainable handlers for login with OAuth1 and OAuth2 authentication providers.
gorbac - provides a lightweight role-based access control (RBAC) implementation in Golang.
goth - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple provides out of the box.
httpauth - HTTP Authentication middleware.
jwt-go - Golang implementation of JSON Web Tokens (JWT).
oauth2 - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support.
osin - Golang OAuth2 server library.
permissions2 - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt.
yubigo - a Yubikey client package that provides a simple API to integrate the Yubico Yubikey into a go application.
Command Line

Standard CLI

Libraries for building standard or basic Command Line applications

cli - A feature-rich and easy to use command-line package based on golang tag
cli-init - The easy way to start building Golang command line application.
climax - An alternative CLI with "human face", in spirit of Go command
cobra - A Commander for modern Go CLI interactions
docopt.go - A command-line arguments parser that will make you smile.
go-flags - go command line option parser
kingpin - A command line and flag parser supporting sub commands.
liner - A Go readline-like library for command-line interfaces.
mitchellh/cli - A Go library for implementing command-line interfaces.
mow.cli - A Go library for building CLI applications with sophisticated flag and argument parsing and validation.
readline - A pure golang implementation that provide most of features in GNU-Readline under MIT license.
ukautz/clif - A small command line interface framework.
urfave/cli - A simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).
wlog - A simple logging interface that supports cross-platform color and concurrency.
wmenu - An easy to use menu structure for cli applications that prompts users to make choices.
Advanced Console UIs

Libraries for building Console Applications and Console User Interfaces

chalk - Intuitive package for prettifying terminal/console output.
color - Versatile package for colored terminal output.
colourize - Go library for ANSI colour text in terminals.
go-colortext - Go library for color output in terminals.
gocui - Minimalist Go library aimed at creating Console User Interfaces.
gommon/color - Style terminal text.
termbox-go - Termbox is a library for creating cross-platform text-based interfaces.
termtables - A Go port of the Ruby library terminal-tables for simple ASCII table generation as well as providing markdown and HTML output
termui - Go terminal dashboard based on termbox-go and inspired by blessed-contrib.
uilive - A library for updating terminal output in realtime.
uiprogress - A flexible library to render progress bars in terminal applications.
uitable - A library to improve readability in terminal apps using tabular data.
Configuration

Libraries for configuration parsing

config - JSON or YAML configuration wrapper with environment variables and flags parsing.
configure - Provides configuration through multiple sources, including JSON, flags and environment variables.
env - Parse environment variables to Go structs (with defaults).
envcfg - Un-marshaling environment variables to Go structs.
envconf - Configuration from environment
envconfig - Read your configuration from environment variables.
gcfg - read INI-style configuration files into Go structs; supports user-defined types and subsections
gofigure - Go application configuration made easy
ingo - Flags persisted in an ini-like config file
ini - Go package for read and write INI files
mini - A golang package for parsing ini-style configuration files
store - A lightweight configuration manager for Go
viper - Go configuration with fangs
Continuous Integration

Tools for help with continuous integration

drone - Drone is a Continuous Integration platform built on Docker, written in Go
goveralls - Go integration for Coveralls.io continuous code coverage tracking system.
overalls - Multi-Package go project coverprofile for tools like goveralls
CSS Preprocessors

Libraries for preprocessing CSS files

c6 - High performance SASS compatible-implementation compiler written in Go
gcss - Pure Go CSS Preprocessor.
go-libsass - Go wrapper to the 100% Sass compatible libsass project.
Data Structures

Generic datastructures and algorithms in Go.

binpacker - Binary packer and unpacker helps user build custom binary stream.
bitset - Go package implementing bitsets.
bloom - Bloom filters implemented in Go.
boomfilters - probabilistic data structures for processing continuous, unbounded streams
count-min-log - A Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory).
cuckoofilter - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go.
encoding - Integer Compression Libraries for Go.
go-adaptive-radix-tree - A Go implementation of Adaptive Radix Tree.
go-datastructures - a collection of useful, performant, and thread-safe data structures
go-geoindex - In-memory geo index.
golang-set - Thread-Safe and Non-Thread-Safe high-performance sets for Go.
goskiplist - A skip list implementation in Go.
mafsa - MA-FSA implementation with Minimal Perfect Hashing
roaring - Go package implementing compressed bitsets.
skiplist - Skiplist implementation in Go
trie - Trie implementation in Go
ttlcache - An in-memory LRU string-interface{} map with expiration for golang
willf/bloom - Go package implementing Bloom filters.
Database

Databases implemented in Go.

bolt - A low-level key/value database for Go.
cache2go - An in-memory key:value cache which supports automatic invalidation based on timeouts.
cockroach - A Scalable, Geo-Replicated, Transactional Datastore
couchcache - A RESTful caching micro-service backed by Couchbase server.
dgraph - Scalable, Distributed, Low Latency, High Throughput Graph Database.
diskv - A home-grown disk-backed key-value store.
forestdb - Go bindings for ForestDB.
GCache - Cache library with support for expirable Cache, LFU, LRU and ARC.
geocache - An in-memory cache that is suitable for geolocation based applications.
go-cache - An in-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
goleveldb - An implementation of the LevelDB key/value database in the Go.
groupcache - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
influxdb - Scalable datastore for metrics, events, and real-time analytics
ledisdb - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
levigo - Levigo is a Go wrapper for LevelDB.
prometheus - Monitoring system and time series database.
rqlite - Replicated SQLite, using Raft consensus.
tidb - TiDB is a distributed SQL database. Inspired by the design of Google F1.
tiedot - Your NoSQL database powered by Golang.
Tile38 - A geolocation DB with spatial index and realtime geofencing.
Database tools.

go-mysql - A go toolset to handle MySQL protocol and replication.
go-mysql-elasticsearch - Sync your MySQL data into Elasticsearch automatically.
goose - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.
kingshard - kingshard is a high performance proxy for MySQL powered by Golang.
migrate - Database migration handling in Golang support MySQL,PostgreSQL,Cassandra and SQLite.
myreplication - MySql binary log replication listener. Support statement and row based replication.
orchestrator - MySQL replication topology manager & visualizer
pgweb - A web-based PostgreSQL database browser
pravasan - Simple Migration tool - currently for MySQL but planning to support soon for Postgres, SQLite, MongoDB, etc.,
sql-migrate - Database migration tool. Allows embedding migrations into the application using go-bindata.
vitess - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.
SQL query builder, libraries for building and using SQL.

dat - Go Postgres Data Access Toolkit
Dotsql - Go library that helps you keep sql files in one place and use it with ease.
goqu - An idiomatic SQL builder and query library.
igor - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.
ozzo-dbx - Powerful data retrieval methods as well as DB-agnostic query building capabilities.
scaneo - Generate Go code to convert database rows into arbitrary structs.
sqrl - SQL query builder, fork of Squirrel with improved performance.
Squirrel - Go library that helps you build SQL queries.
xo - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.
Database Drivers

Libraries for connecting and operating databases.

Relational Databases

firebirdsql - Firebird RDBMS SQL driver for Go
go-adodb - Microsoft ActiveX Object DataBase driver for go that using database/sql.
go-bqstreamer - BigQuery fast and concurrent stream insert.
go-mssqldb - Microsoft MSSQL driver prototype in go language.
go-oci8 - Oracle driver for go that using database/sql.
go-sql-driver/mysql - MySQL driver for Go.
go-sqlite3 - SQLite3 driver for go that using database/sql.
gofreetds Microsoft MSSQL driver. Go wrapper over FreeTDS.
pgx - PostgreSQL driver supporting features beyond those exposed by database/sql.
pq - Pure Go Postgres driver for database/sql.
NoSQL Databases

aerospike-client-go - Aerospike client in Go language.
arangolite - Lightweight golang driver for ArangoDB.
cayley - A graph database with support for multiple backends.
dynago - Dynago is a principle of least surprise client for DynamoDB
go-couchbase - Couchbase client in Go
go-couchdb - Yet another CouchDB HTTP API wrapper for Go
gocb - Official Couchbase Go SDK
gocql - A Go language driver for Apache Cassandra.
gomemcache - memcache client library for the Go programming language.
gorethink - Go language driver for RethinkDB
mgo - MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.
neo4j - Neo4j Rest API Bindings for Golang
Neo4j-GO - Neo4j REST Client in golang.
neoism - Neo4j client for Golang
redigo - Redigo is a Go client for the Redis database.
redis - Redis client for Golang
redis - A simple, powerful Redis client for Go.
redis - Redis-protocol compatible TCP servers/services.
Search and Analytic Databases

bleve - A modern text indexing library for go.
elastic - Elasticsearch client for Google Go.
elastigo - A Elasticsearch client library.
goes - A library to interact with Elasticsearch.
skizze - A probabilistic data-structures service and storage.
Date & Time

Libraries for working with dates and times.

durafmt - A time duration formatting library for Go.
go-persian-calendar - The implementation of the Persian (Solar Hijri) Calendar in Go (golang).
goweek - Library for working with week entity in golang.
now - Now is a time toolkit for golang.
NullTime - Nullable time.Time
timeutil - Useful extensions (Timedelta, Strftime, ...) to the golang's time package.
Distributed Systems

Packages that help with building Distributed Systems.

celeriac - A library for adding support for interacting and monitoring Celery workers, tasks and events in Go
flowgraph - MPI-style ready-send coordination layer.
glow - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go.
go-jump - A port of Google's "Jump" Consistent Hash function.
gorpc - Simple, fast and scalable RPC library for high load.
grpc-go - The Go language implementation of gRPC. HTTP/2 based RPC.
micro - A pluggable microservice toolkit and distributed systems platform.
NATS - A lightweight, high performance messaging system for microservices, IoT, and cloud native systems.
raft - Golang implementation of the Raft consensus protocol, by HashiCorp.
sleuth - A library for master-less p2p auto-discovery and RPC between HTTP services (using ZeroMQ).
torrent - BitTorrent client package.
dht - BitTorrent Kademlia DHT implementation.
go-peerflix - Video streaming torrent client.
Email

Libraries that implement email creation and sending

douceur - CSS inliner for your HTML emails.
email - A robust and flexible email library for Go.
go-dkim - A DKIM library, to sign & verify email.
Gomail - Gomail is a very simple and powerful package to send emails.
Hectane - Lightweight SMTP client providing an HTTP API
MailHog - Email and SMTP testing with web and API interface
SendGrid - SendGrid's Go library for sending email
smtp - SMTP server protocol state machine
Embeddable Scripting Languages

Embedding other languages inside your go code

agora - Dynamically typed, embeddable programming language in Go
anko - Scriptable interpreter written in Go
gisp - Simple LISP in Go
go-duktape - Duktape JavaScript engine bindings for Go
go-lua - A port of the Lua 5.2 VM to pure Go
go-php - PHP bindings for Go
go-python - naive go bindings to the CPython C-API
golua - Go bindings for Lua C API
gopher-lua - a Lua 5.1 VM and compiler written in Go
otto - A JavaScript interpreter written in Go
purl - Perl 5.18.2 embedded in Go
Financial

Packages for accounting and finance

accounting - money and currency formatting for golang
decimal - Arbitrary-precision fixed-point decimal numbers
vat - VAT number validation & EU VAT rates
Forms

Libraries for working with forms.

bind - Bind form data to any Go values
binding - Binds form and JSON data from net/http Request to struct.
conform - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags.
form - Decodes url.Values into struct values and Encodes struct values into url.Values. Dual Array and Full map support.
formam - decode form's values into a struct.
forms - A framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files.
gorilla/csrf - CSRF protection for Go web applications & services.
nosurf - A CSRF protection middleware for Go.
Game Development

Awesome game development libraries.

Ebiten - A simple SNES-like 2D game library in Go
engo - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm.
GarageEngine - 2d game engine written in Go working on OpenGL.
glm - A performance oriented vector, matrix, geometry library.
glop - Glop (Game Library Of Power) is a fairly simple cross-platform game library.
go-astar - Go implementation of the A* path finding algorithm
go-collada - Go package for working with the Collada file format.
go-sdl2 - Go bindings for the Simple DirectMedia Layer.
go3d - A performance oriented 2D/3D math package for Go
gonet - A game server skeleton implemented with golang
Leaf - A lightweight game server framework
lux - A 3D physically based rendering engine.
math - A float32 native version of standard library math.
termloop - Terminal-based game engine for Go, built on top of Termbox
tornago - A 3D rigid body physics engine in pure Go.
Generation & Generics

Tools to enhance the language with features like generics via code generation

gen - Code generation tool for ‘generics’-like functionality.
go-linq - .NET LINQ-like query methods for Go.
interfaces - Command line tool for generating interface definitions.
pkgreflect - A Go preprocessor for package scoped reflection.
Go Compilers

Tools for compiling Go to other languages

gopherjs - A compiler from Go to JavaScript.
llgo - LLVM-based compiler for Go.
tardisgo - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler.
Goroutines

Tools for managing and working with Goroutines

grpool - Lightweight Goroutine pool.
pool - a limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation.
tunny - A goroutine pool for golang.
GUI

Libraries for building GUI Applications

go-gtk - Go bindings for GTK
go-qml - QML support for the Go language
goqt - Golang bindings to the Qt cross-platform application framework.
gosx-notifier - OSX Desktop Notifications library for Go.
gotk3 - Go bindings for GTK3.
sciter - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development.
systray - Cross platform Go library to place an icon and menu in the notification area
trayhost - Cross-platform Go library to place an icon in the host operating system's taskbar.
ui - Platform-native GUI library for Go.
walk - Windows application library kit for Go.
Hardware

Libraries, tools, and tutorials for interacting with hardware.

See go-hardware for a comprehensive list.

Images

Libraries for manipulating images.

bimg - Small package for fast and efficient image processing using libvips
geopattern - Create beautiful generative image patterns from a string.
gift - Package of image processing filters.
go-cairo - Go binding for the cairo graphics library.
go-gd - Go binding for GD library
go-nude - Nudity detection with Go.
go-opencv - Go bindings for OpenCV.
go-webcolors - Port of webcolors library from Python to Go.
imagick - Go binding to ImageMagick's MagickWand C API.
imaginary - Fast and simple HTTP microservice for image resizing
imaging - Simple Go image processing package.
img - A selection of image manipulation tools.
mpo - A decoder and conversion tool for MPO 3D Photos.
picfit - An image resizing server written in Go
resize - Image resizing for the Go with common interpolation methods.
rez - Image resizing in pure Go and SIMD.
smartcrop - Finds good crops for arbitrary images and crop sizes
svgo - Go Language Library for SVG generation.
tga - Package tga is a TARGA image format decoder/encoder.
Logging

Libraries for generating and working with log files.

glog - Leveled execution logs for Go.
go-log - Log lib supports level and multi handlers.
go-log - A log4j implementation in Go.
go-logger - Simple logger of Go Programs, with level handlers.
gologger - Simple easy to use log lib for go, logs in Colored Cosole, Simple Console, File or Elasticsearch.
log - Structured logging package for Go.
log - Simple, configurable and scalable Structured Logging for Go.
log-voyage - Full-featured logging saas written in golang.
log15 - Simple, powerful logging for Go
logex - An golang log lib, supports tracking and level, wrap by standard log lib
logger - Minimalistic logging library for Go.
logrus - a structured logger for Go.
logrusly - logrus plug-in to send errors to a Loggly.
logutils - Utilities for slightly better logging in Go (Golang) extending the standard logger.
logxi - A 12-factor app logger that is fast and makes you happy.
lumberjack - Simple rolling logger, implements io.WriteCloser.
mlog - A simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.
ozzo-log - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).
seelog - logging functionality with flexible dispatching, filtering, and formatting.
slf - The Structured Logging Facade (SLF) for Go (like SLF4J but structured and for Go)
slog - The reference implementation of the Structured Logging Facade (SLF) for Go
stdlog - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.
tail - A Go package striving to emulate the features of the BSD tail program.
xlog - A structured logger for net/context aware HTTP handlers with flexible dispatching.
zap - Fast, structured, leveled logging in Go.
Machine Learning

Libraries for Machine Learning.

bayesian - Naive Bayesian Classification for Golang.
CloudForest - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go.
gago - Multi-population, flexible, parallel genetic algorithm.
go-fann - Go bindings for Fast Artificial Neural Networks(FANN) library.
go-galib - Genetic Algorithms library written in Go / golang
go-pr - Pattern recognition package in Go lang.
gobrain - Neural Networks written in go
godist - Various probability distributions, and associated methods.
goga - Genetic algorithm library for Go.
GoLearn - General Machine Learning library for Go.
golinear - liblinear bindings for Go
goml - On-line Machine Learning in Go
goRecommend - Recommendation Algorithms library written in Go.
libsvm - libsvm golang version derived work based on LIBSVM 3.14.
mlgo - This project aims to provide minimalistic machine learning algorithms in Go.
neural-go - A multilayer perceptron network implemented in Go, with training via backpropagation.
probab - Probability distribution functions. Bayesian inference. Written in pure Go.
regommend - Recommendation & collaborative filtering engine
shield - Bayesian text classifier with flexible tokenizers and storage backends for Go
Messaging

Libraries that implement messaging systems

Centrifugo - Real-time messaging (Websockets or SockJS) server in Go.
dbus - Native Go bindings for D-Bus.
emitter - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins.
EventBus - The lightweight event bus with async compatibility.
go-longpoll - PubSub with long polling.
go-notify - Native implementation of the freedesktop notification spec.
go-nsq - the official Go package for NSQ
gopush-cluster - gopush-cluster is a go push server cluster.
gorush - A push notification server using APNs2 and google GCM.
machinery - An asynchronous task queue/job queue based on distributed message passing.
mangos - Pure go implementation of the Nanomsg ("Scalable Protocols") with transport interoperability.
NATS Go Client - A lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library.
oplog - A generic oplog/replication system for REST APIs
pubsub - A simple pubsub package for go.
sarama - A Go library for Apache Kafka.
Uniqush-Push - A redis backed unified push service for server-side notifications to mobile devices.
zmq4 - A Go interface to ZeroMQ version 4. Also available for version 3 and version 2.
Miscellaneous

These libraries were placed here because none of the other categories seemed to fit

afero - A FileSystem Abstraction System for Go.
archiver - Library and command for making and extracting .zip and .tar.gz archives
autoflags - Go package to automatically define command line flags from struct fields.
banner - Add beautiful banners into your Go applications.
browscap_go - GoLang Library for Browser Capabilities Project.
datacounter - Go counters for readers/writer/http.ResponseWriter.
go-chat-bot - IRC, Slack & Telegram bot written in Go.
go-commons-pool - A generic object pool for Golang.
go-multierror - A Go (golang) package for representing a list of errors as a single error.
go-shortid - Distributed generation of super short, unique, non-sequential, URL friendly IDs.
gopsutil - A cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).
gosms - Your own local SMS gateway in Go that can be used to send SMS
gountries - A package that exposes country and subdivision data.
health - A Easy to use, extensible health check library.
jobs - A persistent and flexible background jobs library.
margelet - A framework for building Telegram bots.
notify - File system event notification library with simple API, similar to os/signal.
secdl - Lighttpd ModSecDownload algorithm ported to go to secure download urls.
stats - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...
werr - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called.
xkg - X Keyboard Grabber
xstrings - A collection of useful string functions ported from other languages.
Natural Language Processing

Libraries for working with human languages.

dpar - Transition-based statistical dependency parser.
go-eco - Similarity, dissimilarity and distance matrices; diversity, equitability and inequality measures; species richness estimators; coenocline models.
go-i18n - A package and an accompanying tool to work with localized text.
go-nlp - Utilities for working with discrete probability distributions and other tools useful for doing NLP work.
go-stem - Implementation of the porter stemming algorithm.
go2vec - Reader and utility functions for word2vec embeddings.
gojieba - This is a Go implementation of jieba which a Chinese word splitting algorithm.
golibstemmer - Go bindings for the snowball libstemmer library including porter 2
gounidecode - Unicode transliterator (also known as unidecode) for Go
icu - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1.
libtextcat - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2.
MMSEGO - This is a GO implementation of MMSEG which a Chinese word splitting algorithm.
paicehusk - Golang implementation of the Paice/Husk Stemming Algorithm
porter - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm.
porter2 - Really fast Porter 2 stemmer.
segment - A Go library for performing Unicode Text Segmentation as described in Unicode Standard Annex #29
sentences - A sentence tokenizer: converts text into a list of sentences.
snowball - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality Snowball native.
stemmer - Stemmer packages for Go programming language. Includes English and German stemmers.
textcat - A Go package for n-gram based text categorization, with support for utf-8 and raw text
Networking

Libraries for working with various layers of the network

arp - Package arp implements the ARP protocol, as described in RFC 826.
buffstreams - Streaming protocolbuffer data over TCP made easy
canopus - CoAP Client/Server implementation (RFC 7252)
dhcp6 - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315.
dns - Go library for working with DNS
ether - A cross-platform Go package for sending and receiving ethernet frames.
ethernet - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags.
fasthttp - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http
ftp - Package ftp implements a FTP client as described in RFC 959.
go-getter - A Go library for downloading files or directories from various sources using a URL.
go-stun - A go implementation of the STUN client (RFC 3489 and RFC 5389).
golibwireshark - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data.
gopacket - A Go library for packet processing with libpcap bindings
gopcap - A Go wrapper for libpcap
goshark - Package goshark use tshark to decode IP packet and create data struct to analyse packet.
gosnmp - Native Go library for performing SNMP actions
gotcp - A Go package for quickly writing tcp applications
grab - Go package for managing file downloads
graval - An experimental FTP server framework.
kcp-go - KCP - A Fast and Reliable ARQ Protocol.
linkio - Network link speed simulation for Reader/Writer interfaces
llb - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response.
mdns - Simple mDNS (Multicast DNS) client/server library in Golang
mqttPaho - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
portproxy - Simple TCP proxy which adds CORS support to API's which don't support it.
raw - Package raw enables reading and writing data at the device driver level for a network interface.
sftp - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt.
sslb - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance.
tcp_server - A Go library for building tcp servers faster.
utp - Go uTP micro transport protocol implementation.
winrm - A Go WinRM client to remotely execute commands on Windows machines
OpenGL

Libraries for using OpenGL in Go.

gl - Go bindings for OpenGL (generated via glow).
glfw - Go bindings for GLFW 3.
goxjs/gl - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).
goxjs/glfw - Go cross-platform glfw library for creating an OpenGL context and receiving events.
mathgl - Pure Go math package specialized for 3D math, with inspiration from GLM.
ORM

Libraries that implement Object-Relational Mapping or datamapping techniques.

beego orm - A powerful orm framework for go. Support: pq/mysql/sqlite3.
go-store - A simple and fast Redis backed key-value store library for Go.
gomodel - A lightweight, fast, orm-like library helps interactive with database.
GORM - The fantastic ORM library for Golang, aims to be developer friendly.
gorp - Go Relational Persistence, ORM-ish library for Go.
QBS - Stands for Query By Struct. A Go ORM.
reform - A better ORM for Go, based on non-empty interfaces and code generation.
Storm - Simple and powerful ORM for BoltDB.
upper.io/db - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.
Xorm - Simple and powerful ORM for Go.
Zoom - A blazing-fast datastore and querying engine built on Redis.
Package Management

Libraries for package and dependency management.

gigo - PIP-like dependency tool for golang, with support for private repositories and hashes.
glide - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip.
godep - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.
gom - Go Manager - bundle for go.
goop - A simple dependency manager for Go (golang), inspired by Bundler.
gopm - Go Package Manager
gpm - Barebones dependency manager for Go.
johnny-deps - Minimal dependency version using Git
nut - Vendor Go dependencies
VenGO - create and manage exportable isolated go virtual environments
Query Language

graphql - graphql parser + utilities.
graphql - GraphQL implementation in go.
graphql-go - An implementation of GraphQL for Go.
jsonql - JSON query expression library in Golang.
Resource Embedding

esc - Embeds files into Go programs and provides http.FileSystem interfaces to them.
fileb0x - Simple tool to embed files in go with focus on "customization" and ease to use.
go-bindata - Package that converts any file into managable Go source code.
go-embed - Generates go code to embed resource files into your library or executable
go-resources - Unfancy resources embedding with Go.
go.rice - go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy.
statics - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks.
vfsgen - Generates a vfsdata.go file that statically implements the given virtual filesystem.
Science and Data Analysis

Libraries for scientific computing and data analyzing.

blas - Implementation of BLAS (Basic Linear Algebra Subprograms)
chart - Simple Chart Plotting library for Go. Supports many graphs types.
evaler - A simple floating point arithmetic expression evaluator
ewma - Exponentially-weighted moving averages
geom - 2D geometry for golang
go-dsp - Digital Signal Processing for Go
go-fn - Mathematical functions written in Go language, that are not covered by math pkg
go-gt - Graph theory algorithms written in "Go" language
go.matrix - linear algebra for go (has been stalled)
gocomplex - A complex number library for the Go programming language.
gofrac - A (goinstallable) fractions library for go with support for basic arithmetic.
gohistogram - Approximate histograms for data streams
gonum/mat64 - The general purpose package for matrix computation. Package mat64 provides basic linear algebra operations for float64 matrices.
gonum/plot - gonum/plot provides an API for building and drawing plots in Go.
goraph - A pure Go graph theory library(data structure, algorith visualization)
gostat - A statistics library for the go language
mudlark-go - A collection of packages providing (hopefully) useful code for use in software using Google's Go programming language.
pagerank - Weighted PageRank algorithm implemented in Go
stats - A statistics package with common functions missing from the Golang standard library.
streamtools - general purpose, graphical tool for dealing with streams of data.
vectormath - Vectormath for Go, an adaptation of the scalar C functions from Sony's Vector Math library, as found in the Bullet-2.79 source code. (currently inactive)
Security

Libraries that are used to help make your application more secure.

acmetool — ACME (Let's Encrypt) client tool with automatic renewal.
BadActor - An in-memory, application-driven jailer built in the spirit of fail2ban
go-yara - Go Bindings for YARA, the "pattern matching swiss knife for malware researchers (and everyone else)"
lego - Pure Go ACME client library and CLI tool (for use with Let's Encrypt)
passlib - Futureproof password hashing library.
simple-scrypt - an scrypt package with a simple, obvious API and automatic cost calibration built-in.
Serialization

Libraries and tools for binary serialization

asn1 - Asn.1 BER and DER encoding library for golang
colfer - Code generation for the Colfer binary format
go-capnproto - Cap'n Proto library and parser for go
bambam - generator for Cap'n Proto schemas from go.
go-codec - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support
gogoprotobuf - Protocol Buffers for Go with Gadgets
goprotobuf - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.
mapstructure - Go library for decoding generic map values into native Go structures.
php_session_decoder - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions
structomap - Library to easily and dynamically generate maps from static structures.
Server Applications

algernon - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber.
Caddy - Caddy is an alternative, HTTP/2 web server that's easy to configure and use.
consul - Consul is a tool for service discovery, monitoring and configuration.
devd - A local webserver for developers
etcd - A highly-available key value store for shared configuration and service discovery.
minio - Minio is a distributed object storage server.
nsq - A realtime distributed messaging platform
yakvs - A small, networked, in-memory key-value store.
Template Engines

Libraries and tools for templating and lexing.

ace - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold.
amber - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade.
damsel - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others.
ego - A lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled.
fasttemplate - Simple and fast template engine. Substitutes template placeholders up to 10x faster than text/template.
gofpdf - A PDF document generator with high level support for text, drawing and images.
kasia.go - Templating system for HTML and other text documents - go implementation.
mustache - A Go implementation of the Mustache template language.
pongo2 - A Django-like template-engine for Go.
quicktemplate - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.
raymond - A complete handlebars implementation in Go.
Razor - Razor view engine for Golang.
Soy - Closure templates (aka Soy templates) for Go, following the official spec
Testing

Libraries for testing codebases and generating test data.

Testing Frameworks

assert - Basic Assertion Library used along side native go testing, with building blocks for custom assertions
assert - Asserts to Go testing
badio - Extensions to Go's testing/iotest package
baloo - Expressive and versatile end-to-end HTTP API testing made easy.
bro - Watch files in directory and run tests for them
frisby - a REST API testing framework
ginkgo - BDD Testing Framework for Go
go-carpet - Tool for viewing test coverage in terminal
go-mutesting - Mutation testing for Go source code
go-vcr - Record and replay your HTTP interactions for fast, deterministic and accurate tests
goblin - Mocha like testing framework fo Go
gocheck - A more advanced testing framework alternative to gotest.
GoConvey - BDD-style framework with web UI and live reload
godog - Cucumber or Behat like BDD framework for Go.
gofight - API Handler Testing for Golang Router framework.
gomega - Rspec like matcher/assertion library.
GoSpec - BDD-style testing framework for the Go programming language.
gospecify - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.
Hamcrest - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
restit - A Go micro framework to help writing RESTful API integration test.
testfixtures - A helper for Rails' like test fixtures to test database applications.
Testify - A sacred extension to the standard go testing package.
Mock

counterfeiter - Tool for generating self-contained mock objects
go-sqlmock - Mock SQL driver for testing database interactions
go-txdb - Single transaction based database driver mainly for testing purposes.
gock - Versatile HTTP mocking made easy.
gomock - Mocking framework for the Go programming language.
mockhttp - Mock object for Go http.ResponseWriter
Fuzzing and delta-debugging/reducing/shrinking

go-fuzz - A randomized testing system
gofuzz - A library for populating go objects with random values
gogenerate - A Scalacheck-like library for Go
Tavor - A generic fuzzing and delta-debugging framework
Text Processing

Libraries for parsing and manipulating texts.

Specific Formats
blackfriday - Markdown processor in Go
github_flavored_markdown - GitHub Flavored Markdown renderer with fenced code block highlighting, clickable header anchor links.
bluemonday - HTML Sanitizer
enca - Minimal cgo bindings for libenca.
genex - Count and expand Regular Expressions into all matching Strings
go-humanize - Formatters for time, numbers, and memory size to human readable format.
go-nmea - NMEA parser library for the Go language.
go-pkg-rss - This package reads RSS and Atom feeds and provides a caching mechanism that adheres to the feed specs.
go-pkg-xmlx - Extension to the standard Go XML package. Maintains a node tree that allows forward/backwards browsing and exposes some simple single/multi-node search functions.
go-runewidth - Functions to get fixed width of the character or string.
gofeed - Parse RSS and Atom feeds in Go
gographviz - Parses the Graphviz DOT language.
gommon/bytes - Format bytes to string.
gonameparts - Parses human names into individual name parts
GoQuery - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.
goregen - A library for generating random strings from regular expressions.
guesslanguage - Functions to determine the natural language of a unicode text.
mxj - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.
sh - A shell parser and formatter
slug - URL-friendly slugify with multiple languages support.
Slugify - A Go slugify application that handles string.
toml - TOML configuration format (encoder/decoder with reflection).
Utility
gotabulate - Easily pretty-print your tabular data with Go.
kace - Common case conversions covering common initialisms.
parseargs-go - A string argument parser that understands quotes and backslashes
parth - URL path segmentation parsing.
xurls - Extract urls from text
Third-party APIs

Libraries for accessing third party APIs.

anaconda - A Go client library for the Twitter 1.1 API
aws-sdk-go - The official AWS SDK for the Go programming language.
brewerydb - Go library for accessing the BreweryDB API.
clarifai - A Go client library for interfacing with the Clarifai API.
discordgo - Go bindings for the Discord Chat API
facebook - Go Library that supports the Facebook Graph API
gads - Google Adwords Unofficial API
gami - Go library for Asterisk Manager Interface.
gcm - Go library for Google Cloud Messaging
geo-golang - Go Library to access Google Maps, MapQuest, Nominatim, OpenCage, HERE, Bing, Mapbox, and OpenStreetMap geocoding / reverse geocoding APIs.
ghost - Go Library for accessing the Snapchat API.
github - Go library for accessing the GitHub API.
go-imgur - Go client library for imgur
go-jira - Go client library for Atlassian JIRA
go-marathon - A Go library for interacting with Mesosphere's Marathon PAAS.
go-trending - Go library for accessing trending repositories and developers at Github.
go-twitter - Go client library for the Twitter v1.1 APIs.
go-xkcd - Go client for the xkcd API.
goamz - Popular fork of goamz which adds some missing API calls to certain packages.
GoMusicBrainz - a Go MusicBrainz WS2 client library.
google - Auto-generated Google APIs for Go.
google-analytics - A simple wrapper for easy google analytics reporting.
google-cloud - Google Cloud APIs Go Client Library.
gostorm - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.
hipchat - This project implements a golang client library for the Hipchat API.
hipchat (xmpp) - A golang package to communicate with HipChat over XMPP.
Medium - A Golang SDK for Medium's OAuth2 API.
megos - A client library for accessing an Apache Mesos cluster
minio-go - Minio Go Library for Amazon S3 compatible cloud storage.
mixpanel - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.
paypal - Wrapper for PayPal payment API
playlyfe - The Playlyfe Rest API Go SDK
pushover - Go wrapper for the Pushover API.
rrdaclient - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP.
shopify - Go Library to make CRUD request to the Shopify API.
slack - Slack API in Go.
smite - Go package to wraps access to the Smite game API.
spotify - Go Library to access Spotify WEB API.
steam - Go Library to interact with Steam game servers.
stripe - Go client for the Stripe API
telebot - Telegram bot framework written in Go.
telegram-bot-api - Simple and clean Telegram bot client.
textbelt - Go client for the textbelt.com txt messaging API.
TheMovieDb - A simple golang package to communicate with themoviedb.org
translate - Go online translation package.
tumblr - Go wrapper for the Tumblr v2 API.
webhooks - Webhook reciever for GitHub and Bitbucket.
Utilities

General utilities and tools to make your life easier.

abutil - A collection of often-used Golang helpers.
apm - A process manager for Golang applications with an HTTP API.
boilr - A blazingly fast CLI tool for creating projects from boilerplate templates.
command - Command pattern for Go with thread safe serial and parallel dispatcher
coop - Cheat sheet for some of the common concurrent flows in Go.
Death - Managing go application shutdown with signals.
Deepcopier - Simple struct copying for Go.
delve - Go debugger.
fastlz - Wrap over FastLz (free, open-source, portable real-time compression library) for GoLang.
filetype - Small package to infer the file type checking the magic numbers signature.
fzf - A command-line fuzzy finder written in Go
generate - runs go generate recursively on a specified path or environment variable and can filter by regex.
gentleman - Full-featured plugin-driven HTTP client library.
go-cron - A simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.
go-debug - Conditional debug logging for Golang libraries & applications.
go-dry - DRY (don't repeat yourself) package for Go.
go-rate - A timed rate limiter for Go.
go-sitemap-generator - XML Sitemap generator written in Go.
go-trigger - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.
go-underscore - A useful collection of helpfully functional Go collection utilities.
goback - Go simple exponential backoff package.
godaemon - Utility to write daemons.
godotenv - A Go port of Ruby's dotenv library (Loads environment variables from .env.)
godropbox - Common libraries for writing Go services/applications from Dropbox.
gohper - Various tools/modules help for development.
gojq - JSON query in Golang.
golarm - Fire alarms with system events.
golog - Easy and lightweight CLI tool to time track your tasks.
gopencils - Small and simple package to easily consume REST APIs.
goplaceholder - a small golang lib to generate placeholder images.
goreq - Minimal and simple request library for Go language.
goreq - An enhanced simplified HTTP client based on gorequest.
gorequest - Simplified HTTP client with rich features for Go.
gotenv - Load environment variables from .env or any io.Reader in Go
grequests - An elegant and simple net/http wrapper that follows Python's requests library
htcat - Parallel and Pipelined HTTP GET Utility
httpcontrol - Package httpcontrol allows for HTTP transport level control around timeouts and retries.
hystrix-go - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker.
JobRunner - Smart and featureful cron job scheduler with job queuing and live monitoring built in.
jsonf - Console tool for highlighted formatting and struct query fetching JSON.
jsongo - Fluent API to make it easier to create Json objects.
lrserver - LiveReload server for Go
mc - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.
mergo - A helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.
moldova - A utility for generating random data based on an input template.
mp - A simple cli email parser. It currently takes stdin and outputs JSON.
multitick - Multiplexor for aligned tickers.
netbug - Easy remote profiling of your services.
ngrok - Introspected tunnels to localhost.
okrun - go run error steamroller.
panicparse - Groups similar goroutines and colorizes stack dump.
peco - Simplistic interactive filtering tool.
pester - Go HTTP client calls with retries, backoff, and concurrency.
pm - Process (i.e. goroutine) manager with an HTTP API.
profile - Simple profiling support package for Go.
request - Go HTTP Requests for Humans™.
rerate - Redis-based rate counter and rate limiter for Go.
rerun - Recompiling and rerunning go apps when source changes.
resty - Simple HTTP and REST client for Go inspired by Ruby rest-client.
robustly - Runs functions resiliently, catching and restarting panics.
scheduler - Cronjobs scheduling made easy.
sling - Go HTTP requests builder for API clients.
spinner - Go package to easily provide a terminal spinner with options.
sqlx - provides a set of extensions on top of the excellent built-in database/sql package.
ugo - ugo is slice toolbox with concise syntax for Go.
xferspdy - Xferspdy provides binary diff and patch library in golang
xlsx - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.
Validation

Libraries for validation.

govalidator - Validators and sanitizers for strings, numerics, slices and structs.
validator - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.
Version Control

Libraries for version control.

gh - Scriptable server and net/http middleware for GitHub Webhooks.
git2go - Go bindings for libgit2.
go-vcs - manipulate and inspect VCS repositories in Go.
hgo - Hgo is a collection of Go packages providing read-access to local Mercurial repositories.
Video

Libraries for manipulating video.

aac/h264 - Golang aac/h264 encoder and decoder.
gmf - Go bindings for FFmpeg av* libraries.
goav - Comphrensive Go bindings for FFmpeg.
gst - Go bindings for GStreamer.
Web Frameworks

Full stack web frameworks.

Beego - beego is an open-source, high-performance web framework for the Go programming language.
Bone - Lightning Fast HTTP Multiplexer.
Bxog - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters.
chi - Small, fast and expressive HTTP router built on net/context.
Echo - A fast and unfancy micro web framework for Go.
Gin - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.
Gizmo - Microservice toolkit used by the New York Times.
Glue - Robust Go and Javascript Socket Library (Alternative to Socket.io).
go-json-rest - A quick and easy way to setup a RESTful JSON API.
go-kit - A Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.
go-relax - A framework of pluggable components to build RESTful API's.
go-rest - A small and evil REST framework for Go.
go-socket.io - socket.io library for golang, a realtime application framework.
goa - Framework for developing microservices based on the design of Ruby's Praxis.
Goat - A minimalistic REST API server in Go.
gocraft/web - A mux and middleware package in Go.
Goji - Goji is a minimalistic and flexible HTTP request multiplexer with support for net/context.
Golf - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library.
golongpoll - HTTP longpoll server library that makes web pub-sub simple.
Gondola - The web framework for writing faster sites, faster
goose - Server Sent Events in Go
Gorilla - Gorilla is a web toolkit for the Go programming language.
httprouter - A high performance router. Use this and the standard http handlers to form a very high performance web framework.
httptreemux - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter.
Iris - A very minimal but flexible and high-performance golang web application framework, providing a robust set of features for building web applications.
lars - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks.
Macaron - Macaron is a high productive and modular design web framework in Go.
mango - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333.
medeina - Medeina is a HTTP routing tree based on HttpRouter, inspired by Roda and Cuba.
mux - A powerful URL router and dispatcher for golang.
neo - Neo is minimal and fast Go Web Framework with extremely simple API.
ozzo-routing - A high-performance HTTP router and Web framework supporting routes with regular expressions. Comes with full support for quickly building a RESTful API application.
pat - Sinatra style pattern muxer for Go’s net/http library, by the author of Sinatra.
Resoursea - A REST framework for quickly writing resource based services.
REST Layer - A framework to build REST/GraphQL API on top of databases with mostly configuration over code.
Revel - A high-productivity web framework for the Go language.
rex - Rex is a library for modular development built upon gorilla/mux, fully compatible with net/http.
sawsij - lightweight, open-source web framework for building high-performance, data-driven web applications.
Siesta - Composable framework to write middleware and handlers
tango - Micro & pluggable web framework for Go.
tigertonic - A Go framework for building JSON web services inspired by Dropwizard
traffic - Sinatra inspired regexp/pattern mux and web framework for Go.
VarHandler - Generate boilerplate http input and ouput handling.
vestigo - A performant, stand-alone, HTTP compliant URL Router for go web applications.
Volatile - Minimalist middleware stack promoting flexibility, good practices and clean code.
xmux - A high performance muxer based on httprouter with net/context support.
Zerver - Zerver is an expressive, modular, feature completed RESTful framework.
zeus - A very simple and fast HTTP router for Go.
Middlewares

Actual middlewares

CORS - Easily add CORS capabilities to your API.
formjson - Transparently handle JSON input as a standard form POST.
Limiter - Dead simple rate limit middleware for Go.
Tollbooth - Rate limit HTTP request handler.
XFF - Handle X-Forwarded-For header and friends.
Libraries for creating HTTP middlewares

alice - Painless middleware chaining for Go.
catena - http.Handler wrapper catenation (same API as "chain").
chain - Handler wrapper chaining with scoped data (net/context-based "middleware").
go-wrap - Small middlewares package for net/http.
gores - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs.
httpware - Stackable middleware (using net/context) with easy chaining.
interpose - Minimalist net/http middleware for golang.
muxchain - Lightweight middleware for net/http.
negroni - Idiomatic HTTP middleware for Golang.
render - Go package for easily rendering JSON, XML, and HTML template responses.
stats - A Go middleware that stores various information about your web application.
Tools
Go software and plugins.

Code Analysis

dupl - A tool for code clone detection.
errcheck - Errcheck is a program for checking for unchecked errors in Go programs.
gcvis - Visualise Go program GC trace data in real time.
Go Metalinter - Metalinter is a tool to automatically apply all static analysis tool and report their output in normalized form.
go-checkstyle checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style refered to some points in Go Code Review Comments.
go-outdated - Console application that displays outdated packages.
goast-viewer - Web based Golang AST visualizer.
GoCover.io - GoCover.io offers the code coverage of any golang package as a service.
goimports - Tool to fix (add, remove) your Go imports automatically.
GoLint - Golint is a linter for Go source code.
Golint online - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
goreturns - Adds zero-value return statements to match the func return types.
gostatus - A command line tool, shows the status of repositories that contain Go packages.
interfacer - A linter that suggests interface types.
validate - Automatically validates struct fields with tags.
Editor Plugins

go-lang-idea-plugin Go plugin for IntelliJ IDEA.
go-plus - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting
Goclipse - An Eclipse plugin for Go.
gocode - An autocompletion daemon for the Go programming language.
GoSublime - A Golang plugin collection for the text editor SublimeText 2 providing code completion and other IDE-like features.
velour - An IRC client for the acme editor.
vim-compiler-go - A Vim plugin to highlight syntax errors on save.
vim-go - Go development plugin for Vim.
Watch - Runs a command in an acme win on file changes.
Go Tools

colorgo - A wrapper around go command for colorized go build output.
gb - An easy to use project based build tool for the Go programming language.
go-pkg-complete - Bash completion for go and wgo.
rts - RTS: response to struct. Generates Go structs from server responses.
Software Packages

Software written in Go.

DevOps Tools

aptly - aptly is a Debian repository management tool.
awsenv - a small binary that loads Amazon (AWS) environment variables for a profile.
Banshee - Anomalies detection system for periodic metrics.
Boom - Boom is a tiny program that sends some load to a web application.
bosun - Time Series Alerting Framework.
dogo - Monitoring changes in the source file and automatically compile and run (restart).
Dropship - A tool for deploying code via cdn.
EasySSH - Golang package for easy remote execution through SSH and SCP downloading.
Go Metrics - Go port of Coda Hale's Metrics library: https://github.com/codahale/metrics.
go-selfupdate - Enable your Go applications to self update.
gobrew - gobrew lets you easily switch between multiple versions of go.
godbg - Web-based gdb front-end application.
Gogs - A Self Hosted Git Service in the Go Programming Language.
gonative - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.
gox - A dead simple, no frills Go cross compile tool.
goxc - build tool for Go, with a focus on cross-compiling and packaging.
GVM - GVM provides an interface to manage Go versions.
kala - Simplistic, modern, and performant job scheduler.
kubernetes - Container Cluster Manager from Google.
Mora - REST server for accessing MongoDB documents and meta data.
ostent - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB.
Packer - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
Rodent - Rodent helps you manage Go versions, projects and track dependencies.
s3gof3r - A small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.
Scaleway-cli - Manage BareMetal Servers from Command Line (as easily as with Docker).
Vegeta - HTTP load testing tool and library. It's over 9000!
webhook - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.
Wide - A Web-based IDE for Teams using Golang.
winrm-cli - A cli tool to remotely execute commands on Windows machines
Other Software

boxed - Dropbox based blog engine
Cherry - A tiny webchat server in Go.
Circuit - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
Comcast - Simulate bad network connections.
confd - Manage local application configuration files using templates and data from etcd or consul.
Docker - An open platform for distributed applications for developers and sysadmins.
fleet - A Distributed init System.
Go Package Store - An app that displays updates for the Go packages in your GOPATH.
gocc - Gocc is a compiler kit for Go written in Go.
GoDocTooltip - A chrome extension for Go Doc sites, which shows function description as tooltip at funciton list.
Gor - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.
heka - universal tool for data processing from Mozilla. Large collection of built-in plugins. Extendable via Go and Lua plugin API.
hsync - A filesystem hierarchy synchronizer.
hugo - A Fast and Modern Static Website Engine.
ipe - An open source Pusher server implementation compatible with Pusher client libraries written in GO.
Juju - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
limetext Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
LiteIDE LiteIDE is a simple, open source, cross-platform Go IDE.
mockingjay Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests.
naclpipe - A simple NaCL EC25519 based crypto pipe tool written in Go.
nes - A Nintendo Entertainment System (NES) emulator written in Go.
orange-cat - A Markdown previewer written in Go.
peg - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator.
Postman - Command-line utility for batch-sending email.
restic - De-duplicating backup program.
rkt - An App Container runtime that integrates with init systems, is compatible with other container formats like Docker, and supports alternative execution engines like KVM.
Seaweed File System - Fast, Simple and Scalable Distributed File System with O(1) disk seek.
shell2http - Executing shell commands via http server (for prototyping or remote control).
snap - A powerful telemetry framework.
Stack Up - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers.
syncthing - An open, decentralized file synchronization tool and protocol.
Tenyks - Service oriented IRC bot using Redis and JSON for messaging.
toto - A simple proxy server written in Go language, can be used together with browser.
toxiproxy - Proxy to simulate network and system conditions for automated tests.
tsuru - An extensible and open source Platform as a Service software.
websysd - Web based process manager (like Marathon or Upstart).
wellington - Sass project management tool, extends the language with sprite functions (like Compass).
Resources
Where to discover new Go libraries.

Benchmarks

autobench - Framework to compare the performance between different Go versions.
go-benchmarks - A few miscellaneous Go microbenchmarks. Compare some language features to alternative aproaches.
go-http-routing-benchmark - Go HTTP request router benchmark and comparison.
go-type-assertion-benchmark - Naive performance test of two ways to do type assertion in Go.
go_serialization_benchmarks - Benchmarks of Go serialization methods.
gocostmodel - Benchmarks of common basic operations for the Go language.
golang-micro-benchmarks - Tiny collection of Go micro benchmarks. The intent is to compare some language features to others.
golang-sql-benchmark - A collection of benchmarks for popular Go database/SQL utilities.
gospeed - Go micro-benchmarks for calculating the speed of language constructs.
kvbench - Key/Value database benchmark.
skynet - Skynet 1M threads microbenchmark.
speedtest-resize - Compare various Image resize algorithms for the Go language.
Conferences

dotGo - Paris, France
GoCon - Tokyo, Japan
GolangUK - London, UK
GopherChina - Shanghai, China
GopherCon - Denver, USA
GopherCon Dubai - Dubai, UAE
GopherCon India - Bengaluru, India
GothamGo - New York City, USA
E-Books

A Go Developer's Notebook
An Introduction to Programming in Go
Build Web Application with Golang
Building Web Apps With Go
Go Bootcamp
GoBooks - A curated list of Go books
Learning Go
Network Programming With Go
The Go Programming Language
Twitter

@golang
@golang_news
@golangweekly
Websites

Awesome Go @LibHunt - Your go-to Go Toolbox.
Awesome Remote Job - A curated list of awesome remote jobs. A lot of them is looking for Go hackers.
awesome-awesomeness - List of other amazingly awesome lists.
Flipboard - Go Magazine - A collection of Go articles and tutorials.
Go Blog - The official Go blog.
Go Forum - Forum to discuss Go.
Go Projects - List of projects on the Go community wiki.
godoc.org - Documentation for open source Go packages.
golang-graphics - A collection of Go images, graphics, and art.
golang-nuts - Go mailing list.
Google Plus Community - The Google+ community for #golang enthusiasts.
gowalker.org - Go Project API documentation.
r/Golang - News about Go.
Trending Go repositories on GitHub today - Good place to find new Go libraries.
Tutorials

A Tour of Go - Interactive tour of Go.
Go By Example - A hands-on introduction to Go using annotated example programs.
Go database/sql tutorial - Introduction to database/sql.
Working with Go - An intro to go for experienced programmers.
Windows

d3d9 - Go bindings for Direct3D9
go-ole - Win32 OLE implementation for golang.