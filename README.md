# Basketball Job Portal

CKM provides an online job portal for professional hockey players. The purpose of this project is to provide the same service to professional basketball players internationally. This portal will serve as a commmunication system to teams, agents, players, and team staff members. 

In developing this project, C# and the .NET Framework will be used to:
  * Implement player,team registration 
  * Account verification
  * Data scraping
    * [CKMSports.com](http://ckmsports.com "CKM Main Page")
    * [EliteProspects](http://jobs.eliteprospects.com "Elite Prospects Main Page")
  * Allow for team/job/player listings
  * Allow for documents to be uploaded and accessed by users
    * Contracts
    * Travel arrangement
    * Other legal documents as requested
  
# Environment
C# and .NET Framework

The existing job portal uses Azure and MySQL (2 instances)
  1. Production 
  2. Staging

The system uses SSMS (SQL Service Management Studio) as a commmunication service between in-house applications and databases

# Context Data Flow
1. Team
  * Provides
    * Travel arrangement
    * Extended offers
    * Player queries
    * Open positions
    * Messages to players
  * Receives
    * Messages from team/players
    
2. Players
  * Provides
    * Job application
    * Job search
  * Receives
    * Travel Arrangements
    * Accepted offers

3. Admin
  * Provides
    * Player upkeep
    * Verification process

4.  Agents
  * Provides
    * Player search
    * Job application 
    * Registration info
  * Receives
  
5. Team Staff
  * Provides
    * Job application
    * Job search
  * Receives
    * Accepted offers
    * Travel arrangments
  
