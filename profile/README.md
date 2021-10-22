<p align="center">
  <a href="https://github.com/dotenv-linter/dotenv-linter">
    <img alt="dotenv-linter"
         width="350" height="192"
         src="https://raw.githubusercontent.com/dotenv-linter/dotenv-linter/master/logo.svg?sanitize=true">
  </a>
</p>

<h2 align="center">
⚡️Lightning-fast linter for <code>.env</code> files. Written in Rust 🦀
</h2>

Dotenv-linter can **[check](https://github.com/dotenv-linter/dotenv-linter#-check)** / **[fix](https://github.com/dotenv-linter/dotenv-linter#-fix)** / **[compare](https://github.com/dotenv-linter/dotenv-linter#-compare)** `.env` files for problems that may cause the application to malfunction.

**Available checks**:

<p>
&nbsp;&nbsp;&nbsp;&nbsp;✅&nbsp;<a href="https://dotenv-linter.github.io/#/checks/duplicated_key">Duplicated Key</a><br />
&nbsp;&nbsp;&nbsp;&nbsp;✅&nbsp;<a href="https://dotenv-linter.github.io/#/checks/ending_blank_line">Ending Blank Line</a><br />
&nbsp;&nbsp;&nbsp;&nbsp;✅&nbsp;<a href="https://dotenv-linter.github.io/#/checks/extra_blank_line">Extra Blank Line</a><br />
&nbsp;&nbsp;&nbsp;&nbsp;✅&nbsp;<a href="https://dotenv-linter.github.io/#/checks/incorrect_delimiter">Incorrect delimiter</a><br />
&nbsp;&nbsp;&nbsp;&nbsp;✅&nbsp;<a href="https://dotenv-linter.github.io/#/checks/key_without_value">Key without value</a><br />
&nbsp;&nbsp;&nbsp;&nbsp;✅&nbsp;<a href="https://dotenv-linter.github.io/#/checks/leading_character">Leading character</a><br />
&nbsp;&nbsp;&nbsp;&nbsp;✅&nbsp;<a href="https://dotenv-linter.github.io/#/checks/lowercase_key">Lowercase key</a><br />
&nbsp;&nbsp;&nbsp;&nbsp;✅&nbsp;<a href="https://dotenv-linter.github.io/#/checks/quote_character">Quote character</a><br />
&nbsp;&nbsp;&nbsp;&nbsp;✅&nbsp;<a href="https://dotenv-linter.github.io/#/checks/space_character">Space character</a><br />
&nbsp;&nbsp;&nbsp;&nbsp;✅&nbsp;<a href="https://dotenv-linter.github.io/#/checks/substitution_key">Substitution Key</a><br />
&nbsp;&nbsp;&nbsp;&nbsp;✅&nbsp;<a href="https://dotenv-linter.github.io/#/checks/trailing_whitespace">Trailing whitespace</a><br />
&nbsp;&nbsp;&nbsp;&nbsp;✅&nbsp;<a href="https://dotenv-linter.github.io/#/checks/unordered_key">Unordered Key</a><br />
</p>

**What is a `.env` file?**

<p>
&nbsp;&nbsp;&nbsp;&nbsp;💡&nbsp;A <code>.env</code> file or <code>dotenv</code> file is a simple text file containing all the environment variables of a project.<br /> &nbsp;&nbsp;&nbsp;&nbsp;Storing <a href="https://12factor.net/config">configuration in the environment variables</a> is one of the tenets of the <a href="https://12factor.net">Manifesto of Twelve-Factor App</a>.<br />
&nbsp;&nbsp;&nbsp;&nbsp;The <code>.env</code> file has a simple key-value format, for example: <code>FOO=BAR</code>.<br />
&nbsp;&nbsp;&nbsp;&nbsp;More information you can find in articles in <a href="https://evrone.com/dotenv-linter?utm_source=github&utm_campaign=dotenv-linter">English</a> and <a href="https://www.mgrachev.com/2020/04/20/dotenv-linter">Russian</a>.
</p>

**The key features**:

<p>
&nbsp;&nbsp;&nbsp;&nbsp;⚡️&nbsp;Lightning-fast because it is written in Rust 🦀<br />
&nbsp;&nbsp;&nbsp;&nbsp;💣&nbsp;Can be used on any project regardless of the programming language 💥<br />
&nbsp;&nbsp;&nbsp;&nbsp;🚀&nbsp;Can be integrated with <a href="https://github.com/reviewdog/reviewdog">reviewdog</a> and other CI services (including <a href="https://github.com/dotenv-linter/action-dotenv-linter">GitHub Actions</a> and <a href="https://github.com/github/super-linter">Super-Linter</a>) 🔥
</p>
