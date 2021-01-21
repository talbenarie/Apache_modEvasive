26 August 2019 2.0
09 February 2020 Update to 2.2.0


                                           Apache Lounge Distribution

                                       mod_evasive 2.2.0 for Apache 2.4 Win64 VS16

# Original Home: https://github.com/jvdmr/mod_evasive
# Binary by: Steffen
# Mail: info@apachelounge.com
# Home: http://www.apachelounge.com/

Changelog www.apachelounge.com/viewtopic.php?p=31065

Build with Visual Studio® 2019 (VS16)

# Install:

- Copy mod_evasive.so to your modules folder 


# Add to your httpd.conf

LoadModule evasive_module modules/mod_evasive.so

<IfModule evasive_module>
    DOSEnabled          true
    DOSHashTableSize    3097
    DOSPageCount        2
    DOSSiteCount        50
    DOSPageInterval     1
    DOSSiteInterval     1
    DOSBlockingPeriod   10
</IfModule>


# Directives provided by mod_evasive

Defaults:

    DOSEnabled          true
    DOSHashTableSize    3097
    DOSPageCount        2
    DOSSiteCount        50
    DOSPageInterval     1
    DOSSiteInterval     1
    DOSBlockingPeriod   10
 
Other directives and info , see:

 https://github.com/jvdmr/mod_evasive/blob/master/README.md
