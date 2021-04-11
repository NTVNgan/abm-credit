# Fireapps Website V2


## 1. Install 

**Clone project**

**Create database**
```
Create database fireapps_website_v2
```

**Import database**

```
Import from  _database/fireapps_v2.sql.zip
```

**Change url website**
```
- Go to table options
- change option_value of siteurl and home to your url local
```

**Copy wp-config-sample.php to wp-config.php**

Change config Database
```
   /** The name of the database for WordPress */
   define( 'DB_NAME', 'fireapps_website_v2' );
   
   /** MySQL database username */
   define( 'DB_USER', 'root' );
   
   /** MySQL database password */
   define( 'DB_PASSWORD', '' );
   
   /** MySQL hostname */
   define( 'DB_HOST', 'localhost' );
```

## 2. Manage 

**Account login**
```
Go to : /wp-admin
```

**Import media uploads**

```

In admin, click Tool -> Import -> WordPress Run import 

-> Choose file (from _database/fireapps.WordPress.2020-04-08_media.xml)

-> click Upload file and import

On **Import Attachments** check  : Download and import file attachments 

-> Click Submit


```
