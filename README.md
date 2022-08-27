Dual listbox for Dash. Original component: https://rawgit.com/jyotirmaybanerjee/react-duallist/master/example/examples.html#

Install using:
<code>pip install dash-dual-listbox</code>

************************************************************************
<code>pip install dash-dual-listbox</code> installs a version that contains packages which no longer work. In that version, callbacks are broken.

The DualList.py file will need to be rebuilt. 

To do this:

- Make sure you have <code>node.js</code> and <code>npm</code> installed
- <code>git clone https://github.com/vivekvs1/dash-dual-listbox.git</code>
- cd dash-dual-listbox
- npm install
- npm run build:js
- npm run build:py

You can now run: <code>python setup.py install</code> to install the dash-dual-listbox to your packages

To get the list box to show up properly styled:
- copy the style.css file from <code>dash_dual_listbox/style.css</code> to an <code>assets</code> folder in your dash app

Check out the `usage.py` file for usage
