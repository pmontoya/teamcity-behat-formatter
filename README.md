teamcity-behat-formatter
========================

Behat tests formatter for TeamCity

behat.xml:

<pre>
default:
  formatters:
    teamcity:
      name: teamcity
  extensions:
    Behat\TeamCity\TeamCityFormatterExtension:
      name: teamcity
</pre>
