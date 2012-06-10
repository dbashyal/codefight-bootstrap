codefight-bootstrap
===================

Codefight's Bootstrap JS to style form inputs and etc...

before:
-------
&lt;input class="btn btn-danger" name="delete" type="submit" id="delete" value="Delete Selected"/&gt;
after:
------
&lt;button class="btn btn-danger"&gt;&lt;i class="icon-trash icon-white"&gt;&lt;/i&gt;&nbsp;Delete Selected&lt;/button&gt;&lt;span class="hide"&gt;&lt;input type="submit" value="Delete Selected" id="delete" name="delete" class="btn btn-danger"&gt;&lt;/span&gt;

before:
-------
&lt;input data-cfbootstrap-options='{"delete":"minus-sign"}' class="btn btn-danger" name="delete" type="submit" id="delete" value="Delete Selected"/&gt;
after:
------
&lt;button class="btn btn-danger"&gt;&lt;i class="icon-minus-sign icon-white"&gt;&lt;/i&gt;&nbsp;Delete Selected&lt;/button&gt;&lt;span class="hide"&gt;&lt;input type="submit" value="Delete Selected" id="delete" name="delete" class="btn btn-danger"&gt;&lt;/span&gt;

This will be added to new codefight cms.

Thanks to zenorocha for the plugin skeleton - https://github.com/zenorocha/jquery-plugin-patterns