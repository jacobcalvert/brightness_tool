<p>This is a python utility to control the brightness on my HP Pavillion DV7 because the hardware buttons don't work nor does the software slider in Linux Mint 17.</p>


<h4>Basic usage</h4>

<p>brightness_tool [set|get|inc|dec] arg0</p>

<h4>Examples</h4>

<ul>
	<li>'brightness_tool set 10' will set the brightness to 10% </li>
	<li>'brightness_tool inc 4' will increase the current brightness by 4%</li>
	<li>'brightness_tool dec 12' will decrease the current brightness by 12%</li>
	<li>'brightness_tool set max' will set the brightness to 100%</li>
	<li>'brightness_tool set min' will set the brightness to 5%</li>
	<li>'brightness_tool inc' will increase the current brightness by the default (10%)</li>
	<li>'brightness_tool dec' will decrease the current brightness by the default (10%)</li>
</ul>

<h4>How to install</h4>
<p>Download the file, copy it to /usr/local/bin/brightness_tool and make it executable. (chmod +x /usr/local/bin/brightness_tool)</p>
