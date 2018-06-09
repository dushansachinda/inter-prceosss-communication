'{"Name":"Bob", "Address":"20, Palm Grove, Colombo, Sri Lanka", 
   "ContactNumber":"+94777123456"}'


curl -v -X POST -d \
   '{"Name":"Dushan", "pickupaddr":"1817, Anchor Way, San Jose, US", 
   "ContactNumber":"0014089881345"}' \
   "http://localhost:9090/trip-manager/pickup" -H "Content-Type:application/json" 