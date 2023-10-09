FROM mongo

COPY pets.js /pets.js
CMD mongoimport --host mongodb --db reach-engine --collection MyDummyCollection --type json --file /pets.js --jsonArray

