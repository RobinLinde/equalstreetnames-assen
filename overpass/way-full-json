[out:json][timeout:300];
( area["admin_level"="10"]["ref:woonplaatscode"="2391"]["wikidata"="Q798"]; )->.a;
(
	way["highway"]["name"]["highway"!="bus_stop"]["highway"!="raceway"](area.a);
	way["place"="square"]["name"](area.a);
);
out body;
>;
out skel qt;