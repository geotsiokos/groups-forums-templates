groups-forums-templates
=======================

Theme templates for the <a href="http://www.itthinx.com/plugins/groups-forums/">Groups Forums</a> WordPress plugin.

This repository gathers theme-specific templates for Groups Forums.

Themes
------

Groups Forums integrates automatically with the active theme.
It does not impose a specific look on forums, instead it uses the active theme to represent forums and topics, just like normal categories and posts are displayed.

If you would like to adjust the way things are displayed, you can use WordPress’ template system to customize how forums and topics are rendered.

In your active theme, add a groups-forums folder. You can provide template files in that folder for the type of page you want to customize, for example:

`single-topic.php` used to display a topic
`taxonomy-forum.php` used to display the topics in a forum

`taxonomy-forum-support.php` to target a specific forum, here for example the Support forum with the support slug
`archive-topic.php` for other forum archives.

Default templates, which can also be used to derive your own, are provided in the plugin’s templates folder.
Included are a `single-topic.php` and a `taxonomy-forum.php` template.

Contributing theme-specific templates
-------------------------------------

If you want to contribute theme-specific templates, fork the <a href="https://github.com/itthinx/groups-forums-templates">Groups Forums Templates</a> repository on GitHub, add a subfolder called <code>groups-forums</code> for the theme with the template files within it and issue a pull request.

If your theme is a free theme that can be downloaded, please add a readme.txt with a link to where it can be obtained.
If your theme is a premium theme, please include a link to where it can be obtained as well and provide access to a copy of the theme so your theme-specific templates can be tested.
Pull requests for themes we can not test will not be granted.

Example: Assuming you're using a theme called Foobar that is in <code>wp-content/themes/foobar</code>, add the theme templates in <code>wp-content/themes/foobar/groups-forums</code>. To have it added to the repository, fork it, add the <code>foobar/groups-forums</code> folder to the root of the repository and issue a pull request.

You should end up with the following folder structure:

<ul>
  <li>groups-forums-templates</li>
  <li>
    <ul>
      <li>foobar</li>
      <li>
        <ul>
          <li>groups-forums</li>
          <li>
            <ul>
              <li>readme.txt</li>
              <li>single-topic.php</li>
              <li>taxonomy-forum.php</li>
            </ul>
          </li>
        </ul>
      </li>
    </ul>
  </li>
</ul>
