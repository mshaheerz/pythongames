# pythongames
imported from freegame library ,
not edited
trying to changes..............



# Features¶
Fun to play!

Simple Python code

Easy to install

Designed for education

Depends only on the Python Standard Library

Used in hundreds of hours of classroom instruction

Fully Documented

100% Test Coverage

Developed on Python 3.7

Tested on CPython 2.7, 3.4, 3.5, 3.6, and 3.7

Tested on Windows, Mac OS X, Raspbian (Raspberry Pi), and Linux

Tested using Travis CI and AppVeyor CI

<a class="reference external image-reference" href="http://www.grantjenks.com/docs/freegames/"><img alt="https://api.travis-ci.org/grantjenks/free-python-games.svg?branch=master" src="https://api.travis-ci.org/grantjenks/free-python-games.svg?branch=master" /></a>
<a class="reference external image-reference" href="http://www.grantjenks.com/docs/freegames/"><img alt="https://ci.appveyor.com/api/projects/status/github/grantjenks/free-python-games?branch=master&amp;svg=true" src="https://ci.appveyor.com/api/projects/status/github/grantjenks/free-python-games?branch=master&amp;svg=true" /></a>
</div>
<div class="section" id="quickstart">
<h2>Quickstart<a class="headerlink" href="#quickstart" title="Permalink to this headline">¶</a></h2>
<p>Installing Free Python Games is simple with <a class="reference external" href="https://pypi.python.org/pypi/pip">pip</a>:</p>
<div class="highlight-default notranslate"><div class="highlight"><pre><span></span>$ python3 -m pip install freegames
</pre></div>
</div>
<p>Free Python Games supports a command-line interface (CLI). Help for the CLI is
available using:</p>
<div class="highlight-default notranslate"><div class="highlight"><pre><span></span>$ python3 -m freegames --help
</pre></div>
</div>
<p>The CLI supports three commands: list, copy, and show. For a list of all games
run:</p>
<div class="highlight-default notranslate"><div class="highlight"><pre><span></span>$ python3 -m freegames list
</pre></div>
</div>
<p>Any of the listed games may be played by executing the Python module from the
command-line. To reference the Python module, combine “freegames” with the name
of the game. For example, to play the “snake” game run:</p>
<div class="highlight-default notranslate"><div class="highlight"><pre><span></span>$ python3 -m freegames.snake
</pre></div>
</div>
<p>Games can be modified by copying their source code. The copy command will
create a Python file in your local directory which you can edit. For example,
to copy and play the “snake” game run:</p>
<div class="highlight-default notranslate"><div class="highlight"><pre><span></span>$ python3 -m freegames copy snake
$ python3 snake.py
</pre></div>
</div>
<p>Python includes a built-in text editor named IDLE which can also execute Python
code. To launch the editor and make changes to the “snake” game run:</p>
<div class="highlight-default notranslate"><div class="highlight"><pre><span></span>$ python3 -m idlelib.idle snake.py
</pre></div>
</div>
<p>You can also access documentation in the interpreter with Python’s built-in
help function:</p>
<div class="highlight-default notranslate"><div class="highlight"><pre><span></span><span class="gp">&gt;&gt;&gt; </span><span class="kn">import</span> <span class="nn">freegames</span>
<span class="gp">&gt;&gt;&gt; </span><span class="n">help</span><span class="p">(</span><span class="n">freegames</span><span class="p">)</span>
</pre></div>
</div>
</div>
<div class="section" id="free-games">
<h2>Free Games<a class="headerlink" href="#free-games" title="Permalink to this headline">¶</a></h2>
<div class="section" id="paint">
<h3>Paint<a class="headerlink" href="#paint" title="Permalink to this headline">¶</a></h3>
<p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/paint.html">Paint</a> – draw lines and shapes on the screen. Click to mark the start of a
shape and click again to mark its end. Different shapes and colors can be
selected using the keyboard.</p>
<img alt="Paint Free Python Game" src="http://www.grantjenks.com/docs/freegames/_static/paint.gif" />
</div>
<div class="section" id="snake">
<h3>Snake<a class="headerlink" href="#snake" title="Permalink to this headline">¶</a></h3>
<p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/snake.html">Snake</a> – classic arcade game. Use the arrow keys to navigate and eat the
green food. Each time the food is consumed, the snake grows one segment
longer. Avoid eating yourself or going out of bounds!</p>
<img alt="Snake Free Python Game" src="http://www.grantjenks.com/docs/freegames/_static/snake.gif" />
</div>
<div class="section" id="pacman">
<h3>Pacman<a class="headerlink" href="#pacman" title="Permalink to this headline">¶</a></h3>
<p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/pacman.html">Pacman</a> – classic arcade game. Use the arrow keys to navigate and eat all
the white food. Watch out for red ghosts that roam the maze.</p>
<img alt="Pacman Free Python Game" src="http://www.grantjenks.com/docs/freegames/_static/pacman.gif" />
</div>
<div class="section" id="cannon">
<h3>Cannon<a class="headerlink" href="#cannon" title="Permalink to this headline">¶</a></h3>
<p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/cannon.html">Cannon</a> – projectile motion. Click the screen to fire your cannnonball. The
cannonball pops blue balloons in its path. Pop all the balloons before they can
cross the screen.</p>
<img alt="Cannon Free Python Game" src="http://www.grantjenks.com/docs/freegames/_static/cannon.gif" />
</div>
<div class="section" id="connect">
<h3>Connect<a class="headerlink" href="#connect" title="Permalink to this headline">¶</a></h3>
<p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/connect.html">Connect</a> – Connect 4 game. Click a row to drop a disc. The first player to
connect four discs vertically, horizontally, or diagonally wins!</p>
<img alt="Connect 4 Free Python Game" src="http://www.grantjenks.com/docs/freegames/_static/connect.gif" />
</div>
<div class="section" id="flappy">
<h3>Flappy<a class="headerlink" href="#flappy" title="Permalink to this headline">¶</a></h3>
<p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/flappy.html">Flappy</a> – Flappy-bird inspired game. Click the screen to flap your
wings. Watch out for black ravens as you fly across the screen.</p>
<img alt="Flappy Bird Free Python Game" src="http://www.grantjenks.com/docs/freegames/_static/flappy.gif" />
</div>
<div class="section" id="memory">
<h3>Memory<a class="headerlink" href="#memory" title="Permalink to this headline">¶</a></h3>
<p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/memory.html">Memory</a> – puzzle game of number pairs. Click a tile to reveal a
number. Match two numbers and the tiles will disappear to reveal an image.</p>
<img alt="Memory Free Python Game" src="http://www.grantjenks.com/docs/freegames/_static/memory.gif" />
</div>
<div class="section" id="pong">
<h3>Pong<a class="headerlink" href="#pong" title="Permalink to this headline">¶</a></h3>
<p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/pong.html">Pong</a> – classic arcade game. Use the keyboard to move your paddle up and
down. The first player to miss the ball loses.</p>
<img alt="Pong Free Python Game" src="http://www.grantjenks.com/docs/freegames/_static/pong.gif" />
</div>
<div class="section" id="simon-says">
<h3>Simon Says<a class="headerlink" href="#simon-says" title="Permalink to this headline">¶</a></h3>
<p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/simonsays.html">Simon Says</a> – classic memory puzzle game. Click the screen to start. Watch
the pattern and then click the tiles in the same order. Each time you get the
sequence right the pattern gets one step longer.</p>
<img alt="Simon Says Free Python Game" src="http://www.grantjenks.com/docs/freegames/_static/simonsays.gif" />
</div>
<div class="section" id="tic-tac-toe">
<h3>Tic Tac Toe<a class="headerlink" href="#tic-tac-toe" title="Permalink to this headline">¶</a></h3>
<p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/tictactoe.html">Tic Tac Toe</a> – classic game. Click the screen to place an X or O. Connect
three in a row and you win!</p>
<img alt="Tic Tac Toe Free Python Game" src="http://www.grantjenks.com/docs/freegames/_static/tictactoe.gif" />
</div>
<div class="section" id="tiles">
<h3>Tiles<a class="headerlink" href="#tiles" title="Permalink to this headline">¶</a></h3>
<p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/tiles.html">Tiles</a> – puzzle game of sliding numbers into place. Click a tile adjacent to
the empty square to swap positions. Can you make the tiles count one to fifteen
from left to right and bottom to top?</p>
<img alt="Tiles Free Python Game" src="http://www.grantjenks.com/docs/freegames/_static/tiles.gif" />
</div>
<div class="section" id="tron">
<h3>Tron<a class="headerlink" href="#tron" title="Permalink to this headline">¶</a></h3>
<p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/tron.html">Tron</a> – classic arcade game. Use the keyboard to change the direction of
your Tron player. Avoid touching the line drawn by your opponent.</p>
<img alt="Tron Free Python Game" src="http://www.grantjenks.com/docs/freegames/_static/tron.gif" />
</div>
<div class="section" id="life">
<h3>Life<a class="headerlink" href="#life" title="Permalink to this headline">¶</a></h3>
<p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/life.html">Life</a> – Conway’s Game of Life. The classic, zero-player, cellular automation
created in 1970 by John Conway.</p>
<img alt="Game of Life Free Python Game" src="http://www.grantjenks.com/docs/freegames/_static/life.gif" />
</div>
<div class="section" id="maze">
<h3>Maze<a class="headerlink" href="#maze" title="Permalink to this headline">¶</a></h3>
<p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/maze.html">Maze</a> – move from one side to another. Inspired by <a class="reference external" href="https://www.makeartwithpython.com/blog/10-print-in-python/">A Universe in One Line
of Code with 10 PRINT</a>. Tap the screen to trace a path from one side to
another.</p>
<img alt="Maze Free Python Game" src="http://www.grantjenks.com/docs/freegames/_static/maze.gif" />
</div>
<div class="section" id="fidget">
<h3>Fidget<a class="headerlink" href="#fidget" title="Permalink to this headline">¶</a></h3>
<p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/fidget.html">Fidget</a> – fidget spinner inspired animation. Click the screen to accelerate
the fidget spinner.</p>
<img alt="Fidget Spinner Free Python Game" src="http://www.grantjenks.com/docs/freegames/_static/fidget.gif" />
</div>
</div>
<div class="section" id="user-guide">
<h2>User Guide<a class="headerlink" href="#user-guide" title="Permalink to this headline">¶</a></h2>
<p>For those wanting more details, this part of the documentation describes
curriculum, API, and development.</p>
<ul class="simple">
<li><p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/give-gift-python.html">Talk: Give the Gift of Python</a></p></li>
<li><p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/curriculum.html">Free Python Games Curriculum</a></p></li>
<li><p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/api.html">Free Python Games API Reference</a></p></li>
<li><p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/development.html">Free Python Games Development</a></p></li>
</ul>
</div>
<div class="section" id="references">
<h2>References<a class="headerlink" href="#references" title="Permalink to this headline">¶</a></h2>
<ul class="simple">
<li><p><a class="reference external" href="http://www.grantjenks.com/docs/freegames/">Free Python Games Documentation</a></p></li>
<li><p><a class="reference external" href="https://pypi.python.org/pypi/freegames">Free Python Games at PyPI</a></p></li>
<li><p><a class="reference external" href="https://github.com/grantjenks/free-python-games">Free Python Games at GitHub</a></p></li>
<li><p><a class="reference external" href="https://github.com/grantjenks/free-python-games/issues">Free Python Games Issue Tracker</a></p></li>
</ul>
</div>
<div class="section" id="free-python-games-license">
<h2>Free Python Games License<a class="headerlink" href="#free-python-games-license" title="Permalink to this headline">¶</a></h2>
<p>Copyright 2017-2020 Grant Jenks</p>
<p>Licensed under the Apache License, Version 2.0 (the “License”); you may not use
this file except in compliance with the License.  You may obtain a copy of the
License at</p>
<blockquote>
<div><p><a class="reference external" href="http://www.apache.org/licenses/LICENSE-2.0">http://www.apache.org/licenses/LICENSE-2.0</a></p>
</div></blockquote>
<p>Unless required by applicable law or agreed to in writing, software distributed
under the License is distributed on an “AS IS” BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied.  See the License for the
specific language governing permissions and limitations under the License.</p>
<div class="toctree-wrapper compound">
</div>
</div>
</div>
