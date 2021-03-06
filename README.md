# tilder

<?xml version="1.0" ?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="content-type" content="text/html; charset=utf-8" />
<link rev="made" href="mailto:" />
</head>

<body>



<ul id="index">
  <li><a href="#NAME">NAME</a></li>
  <li><a href="#SYNOPSIS">SYNOPSIS</a></li>
  <li><a href="#DESCRIPTION">DESCRIPTION</a></li>
  <li><a href="#OPTIONS">OPTIONS</a></li>
  <li><a href="#EXAMPLES">EXAMPLES</a></li>
  <li><a href="#REQUIREMENTS">REQUIREMENTS</a></li>
  <li><a href="#SEE-ALSO">SEE ALSO</a></li>
  <li><a href="#AUTHOR">AUTHOR</a></li>
  <li><a href="#COPYRIGHT">COPYRIGHT</a></li>
  <li><a href="#LICENSE">LICENSE</a></li>
</ul>

<h1 id="NAME">NAME</h1>

<p>tilder - File backup assistant</p>

<h1 id="SYNOPSIS">SYNOPSIS</h1>

<pre><code>    python tilder.py [-h] [--ts_lev {d,dt,none}] [--ts_pos {bef,aft}]
                     [--nopause] file [file ...]</code></pre>

<h1 id="DESCRIPTION">DESCRIPTION</h1>

<pre><code>    Back up your files into respective subdirectories
    with explicit timestamps.</code></pre>

<h1 id="OPTIONS">OPTIONS</h1>

<pre><code>    -h, --help
        Help message

    --ts_lev {d,dt,none}
        d (default)
            Timestamping up to yyyymmdd
        dt
            Timestamping up to yyyymmdd_hhmm
        none
            No timestamping

    --ts_pos {bef,aft}
        bef
            Timestamping before the filename
        aft (default)
            Timestamping after the filename

    --nopause
        The shell will not be paused at the end of the program.

    file ...
        List of files to be backed up.</code></pre>

<h1 id="EXAMPLES">EXAMPLES</h1>

<pre><code>    python tilder.pl oliver.eps heaviside.dat --nopause
    python tilder.pl bateman.ps --ts_lev=d</code></pre>

<h1 id="REQUIREMENTS">REQUIREMENTS</h1>

<p>Python 3</p>

<h1 id="SEE-ALSO">SEE ALSO</h1>

<p><a href="https://github.com/jangcom/baker">baker: Sister Perl program</a></p>

<h1 id="AUTHOR">AUTHOR</h1>

<p>Jaewoong Jang &lt;jangj@korea.ac.kr&gt;</p>

<h1 id="COPYRIGHT">COPYRIGHT</h1>

<p>Copyright (c) 2018-2020 Jaewoong Jang</p>

<h1 id="LICENSE">LICENSE</h1>

<p>This software is available under the MIT license; the license information is found in &#39;LICENSE&#39;.</p>


</body>

</html>