# IoP-satellite
A collection of bits and pieces related to the Internet of Plants

## home, sweet home

    git@github.com:michaeldallen/IoP-satellite.git


## adopt me

    git subtree add  --message 'mtools git subtree add locator - IoP-satellite\nrepo=git@github.com:michaeldallen/IoP-satellite.git\nprefix=IoP-satellite\nbranch=master' --prefix IoP-satellite  git@github.com:michaeldallen/IoP-satellite.git master --squash


## inherit updates from the mother ship

    git subtree pull --prefix IoP-satellite git@github.com:michaeldallen/IoP-satellite.git master --squash


## push our updates to the mother ship

    git subtree push --prefix IoP-satellite git@github.com:michaeldallen/IoP-satellite.git master --squash

