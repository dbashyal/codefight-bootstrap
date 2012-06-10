codefight-bootstrap
===================

Codefight's Bootstrap JS to style form inputs and etc...

before:
-------
<input class="btn btn-danger" name="delete" type="submit" id="delete" value="Delete Selected"/>
after:
------
<button class="btn btn-danger"><i class="icon-trash icon-white"></i>&nbsp;Delete Selected</button><span class="hide"><input type="submit" value="Delete Selected" id="delete" name="delete" class="btn btn-danger"></span>

before:
-------
<input data-cfbootstrap-options='{"delete":"minus-sign"}' class="btn btn-danger" name="delete" type="submit" id="delete" value="Delete Selected"/>
after:
------
<button class="btn btn-danger"><i class="icon-minus-sign icon-white"></i>&nbsp;Delete Selected</button><span class="hide"><input type="submit" value="Delete Selected" id="delete" name="delete" class="btn btn-danger"></span>

This will be added to new codefight cms.

Thanks to zenorocha for the plugin skeleton - https://github.com/zenorocha/jquery-plugin-patterns