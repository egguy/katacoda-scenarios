# eBot's configuration


## ebot configuration


  EXTERNAL_IP: 'xxx.xxx.xxx.xxx' => put the ip of the machine

Don't touch this configuration if you use the integreated mysql docker image.
You can use a local mysql instance 

    MYSQL_HOST: 'mysql'
    MYSQL_PORT: '3306'
    MYSQL_DB: 'ebotv3'
    MYSQL_USER: 'ebotv3'
    MYSQL_PASS: 'ebotv3'

Configure as requested

    LO3_METHOD: 'restart'
    KO3_METHOD: 'restart'
    DEMO_DOWNLOAD: 'true'
    REMIND_RECORD: 'false'
    DAMAGE_REPORT: 'true'
    DELAY_READY: 'false'

## ebot web configuration

put the same external IP

    EBOT_IP: 'xxx.xxx.xxx.xxx'
    EBOT_PORT: '12360' => don't touche the default port

Password and user for the admin.php access, can be changed later

    EBOT_ADMIN_USER: 'admin'
    EBOT_ADMIN_PASS: 'password'
    EBOT_ADMIN_MAIL: ''

Same remark as before

    MYSQL_HOST: 'mysql'
    MYSQL_PORT: '3306'
    MYSQL_DB: 'ebotv3'
    MYSQL_USER: 'ebotv3'
    MYSQL_PASS: 'ebotv3'

Make the demo downloadable 

    DEMO_DOWNLOAD: 'true'

The tournament key if you want the autofill of tournament

    TOORNAMENT_ID: ''
    TOORNAMENT_SECRET: ''
    TOORNAMENT_API_KEY: ''
    TOORNAMENT_PLUGIN_KEY: ''