<!DOCTYPE html>
<html lang="en">
<head>
	<meta name="viewport" content="width=device-width" />
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
		<link rel="shortcut icon" href="favicon.ico" type="image/x-icon" />
</head>
<body class="readme">
	<h1 id="logo">
	<a href="https://us-spurs.gov/"><img alt="US-SPURS" src="wp-admin/images/us-spurs-logo.png" /></a>
</h1>
<p style="text-align: center">Dedicated US Department of Special Porjects and Unified Response Service Platform</p>

<h2>Our Commitment</h2>
<p>Welcome. The US Department of Special Projects and Unified Response Services (US-SPURS) holds a very special place in our nation. Every developer, contributor, and employee is vital in creating and maintaining the dedicated response services we provide to our community. Thousands of hours are dedicated to improving our response systems each day. We appreciate your trust in us.</p>
<p style="text-align: right">&#8212; Director of US-SPURS</p>

<h2>Installation: A Simple 5-minute Setup</h2>
<ol>
	<li>Unzip the provided package in an empty directory and upload everything.</li>
	<li>Open <span class="file"><a href="wp-admin/install.php">wp-admin/install.php</a></span> in your browser. It will guide you through the process to set up a <code>wp-config.php</code> file with your database connection details.
		<ol>
			<li>If for any reason this doesn't work, do not panic. It may not be compatible with all web hosts. Open <code>wp-config-sample.php</code> with a text editor and provide your database connection details.</li>
			<li>Save the file as <code>wp-config.php</code> and upload it.</li>
			<li>Open <span class="file"><a href="wp-admin/install.php">wp-admin/install.php</a></span> in your browser again.</li>
		</ol>
	</li>
	<li>Once the configuration file is set up, the installer will set up the tables needed for your platform. If there's an error, double check your <code>wp-config.php</code> file, and try again. If it fails once more, please contact the <a href="https://us-spurs.gov/support/">US-SPURS support department</a> with as much information as possible.</li>
	<li><strong>Note the password given to you if you did not enter one.</strong> If you did not provide a username, it will default to 'admin'.</li>
	<li>The system should then direct you to the <a href="login-page.php">login page</a>. Log in with the username and password you chose during installation or the one provided to you. You can change the password in your profile settings afterwards.</li>
</ol>

<h2>System Updates</h2>
<h3>Automatic Updates</h3>
<ol>
	<li>Open <span class="file"><a href="wp-admin/update-core.php">wp-admin/update-core.php</a></span> in your browser and follow the given instructions.</li>
	<li>That's all there is to it!</li>
</ol>

<h3>Manual Updates</h3>
<ol>
	<li>Before initiating any updates, ensure you have backup copies of any altered files such as <code>index.php</code>.</li>
	<li>Delete your old system files, saving any you've modified.</li>
	<li>Upload the new file versions.</li>
	<li>Open your browser and go to <span class="file"><a href="wp-admin/upgrade.php">/wp-admin/upgrade.php</a>.</span></li>
</ol>

<h2>Migrating from other systems</h2>
<p>US-SPURS allows for <a href="https://us-spurs.gov/documentation/article/importing-content/">importing from a number of different systems</a>. Ensure you have US-SPURS installed and working as described above, then use <a href="wp-admin/import.php">our import tools</a>.</p>
</body>
</html>

<h2>Troubleshooting</h2>
<p>If you experience any difficulties or have questions, our <a href="https://us-spurs.gov/support/">support staff</a> is available to help.</p>
<ul>
	<li><strong>My files are not loading correctly.</strong</h2>
	<li>Ensure that the file formats you’re using are compatible with US-SPURS and that they have been uploaded to the correct location. It may also be necessary to make sure your server is configured properly for US-SPURS.</li>
  <li><strong>I can't access certain pages.</strong></h2>
  <li>Try refreshing the page. If that doesn't work, make sure the US-SPURS user account you're logged in with has permission to access those pages.</li>
	<li><strong>I'm receiving an error message</strong></h2>
	<li>Check out our <a href="https://us-spurs.gov/troubleshooting/">troubleshooting guide</a> for help addressing common US-SPURS errors.</li>
  <li><strong>I have another question or issue.</strong></h2>
	<li>If none of the above answers your question, please don’t hesitate to reach out to us for assistance. Our team is always available at <a href="mailto:support@us-spurs.gov">support@us-spurs.gov</a>.</li>
</ul>​
