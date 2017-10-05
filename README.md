<h1 id="forgotten">forgotten</h1>

<p>A vim theme inspired by the <a href="https://oblotzky.github.io/sa-oblivion/">Oblivion keycap set</a> by oblotzky (which was inspired by the Oblivion tmTheme by Paolo Borelli).</p>

<h2 id="screenshots">screenshots</h2>

<table>
<tr></tr><tr><td align="center"><strong>forgotten-<br />light</strong></td>
<td align="center"><img src="/img/screenshot-forgotten-light.png" alt="screenshot of the forgotten-light vim theme" width="288" /> <img src="/img/screenshot-forgotten-dark.png" alt="screenshot of the forgotten-dark vim theme" width="288" /></td>
<td align="center"><strong>forgotten-<br />dark</strong></td></tr>
</table>

<h2 id="setup">setup</h2>

<h3 id="installation">installation</h3>

<p>While themes can be installed manually (by placing a <a href="https://github.com/nightsense/forgotten/tree/master/colors">theme file</a> in <code class="highlighter-rouge">~/.vim/colors/</code>), a <strong>plugin helper</strong> is recommended.</p>

<p>If you don’t have a preferred helper, consider trying <a href="https://github.com/junegunn/vim-plug">vim-plug</a>, which can be installed with:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
</code></pre>
</div>

<p>To install forgotten via vim-plug, add the following to the top of your <code class="highlighter-rouge">vimrc</code>:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>call plug#begin('~/.vim/plugged')
Plug 'nightsense/forgotten'
call plug#end()
</code></pre>
</div>

<p>Then restart vim and run <code class="highlighter-rouge">PlugUpdate</code> (from the vim command line).</p>

<h3 id="activation">activation</h3>

<p>To activate the forgotten theme, add one of the following lines to your <code class="highlighter-rouge">vimrc</code>:</p>

<ul>
  <li><code class="highlighter-rouge">colorscheme forgotten-light</code></li>
  <li><code class="highlighter-rouge">colorscheme forgotten-dark</code></li>
</ul>

<p>Note that the <code class="highlighter-rouge">background</code> setting doesn’t affect this theme.</p>

<blockquote>
  <p>To assign themes to specific intervals of the day, try the <a href="https://github.com/nightsense/night-and-day">night-and-day</a> plugin.</p>
</blockquote>

<h2 id="terminal-vim">terminal vim</h2>

<p>See the <a href="https://github.com/nightsense/nightshell">nightshell</a> repository, which allows forgotten to be used in a variety of terminal applications.</p>

<h2 id="palette">palette</h2>

<table>
  <thead>
    <tr>
      <th style="text-align: right">hex</th>
      <th style="text-align: center">base</th>
      <th style="text-align: center">accent</th>
      <th style="text-align: left">hex</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">191c1f</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/191c1f.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/d44652.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">d44652</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">282c30</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/282c30.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/d47211.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">d47211</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">444b52</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/444b52.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/bf850f.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">bf850f</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">676c70</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/676c70.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/659425.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">659425</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">8d9399</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/8d9399.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/3e947e.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">3e947e</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">b0b8bf</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/b0b8bf.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/3f8abf.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">3f8abf</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">dfe3e8</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/dfe3e8.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/7d6fbf.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">7d6fbf</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><code class="highlighter-rouge">f5faff</code></td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/f5faff.png" height="24" width="42" /> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/bf6fab.png" height="24" width="42" /> </td>
      <td style="text-align: left"><code class="highlighter-rouge">bf6fab</code></td>
    </tr>
  </tbody>
</table>

<h3 id="syntax-highlighting-logic">syntax highlighting logic</h3>

<p><img src="http://www.colorhexa.com/d44652.png" height="24" width="42" />
<strong>Red</strong>, the colour of alarm, is used for <strong>warning elements</strong>, including error messages, misspellings, and diff deletions.</p>

<p><img src="http://www.colorhexa.com/d47211.png" height="24" width="42" />
<strong>Orange</strong> is the colour of fire, which serves as a preliminary to many practical activities. Orange is therefore used for <strong>preliminary elements</strong>, such as preprocessor commands (which prepare data to be handled by another program), incremental searching (that is, a search term in the process of being typed), titles, and miscapitalized words.</p>

<p><img src="http://www.colorhexa.com/bf850f.png" height="24" width="42" />
<strong>Yellow</strong>, the classic highlighting colour, is applied to elements that are not warnings yet should draw attention with high visibility. These <strong>highlighted elements</strong> include search results, task tags (<code class="highlighter-rouge">TODO</code>, <code class="highlighter-rouge">FIXME</code>…), and diff changes.</p>

<p><img src="http://www.colorhexa.com/659425.png" height="24" width="42" />
<strong>Green</strong>, the colour that says “go ahead, proceed with the task at hand”, is used for positive <strong>action elements</strong>, such as statements (if/then, while/do, case…), mode indicators (insert, visual…), vim user prompts, and diff additions.</p>

<p><img src="http://www.colorhexa.com/3e947e.png" height="24" width="42" />
<strong>Teal</strong> is named after the “common teal”, a kind of duck, thus connecting this colour with the concept of “species”, which is a means of classifying life into very specific types. Teal is therefore used for specifying <strong>object types</strong>, such as data type (boolean, integer, string…) or storage class (static, volatile…), as well as mislocalized words (that is, words that are not misspelled but of the wrong type, namely a foreign type).</p>

<p><img src="http://www.colorhexa.com/3f8abf.png" height="24" width="42" />
<strong>Blue</strong>, a colour of calm stability, is used for <strong>constants</strong>, which come in the form of boolean values, integers, floating-point numbers, characters, and strings.</p>

<p><img src="http://www.colorhexa.com/7d6fbf.png" height="24" width="42" />
<strong>Purple</strong>, often associated with rare purple dyes historically produced for special works of art, is used for <strong>special text</strong>, including special characters (standalone or within syntax units), vim tags, and debugging statements. Rarely-used words are also marked, allowing the writer to consider whether such a specially uncommon word is appropriate.</p>

<p><img src="http://www.colorhexa.com/bf6fab.png" height="24" width="42" />
<strong>Pink</strong>, the colour of spring blossoms, is used for <strong>object names</strong>, including the names of variables and functions. To code is to bring countless objects blossoming into existence as one types their names.</p>
