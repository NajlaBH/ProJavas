#_Cheat Sheat_ :: BUILD OPEN JDK image
# I. REQUIREMENT
### I.1 Docker
<pre>Docker version 1.9.1, build a34a1d5 </pre>
### I.2 Runing Docker on osx
```bash
bash '/Applications/Docker/Docker Quickstart Terminal.app/Contents/Resources/Scripts/start.sh'
```
### I.3 Build the image
<pre>docker build --tag="yourTag" --file="/pathto/Dockerfile"<code>
</code></pre>
```bash
/pathto/Dockerfile
docker build . 
```
# II. RUN
### II.1 Run container
```docker run -it --rm openjdk:6```
### II.2 Check java version
```java -version```
<pre><code>OpenJDK Runtime Environment (IcedTea6 1.13.10) (6b38-1.13.10-1~deb7u1)
OpenJDK 64-Bit Server VM (build 23.25-b01, mixed mode)</code></pre>

# III. RESSOURCES
### III.1 Documentation
<ul>
<li>Docker official image for openjdk : <a href="https://github.com/docker-library/openjdk/blob/master/6-jdk/Dockerfile">https://github.com/docker-library/openjdk/blob/master/6-jdk/Dockerfile</a> </li>
<li>Start a Java instance in your app : <a href="https://hub.docker.com/_/openjdk/">https://hub.docker.com/_/openjdk/</a> </li>
</ul>
<h1 id='idtitle4'>IV. Issues and Contributing</h1> 
<h2>IV.1/ Support</h2>
<p>
If you are having issues, please let me know.
</p>
<h2>IV.2/ Contribute</h2>
<p>Bug reports, bug fixes, and new features are always welcome.<br>
* Issue Tracker: <a href="https://github.com/NajlaBioinfo/ProJavas/issues">github</a><br>
* Source Code: <a href="https://github.com/NajlaBioinfo/ProJavas/pulls">github</a></p>
<h2 id='idtitleE'>IV.3/ Authors and Maintainers</h2>
<p>BEN HASSINE NAJLA : <a href="MAILTO:bhndevtools@gmail.com?Subject=ProJavas-OJDK6">bhndevtools@gmail.com</a></p>
<section style="font: bold;color:green;align:center;font-size:small;">
<footer>BHNtools©copyrights-2016<br></section>License MIT.</footer>
</article>

