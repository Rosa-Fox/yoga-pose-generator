# yoga-pose-generator
Yoga Pose Generator put together put together as an example before mentoring at Codebar - Mind the Code

clone the repo and `cd`

Make sure you have Ruby installed https://www.ruby-lang.org/en/downloads/

```gem install bundler```

```
bundle install
```

Download and install [PostgreSQL](http://www.postgresql.org/download/)
Add a development database:

```bash
$ createdb development
```

Start the local server

```
rackup
```

Navigate to http://localhost:9292

Create a public/images folder and add images. I didn't push them to Github as I don't own them. Then make sure the images in your database have the same file names as the names of the poses in your database.

To query/add stuff to the db using the command line (make sure you `cd` into the root directory:

```
pry
```

```
require './server'
```

```
Pose.all
```

```
Pose.create
```

```
Pose.get(1)
```

etc

More here http://cheat.errtheblog.com/s/datamapper
