## SAGE DRAUGHTS

<img src="https://raw.githubusercontent.com/orac81/Orac-Draughts/refs/heads/main/sage/sage-screen1.png">

Download the latest version of SAGE (10.346) with source and executable:
  <https://github.com/orac81/Orac-Draughts/raw/refs/heads/main/sage/sage-draughts-latest.zip>


SAGE DRAUGHTS is released as free software under the GNU GPL-3 Software license. 
For latest version, source and more details see the Github page: https://github.com/orac81/Orac-Draughts
The software supplied "as-is" with no warranty. 

SAGE is a 32 bit Windows program, which should run on any version from XP up to Windows 11. It can can run under LINUX or MAC-OS using a windows emulator like WINE. It can be installed by simply downloading and extracting the zip file. To run, open the SAGE folder and click/run SAGE.EXE.


SAGE is one of the most comprehensive Checker playing programs available. Not only can it play a strong game, but it also provides advanced features such as PDN Game Databases, advanced game analysis, annotation, autolearning, and much more. Despite its wealth of features, it is very easy to use, anyone who knows how to use a standard Windows program should have no problems with SAGE's simple interface. It can play both the English and Italian variant of the game, up to Master level. 

On running, SAGE presents some version information, and asks you to select (Play) or (Reset) If you select (Reset) SAGE resets all its parameters and settings. If you select (Play) it remembers the Game, Engine settings, screen layout and colours from the last time you used it. You are now ready to play SAGE! The main SAGE screen consists of the Board, Move record, Search info, and Book windows, conventional Windows pull down menus, and quick-access toolbar buttons along the top of the screen. These buttons co-relate to menu functions – when you position the mouse on a button, a description of the menu function will appear.

Playing SAGE is very simple - start a new game by selecting Files/New Game menu or click on the New Game toolbar button. At this stage you can also select English Checkers, Dama Italiana or other Draughts variants. Now select the computer thinking time with the Play/Play Levels menu, or select the Play Levels toolbar button - and enter a response time. You are now ready to move - just click the LEFT MOUSE BUTTON on the piece you want to move, drag it to the destination square and release it. If the piece could only move one way, its move is automatic as soon as you click the piece. You can also enter the move by typing in a 4 digit number with the source/destination - keeping leading zeros. Thus to move 4-8 you would type 0408. As you play, SAGE will tell you information about the opening - it will display the code for the opening, together with the name. Let us now go through the available menu options..

Files Menu

    New Game - Starts a new game, allowing you the chance to select the game type (Italian, English or User defined). The User defined rules allow irregular board sizes from 4x4 up to 12x12!
    New 3 Move - Selects a new random 3 move opening. It will choose from the 156 playable openings (as defined in OPENING1.PDN marked with a = sign in the event field)
    Select Opening - Displays a list of all openings, in 3 catagories - first moves only, "Classic" openings, then 3 move ballot openings. Double Click on the opening you want.
    Open Game - Load an existing game file from disk.
    Save Game - Save current game to disk. NOTE - we recommend using the new PDN save-load functions for storing games, since many advanced features are provided for handling PDN databases.
    Save Game and Settings - Saves all screen/engine settings with game.
    Spawn Game - Starts up a new copy of SAGE with the current game set up. It also stops any computation in process on the current copy. Useful if you want to analyse new lines or ideas, and yet return to the current line when done. When you have finished, simply close down the Spawned copy, and the original game will be intact.
    Print Move list - Prints (to Printer or a text file) game-info & all moves up to current one.
    Print Diagram - Prints board position, using true-type fonts. If you print to a file, you can then paste that file into a word-processor and select the "CheckerPCS" font for that text to get a diagram. NOTE - printer functions will require fonts that include the Checker font, to work properly.
    Spool Analysis to.. - Selects a printer/file to receive analysis while moves are played. NOTE - a tick appears by the menu item - you MUST select this option a 2nd time to flush any data and close down the output file/device.
    Paste game from Clipboard - Loads a game from text stored in PDN format on the Windows Clipboard.
    Copy game to Clipboard – Copies the current game as PDN format text to the Windows Clipboard – the game text can then be pasted into another Windows application.
    Quit - Exit the program.

Levels menu

    Play Levels - Set the time the computer spend thinking for each move. This can have the following settings: Time each move: Computer will try to spend this amount of time on each move – this is an average calculated over 60 moves. Tournament settings: two time controls, can be time-per-game or x moves in x time. Similar to Chess Clocks. IQ level setting: fixed depth search - sets an "IQ level" in steps of 10 points. Each 10 points equates to about 1 ply of search depth. Infinite: Search until stopped - for overnight analysis, etc.
    Instant, 2 Seconds/Move etc.. Quick access options for these settings.
    Set Clocks - Set the white-black elapsed-time clocks. Bear in mind that altering these can effect Computer play level, since it uses these clocks to calculate move-time.

Play menu

    Edit Board - Set up a board position - simple pickup/drop pieces with the mouse at will. To erase, drop of the edge. Pick up new pieces from the bottom box. Buttons on right clear board, set up new position, invert board, and Exit with either White or Black to play.
    Engine Thinking parameters : This command allows you to adjust how SAGE thinks, or select external checker-playing "engines". See Engine thinking parameters below..
    Game comments - Edit/enter header data about the current game being played (players, venue, result, year, ELO, ECO) - this is saved/printed with the game.
    Add move comment - Add/Edit comment for the current move.
    Normal play - Selects normal human V computer play mode.
    Two player - Selects 2 human player/move entry mode. Computer will also constantly analyse the current position in this mode, showing this in the Search Info windows, so this mode can be used to browse through and analyse a game.
    Auto play - Start computer V computer auto play from current position, just using the "primary" engine.
    Auto play tournament - Play a match between 2 checker engine "brains" - see Auto-play tournement section below..

