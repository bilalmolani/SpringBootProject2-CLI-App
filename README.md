<h1 id="introduction">Introduction</h1>
<p>This repository includes three Java applications namely Twitter CLI App, Java Grep App and JDBC App. </p>
<h1 id="twitter-cli-app">Twitter CLI App</h1>
<p>This Application allows user to Post, Delete and show Tweets through command line.</p>

<h2 id="setup">Initial Setup</h2>
After creating an application on Twitter Developer account, get access to keys and tokens. Setup those tokens and keys in your local machine's environment variables. For example:

<pre><code>#put the following env var in ~/.bash_profile
export consumerKey=
export consumerSecret=
export accessToken=
export tokenSecret=
$ source ~/.bash_profile
</code></pre>




<h2 id="usage-1">Usage</h2>

<pre><code>To Post a Tweet: TwitterCLI post "Tweet_text" "latitude:longitude"

Description: Create a tweet with a geotag and
output the created tweet object(simplifeid version)
in JSON format.
</code></pre>

<pre><code>To show a tweet: TwitterCLI show  Tweet-Id

Description: Lookup a tweet by ID and print the
tweet object in JSON format.
</code></pre>

<pre><code>To delete a Tweet: TwitterCLI delete Tweet-Id1,Tweet-Id2

Description: Delete a list of tweets by id
Output deleted tweet id and print deleted tweet
object.
</code></pre>
