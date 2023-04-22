# AdministrativeCollections
The script is based on Benoit Lecours collection https://www.systemcenterdudes.com/create-operational-sccm-collection-using-powershell-script/. I extended it by some collections that I frequently implement. I have found most of the queries somewhere but can't give a complete list of references. I also commented out around 100 collections that are partially a bit obsolete and partially only useful in some cases.

Collections that where added:

- System Health | No cummulative update for more than 60 days
- System Health | WUA service disabled
- System Health | WUA service not up-to-date
- System Health | Systems that are not in AD
- System Health | No heartbeat since 30 days
- System Health | Low disk space: < 1GB
- System Health | Low disk space: < 5GB

The update interval will be set to weekly on Sunday. The time is the creation time.

Links:
https://www.systemcenterdudes.com/create-operational-sccm-collection-using-powershell-script/

https://www.andersrodland.com/ultimate-sccm-querie-collection-list/

https://www.sccm.ie/how-to/22-useful-sccm-collections-query

https://github.com/gwblok/garytown/blob/master/CreateDeviceCollections