Action menu

    Computer go - Tells computer to take your side and play, swapping sides.
    Force move - If computer is thinking, tells it to stop and make its best move.
    Next Best - Tells computer to think again about its last move, selecting a new move.
    Quick hint - Show a suggested hint, if the computer has one available.
    Undo/Redo options - Tells computer to step forward/back all/10/1 move. Use these controls to freely navigate a game. NOTE - these controls adjust the elapsed time clocks, to keep the response time correct.

Look/feel menu

    Display options - Select board/text colours, the piece set, and board patterns. (See file CHKSET.DEF for information on customising the piece-sets)
    Text font - Select font used in game-display windows.
    Flip board - Turn board upside-down.
    Sound - Enable/disable sound effects.
    Board co-ordinates - Display board numbering.
    Animation - Enable/disable sliding pieces. (SAGE is faster when off)
    Pop-Up windows - Toggles child/independent game-display windows.
    Reset layout - Resets to original layout.
    2nd Analysis line - Shows previous analysis in Search information window.
    PDN display - Toggles tabbed/PDN type display in move record.
    PDN Numbering - Enable/Disable move numbering in move list window. Also effects database save/transfer, use this to disable move numbering in PDN files too.
    Full analysis - Shows extra analysis information.
    Analysis to Comments - sends computer analysis to comments during play.
    Language options - Select your chosen language

Database menu

    Load game from PDN database - List the games in the current PDN database, in a list box, line by line, ready to be loaded. You can use the Scroll bar to move through the database, then Double-click on a game to load. See "USING DATABASES" below..
    Next game from PDN database - Read the next game from the last used PDN file.
    Reload last game from PDN database - re-read the game loaded from the last used PDN file.
    Select PDN database - Select new PDN database, used by above LOAD function.
    Search PDN Database See Searching databases section below..
    Save game to PDN database - Save/append current game to a PDN file.
    Edit PDN Database as text file.. Edits current database in WORDPAD. Use this to delete/alter game details directly.
    Transfer/Sort PDN Database - This powerful feature can be used to transfer games between databases. Yo can specify a search filter if you like, it will only transfer games that match the search parameters. If you specify "auto-classify" it will classify any games transferred according to the opening codes in OPENING1.PDN. If you specify sort by Date/ECO code, it will sort all games in order according to date/opening code.
    Annotate game - Replays game from current move until end, analysing for time defined by play-level and sends result to Printer/File. Note- when finished select the "Spool Analysis to" option to close/flush the buffer.
    Analyse DPD - Read and analyse a set of positions in a DPD file. Each position is loaded into SAGE, analysed for the current move-time, then written back to the DPD file with a score and best line added, ie. "ce xxxx pv move move move". This is the same format at the CHESS EPD file format. The resultant file can then be viewed with a normal text editor,
    Import DPD - Read the Nth position from a DPD file.
    Import DPD - Read the Next position from a DPD file.
    Export DPD - Save/append current position to a DPD file. A score can be set for the move (in 1/100ths of an evaluation point) – useful for "teaching" SAGE about positions with the HASHOP book feature (see below).
    Export user book - Dump opening book to a file, as a PDN format database.
    Save user book - Save current book to a file.
    Load user book - Load a file into current book.
    User book add line - Adds current game to opening book.
    Import book text - Automatically merge a number of book lines from a text file into the current book. The text file can be either in PDN format, or the old sbook/ibook.txt format used in previous SAGE/DAMA ITALIANA programs.

Many of these mrnu functions can be accessed quickly through the TOOLBAR - just place the mouse over any toolbar option and a text describing the function of it will appear..

Other non-menu functions

Double click left mouse on move field in book window: Execute book move

Double click left mouse on book field in book window. Dialog box alters strength of that book-move.

+ or - to adjust move time (seconds per move) quickly.

 

Search info format

When SAGE is computing, it shows information on what it is thinking about are in the Search info window. The above screenshot shows a typical display. Each time SAGE finds a new "best move", or a new line of play, the display scrolls upwards – hence you can see historic analysis going back over a period of time by scrolling this window upwards. The current best move/line is always at the very bottom. Moves that are actually played are displayed in red, the current move in blue, and "thinking in opponents time" is shown in grey. This is a description of the displayed data, item by item..

    Cur: Most recently analysed move – its "index" and the move itself.
    IQ: Current IQ search depth. Approximately 10 points per ply searched. The 2nd number is the absolute maximum search depth reached.
    Time: The time taken to search this far.
    Nodes: The number of search-tree "terminal" nodes encountered so far.
    Eval: Approximate score for the best move so far. One point (1.00) is roughly equal to a king at the start of the game, and a man towards the end of the game. A positive score means white is ahead, a negative score means black is ahead. When the best line leads to an "endgame database" position (ie <=6 pieces) then a score of <-6.00 means Black is winning, a score of >6.00 means White is winning, a score of around 0.00 means that the position is drawn.
    Best Line: This is the line of play that the computer thinks is "best" from the current position.




For full help, open the HTML file "doc/sagedoc1.htm" in the SAGE folder.


