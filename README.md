# wsh
</li>
            <li>
              <a class="dropdown-item" href="/Tuga-Green-Hat-Hacker/wsh/blame/master/README.md">
                View blame
              </a>
            </li>

              <li class="dropdown-divider" role="none"></li>
              <li>
                <a class="dropdown-item" href="/Tuga-Green-Hat-Hacker/wsh/edit/master/README.md">Edit file</a>
              </li>
              <li>
                <a class="dropdown-item menu-item-danger" href="/Tuga-Green-Hat-Hacker/wsh/delete/master/README.md">Delete file</a>
              </li>
        </ul>
      </details>
    </div>
</div>


        <div id="readme" class="Box-body readme blob js-code-block-container p-5 p-xl-6 gist-border-0">
    <article class="markdown-body entry-content container-lg" itemprop="text"><h1 dir="auto"><a id="user-content-wsh" class="anchor" aria-hidden="true" href="#wsh"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>wsh</h1>
<p dir="auto">A shell for ignoring Android linker warning on termux!</p>
<h3 dir="auto"><a id="user-content-installation" class="anchor" aria-hidden="true" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Installation</h3>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="apt install golang git
git clone https://github.com/Tuga-Green-Hat-Hacker/wsh
cd wsh
go build
mv wsh $PREFIX/bin/
"><pre><code>apt install golang git
git clone https://github.com/Tuga-Green-Hat-Hacker/wsh
cd wsh
go build
mv wsh $PREFIX/bin/
</code></pre></div>
<h3 dir="auto"><a id="user-content-usage" class="anchor" aria-hidden="true" href="#usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Usage</h3>
<div class="highlight highlight-source-shell position-relative overflow-auto" data-snippet-clipboard-copy-content="wsh
"><pre>wsh</pre></div>
<p dir="auto">Then you will be prompted to choose your working shell! Enter your prefered shell name! in my case it's <code>bash</code></p>
<p dir="auto">Done!</p>
<p dir="auto">Now you can run <code>wsh</code> and it will cut off all of your <code>Warning: linker: *</code> messages!</p>
<h3 dir="auto"><a id="user-content-using-on-startup" class="anchor" aria-hidden="true" href="#using-on-startup"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Using on startup!</h3>
<p dir="auto">For doing this trick you need to install another login shell. ex: <code>fish</code> or <code>zsh</code></p>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="apt install zsh
"><pre><code>apt install zsh
</code></pre></div>
<p dir="auto">In my case I've used <code>zsh</code> as a parent shell!</p>
<p dir="auto">Then add this line to your <code>~/.zshrc</code></p>
<div class="highlight highlight-source-shell position-relative overflow-auto" data-snippet-clipboard-copy-content="exec wsh
"><pre><span class="pl-c1">exec</span> wsh</pre></div>
<p dir="auto">Now run</p>
<div class="highlight highlight-source-shell position-relative overflow-auto" data-snippet-clipboard-copy-content="chsh -s zsh
"><pre>chsh -s zsh</pre></div>
<p dir="auto">voila!</p>
<p dir="auto">you've been bypassed <code>WARNING: linker: Unsupported flags DT_FLAGS_1=0x8</code></p>
</article>
  </div>

    </div>

  </readme-toc>
