# ARO-Demo

Deploy MongoDB:

oc process mongodb-persistent -p MONGODB_USER=ratinguser -p MONGODB_PASSWORD=ratingspassword -p MONGODB_DATABASE=ratingsdb -p MONGODB_ADMIN_PASSWORD=ratingspassword | oc create -f -

