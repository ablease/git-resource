This is a forked version of the official git concourse resource which includes any commit
on any branch whose message matches the (case insenstive) pattern '\[finishes.*\]'

To build:

docker build -t servicesapi/git-all-branches .
