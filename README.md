Start the spring boot application DemoApplication.
Then execute GET request to http://localhost:3699/get

In the logs:
<pre><code>
2018-11-04 16:54:20.878 DEBUG <span style="color:yellow">[-,0a51be4ab4ab96aa,0a51be4ab4ab96aa,false]</span> 95164 --- [ctor-http-nio-3] com.example.demo.DemoApplication         : Pre filter
2018-11-04 16:54:21.201 DEBUG <span style="color:yellow">[-,,,]</span> 95164 --- [ctor-http-nio-4] com.example.demo.DemoApplication         : Post filter
</code></pre>