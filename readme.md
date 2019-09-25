<h1>
    <br>
    <img src="https://hackernoon.com/hn-images/1*JfSp7LWmVE1nj15IrxWSWQ.png" alt="Docker" width="200" style="max-width:100%;">
   
</h1>

## Golang with Docker

You don't need install Go in yout local environment. We only installed Docker, and from here to forth you won’t need to install other runtimes if you don’t want, just use a this Docker image and run a container with the required environment.


[Golang documentation](https://golang.org/doc/).

## Run

Make sure your have [Docker](https://docker.com) installed

Clone repo
<pre>
    <code>$ git clone https://github.com/fabiovalencio/docker-golang app-go && cd app-go</code>
</pre>

Build Docker image
<pre>
    <code>docker build . -t golang-image</code>
</pre>

Run the container 
<pre>
    <code>docker run fabiovalencio/codeeducation </code>
</pre>

Try it!
<b>Go to your browser and navigate to localhost:3030. You’ll see a text saying “Code.education Rocks!”. That’s it! It’s alive!</b>


## Image

[fabiovalencio/codeeducation](https://cloud.docker.com/u/fabiovalencio/repository/docker/fabiovalencio/codeeducation)

