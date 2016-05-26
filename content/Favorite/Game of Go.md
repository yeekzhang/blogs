Title: Game of GO
Date: 2016-05-23 9:20
Category: Game
Tags: Game Go

# [GoGinkgo](http://goginkgo.github.io/)
http://goginkgo.github.io - open-source, web-based SGF editor

Board scales dynamically to fill page / window
Can save / load SGF files to / from local machine 

# [BesoGo](https://github.com/yewang/besogo)
Embeddable editor/viewer of SGF records for the game of Go (aka Weiqi, Baduk) http://yewang.github.io/besogo/

# [SGF editor](https://github.com/yishn/Sabaki)
An elegant Go/Baduk/Weiqi board and SGF editor for a more civilized age. http://sabaki.yichuanshen.de/
## Features
- Fuzzy stone placement
- Read and save SGF games and collections
- Display formatted SGF comments using a subset of Markdown
- Personalize board appearance with userstyles
- SGF editing tools
- Lines & arrows markup
- Game graph
- Scoring tool
- Find move
- Position & move annotations
- GTP engines support
- Guess mode

# [EidoGo](http://eidogo.com/source)
[GitHub](git clone git://github.com/jkk/eidogo.git eidogo)

# (SFG Editor)(http://sgfeditor.codeplex.com/)
SGF Editor reads and writes .sgf files, edits game trees, etc. It has several useful commands for reviewing games, including saving in reverse view to give a copy to your opponent. You can also just use it as a Go board to play a game. (For search purposes: goban, baduk, weiqi.)

The project has a Python version (IronPython/WPF required for UI), C#/WPF desktop version, and Windows 8 Windows App Store version. The Python version is the farthest behind (see sgfpy\notes.txt), and the WPF version is behind by a couple of features, also listed in notes.txt). I use PTVS to hack on the IPy version. I use Visual Studio for the C#/WPF and C#/WinRT versions.

[Go Editing Programs](http://senseis.xmp.net/?SGFEditor)
There are a number of software packages that you can use to record games, review and edit game records, produce images and teach yourself go. This page is for the discussion of software for these purposes.

Most go software is multi-functional. Some programs are go clients, some are go editing programs, and some are both. These packages should be reviewed from different angles.

For example, my own situation, that I'm sure many share, is this: After I play my games (live or on-line), I then take the electronic game record (I use PilotGOne to record live ones on my hand-held computer) and review it, adding comments. Later, I need to take some of these games and print them out so I can go over them with my teacher (in person, over a real board). --MtnViewMark 

# [Smart Game Format WikiPedia](https://en.wikipedia.org/wiki/Smart_Game_Format)
The Smart Game Format (SGF) is a computer file format used for storing records of board games. Go is the game that is most commonly represented in this format and is the default. SGF was originally created under a different name by Anders Kierulf for his SmartGO program.

The first version of SGF, FF![1], was conceived by Anders Kierulf in 1987. It is Appendix A in his Ph.D. thesis.[1] FF![3] was written by Martin Muller in 1993. The current version of the SGF is FF![4] by Arno Hollosi, and is supported by most current SGF readers. FF![2] was never made public.

The main purposes of SGF are to store records of played games and to provide features for storing annotated and analyzed games (e.g. board markup, variations). It is a text-only, tree-based format. The tree structure makes the addition of variations simple. It is also text-based instead of binary for the sake of portability.

# [SGF File Format](http://www.red-bean.com/sgf/)
This is the official specification of the SGF FF[4] standard.

SGF is the abbreviation of 'Smart Game Format'. The file format is designed to store game records of board games for two players. It's a text only, tree based format. Therefore games stored in this format can easily be emailed, posted or processed with text-based tools.
The main purposes of SGF are to store records of played games and to provide features for storing annotated and analyzed games (e.g. board markup, variations). 

# [Web Go Board](http://webgoboard.com/)
An online Go Game Browser.

# [The Game Of Go](http://go.davepeck.org/) - [GitHub](https://github.com/davepeck/game-of-go)
This is a website that lets people learn and play the ancient game of Go in an elegant way.

It's currently a Webapp2 site, using Python 2.7, targeted for hosting with Google App Engine. It's open source under the MIT license.

You can see the latest bits running at http://go.davepeck.org/ -- I will always run them there, on my own dime.

# [Node.js-based go game viewer](https://github.com/vdust/gosgf)
library to read and manipulate sgf files(Go game only). Includes a jQuery-based viewer.

# FueGO
https://webdocs.cs.ualberta.ca/~mmueller/ps/fuego-TCIAIG.pdf
https://sourceforge.net/p/fuego/code/HEAD/tree/trunk/
FUEGO’s  GTP E NGINE library  provides  a  game- independent  implementation  of  GTP.  Concrete  game engines will typically derive from the base engine class and register new commands and their handlers. The base engine runs the command loop, parses commands and invokes the command handlers. In addition, G TP E NGINE provides support for pondering , to keep the engine running in the opponent’s time. The pondering function of a game engine is invoked whenever it is waiting for the next command. The base engine sets a flag when the next command has been received to indicate to the game-specific subclass that its pondering function needs to terminate. This facilitates the use of pondering, because the necessary use of multithreading is hidden in the base engine. The functions of the subclass do not need to be thread-safe, because they are only invoked sequentially. G TP E NGINE also provides support for the non-standard GTP extension for interrupting commands as used by the G O G UI graphical user interface [37]. The necessary multithreaded implementation is again hidden in the base engine class.

# [RocAlphaGo] (https://github.com/Rochester-NRT/RocAlphaGo)
This project is a student-led replication/reference implementation of DeepMind's 2016 Nature publication, "Mastering the game of Go with deep neural networks and tree search," details of which can be found on their website. This implementation uses Python and Keras - a decision to prioritize code clarity, at least in the early stages.

# [Learn Go - Go Game Guru](https://gogameguru.com/alphago-defeats-lee-sedol-game-1/)

# [The Interactive Way To Go](http://playgo.to/iwtg/en/)

# [Learn GO](http://www.learngo.co.uk/)
GO is a board game. The current theory is that it was invented by the Chinese between 2,500 and 4,000 years ago, some centuries before the advent of Chess.

It may surprise you to know that it remains the most played board game in the World, with a profile in the East that far exceeds that of Chess in the West. It is not unusual for Sunday TV to provide Go tuition, or coverage of a major Go Tournament.

Go was subsequently adopted in Japan and Korea around 700 AD. However, it was not until the early 20th century that Go spread to the West, starting in Germany. Edward Lasker, the International Chess master, took the game to America, starting the New York Go Club. The game eventually spread across the World.

The rules of Go are very simple, in many ways more so than Chess. However, much like Chess, Go is a hugely engrossing game of great elegance and astonishing depth and richness. It will handsomely reward your efforts in learning the game. 

# [Game records in SGF format](http://www.u-go.net/gamerecords/)
 For other sources of game records, see the list in the links section.

On this page, you can download game records of top amateur games played on the K Go Server (KGS, formerly known as the Kiseido Go Server). I am grateful to Bill Shubert, who created KGS, for the permission to use these files, and for making them available to me in an easy way.

The games in the archives below are those where either one of the players (or both) is 7d or stronger, or both are 6d. All comments are stripped from these games, and all games with variations are omitted. They are suitable for use with Kombilo, but of course, you can use them in any way you like.

# [Drago](http://godrago.net/)
What is it?

Drago is a Windows freeware application dedicated to the game of Go. It enables to:
    browse and edit game files,
    print and export,
    create game databases and search for games with some pattern or some game properties (players, result, date, ...)
    replay games,
    solve problems,
    play against game engines. 