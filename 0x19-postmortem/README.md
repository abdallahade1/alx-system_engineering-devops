##My first postmortem
#Issue Summary 
On March 24, 2017, from 07:32 AM to 07:52 AM GMT, our flagship service experienced a 20-minute outage, impacting 68% of our user base. Users attempting to access the website were met with a disheartening "500 Internal Server Error", robbing them of the joy of browsing our otherwise impeccable content. The root cause was an incorrect Apache server configuration that channeled the digital spirit of "The Twilight Zone" into our system.
#Timeline
07:32 AM GMT: The issue was detected when our coffee-powered engineers received a cascade of alerts from our monitoring system, coupled with a flood of customer complaints reminiscent of a Shakespearean tragedy.
07:35 AM GMT: Initial assumptions pointed to a recent deployment; however, the engineers, after a caffeine boost, ruled out code changes and focused on configuration discrepancies.
07:40 AM GMT: The investigation took a detour into network configuration, but this path was as fruitless as a nut-free fruitcake.
07:45 AM GMT: The incident was escalated to the site reliability team, who put on their detective hats and dove into server logs and configuration files.
07:52 AM GMT: A puppet master in the form of a senior engineer discovered the misconfiguration in the Apache settings and corrected it, restoring harmony and peace to the digital realm.
#Root Cause and Resolution
The outage was caused by a mischievous Apache configuration file that decided to play hide and seek with the PHP module. Once the file was found cowering in the corner, the correct settings were restored, and the service bounced back faster than a cat chasing a laser pointer.
 
#Corrective and Preventative Measures 
Immediate Fixes: Patched the Apache server with the correct configuration and added extra monitoring for similar anomalies because our servers should be seen, not erred.
Long-Term Improvements: Implement a configuration management database (CMDB) to keep track of changes because tracking configurations manually is as outdated as flip phones.
Enhance automated testing of server configurations to include a "Does it blend?" test, ensuring it mixes well with existing settings.
Conduct a workshop on "The Art of Not Breaking Everything", mandatory for all engineers, featuring a guest lecture by Murphy—of Murphy's Law fame.
Start an "Adopt a Server" program where team members are assigned a server to care for, fostering a nurturing environment and reducing server anxiety.
