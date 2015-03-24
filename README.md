uservoice-to-freshdesk-importer
===============================

# Overview

First export tickets from uservoice using their portal

# Dependencies

gem install trollop
gem install nokogiri

# Example run
<pre>
uv-to-fd-importer
  Description: Import an exported UserVoice csv into freshdesk.
  --type: takes values ['articles','tickets','users','suggestions']

  Usage:
  uv-to-fd-importer [options]

  where [options] are:
  -v, --verbose         Verbose output
  -u, --username=    Freshdesk username
  -p, --password=    Freshdesk password
  -d, --domain=      Freshdesk domain (default: myorg.freshdesk.com)
  -t, --type=        Type of CSV export
  -c, --csv=         csv file to read from
  -e, --version         Print version and exit
  -h, --help            Show this message
</pre>
