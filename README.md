## Chaincode Explorer - Chaincode dev Mode Web version

### Prerequisites
<pre><code>node.js - 8.9.x
npm - 5.6.0 or greator
docker - 17.06.2-ce or greater
go - 1.10.x or greater
</code></pre>

#### Start Network
<pre><code>(필수) Docker Setting - Expose deamon on tcp://localhost:2375 without TLS 체크

<pre><code>./startNetwork.sh</code></pre>

#### Start Application 

<pre><code>Powershell(관리자권한)에서 npm install -g windows-build-tools</code></pre>

<pre><code>cd web</code></pre>

<pre><code>npm install</code></pre>

<pre><code>npm start</code></pre>

