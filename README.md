<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" type="text/css" href="../css/style.css">
  <style type="text/css">
  	body {
  font: 600 14px/24px "Open Sans", "HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", Sans-Serif;
}
h1 {
  color: #9799a7;
  font-size: 14px;
  font-weight: bold;
  margin-bottom: 6px;
}
.container:before,
.container:after {
  content: "";
  display: table;
}
.container:after {
  clear: both;
}
.container {
  background: #eaeaed;
  margin-bottom: 24px;
  *zoom: 1;
}
.container-75 {
  width: 75%;
}
.container-50 {
  margin-bottom: 0;
  width: 50%;
}
.container,
section,
aside {
  border-radius: 6px;
}
section,
aside {
  background: #2db34a;
  color: #fff;
  margin: 1.858736059%;
  padding: 20px 0;
  text-align: center;
}
section {
  float: left;
  width: 63.197026%;
}
aside {
  float: right;
  width: 29.3680297%;
}
  </style>
  <title>xample</title>
</head>
<body style="margin:0; font-family:'ubuntu', sans-serif; background-color:#2db34a;">
	<h1>100% Wide Container</h1>

<div class="container">
  <section>Section</section>
  <aside>Aside</aside>
</div>

<h1>75% Wide Container</h1>

<div class="container container-75">
  <section>Section</section>
  <aside>Aside</aside>
</div>

<h1>50% Wide Container</h1>

<div class="container container-50">
  <section>Section</section>
  <aside>Aside</aside>
</div>
</body>
</html>
