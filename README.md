Android TF701t and Hercules
=======

Getting Started

To get started with Android, you'll need to get familiar with Git and Repo.

To initialize your local repository using the trees, use a command like this:

repo init -u git://github.com/Geizerjin/android.git -b DU

repo init --reference=~/Bean4.3 -u git://github.com/Geizerjin/android.git -b DU

Then to sync up:

repo sync

Please see any of the official beanstalk XDA threads for building instructions.

For more information on this Github Organization and how it is structured, please read the wiki article
Buildbot

All supported devices are built nightly and periodically as changes are committed to ensure the source trees remain buildable.
