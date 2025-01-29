# Chameleon Management
https://chameleonmode.com/

## 1/29/2025
### 2025.0.1.*
1. multy tenants per email or multi data interactions ie: cooky sync
    - moved to [2025.0.2.* / App / 1.](#app)
2. only oauth0 for login tenants..
    - moved to [2025.0.2.* / App / 1.](#app)
3. folder sharing
    - in outsourcer module whatever projects is in that folder
    - (maybe also add whatever is shared within a specific tag in enough time after finishing 4. provisioned settings )
    - db + chameleon.app
4. provisioned settings 
    - per profile->per folder>per tags(geo/timezones..)>what oiutsourcer can see what other outsourcers
    - db + chameleon.app
5. autoupdate 
    - simpile executable that verifies user and downloads the zip from render.com
    - db + chameleon.app
6. pings when already open from toolbar
    - QA + chameleon.app

### 2025.0.2.*
#### AI & Browser Automation
1. Reddit
    - AI api + db + chameleon.app + qa
#### App
1. migrate app login from popup to auth0
    - auth0 + db
    - sql migration script to the format created users without a license linked to a tennantId
