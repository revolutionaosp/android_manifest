# RevolutionOS Pie #


# Initialize local repository
repo init -u https://github.com/RevolutionOS-P/android_manifest -b pie

# Sync
repo sync -c -jx --force-sync --no-clone-bundle --no-tags


### Build ###


# Set up environment
$ . build/envsetup.sh

# Choose a target
$ brunch $target
