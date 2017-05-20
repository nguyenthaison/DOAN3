# DOAN3
game trên android
<pre>
  <code>
    cd /usr/local/mysql/bin
    ./mysql -u root
    mysql> use mysql;
    mysql> update user set password=PASSWORD(“mật khẩu mới của bạn“) where User=’root’;
    mysql> flush privileges;
    mysql> quit
  </code>
</pre>

<pre>
  <code>
    var FirstMethod = React.createClass({
      render: function() {
        return <div>First Method</div>;
      }
    });
    React.render(<FirstMethod />,document.body);
  </code>
</pre>

<pre>
  <code>
    var FirstMethod = React.createClass({
      render: function() {
        return (<div>
          <div>Name: {this.props.name}</div>
          <div>Address: {this.props.address}</div>
          <NestedView />
          </div>
        );
      }
    });
    var NestedView = React.createClass({
      render: function(){
        return <div>Good Bye</div>;
      }
    });
    React.render(<FirstMethod name={"Test"} address={"test"} />,document.body);
  </code>
</pre>

<pre>
  <code>
    document.write('welcome to my app');
    console.log('app loaded');
  </code>
</pre>


<pre>
  <code>
    <html>
      <body>
        <script src="bundle.js"></script>
      </body>
    </html>
  </code>
</pre>

<pre>
  <code>
    $webpack --watch
  </code>
</pre>

<pre>
  <code>
    module.exports = {
      entry: "./app.js",
      output: {
        filename: "bundle.js"
      }
    }
  </code>
</pre>

<pre>
  <code>
    module.exports = {
      entry: "./app.js",
      output: {
        filename: "bundle.js"
      },
      watch: true
    }
  </code>
</pre>

<pre>
  <code>
    module.exports = {
     entry: "./app.js",
     output: {
       filename: "bundle.js"
     },
     module: {
       loaders: [
         {
           test: /\.js$/,
           exclude: /node_modules/,
           loader: 'babel-loader',
           query: {
             presets: ['react', 'es2015']
           }
         }
       ]
     },
     resolve: {
       extensions: ['', '.js']
     },
    }
  </code>
</pre>
    
