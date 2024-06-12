To Initialize:
--------------

    git clone https://github.com/xmstone/local_manifests.git -b BRANCH_NAME .repo/local_manifests
    

To Sync:
--------

    repo sync --force-sync -j8 --current-branch --no-tags --no-clone-bundle --optimized-fetch --force-broken
