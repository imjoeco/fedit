fedit
=================

Fedit is a responsive form field text editor built using plain Javascript and CSS.

Demo: [fedit Demo](http://www.shiftypages.com/posts/12)

How To Use
-----------------

To use, simply include the fedit folder in your site's public directory and add the following to your head tag:

    <link href="/fedit/fedit.css" rel="stylesheet" type="text/css">

and the following at the bottom of your body tag:

    <script src="/fedit/fedit.js" type="text/javascript"></script>

After that, you can use the field editor by adding the class "fedit" to your form and fedit.js will automatically convert the form fields to contenteditable divs that work with the editor. 

To style the field you can then wrap the fields in the content tags as you would on the display page.

If you want to disable the editor while still keeping the styling capabilities just add the class "no-fedit" to the fields you wish to diable the editor.

For example:

    <form class="fedit">
      <h1 class="post-title">
        <input type="text" name="title" class="no-fedit">
      </h1>
    
      <p class="post-content">
        <input type="text" name="content">
      </p>
    
      <input type="submit" value="Save Post">
    </form>

Will create an editable form with the editor disabled for the title field as demonstrated on the demo site.

License
----------------

Copyright 2014 Joseph Hernandez

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
