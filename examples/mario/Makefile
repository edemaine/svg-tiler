all: castle underground underwater overworld

castle:
	echo \"castle\" >palette.json
	svgtiler -P mario.coffee door.tsv
	mv door.svg door_castle.svg
	mv door.png door_castle.png

overworld:
	echo \"overworld\" >palette.json
	svgtiler -P mario.coffee door.tsv
	mv door.svg door_overworld.svg
	mv door.png door_overworld.png

underground:
	echo \"underground\" >palette.json
	svgtiler -P mario.coffee door.tsv
	mv door.svg door_underground.svg
	mv door.png door_underground.png

underwater:
	echo \"underwater\" >palette.json
	svgtiler -P mario.coffee door.tsv
	mv door.svg door_underwater.svg
	mv door.png door_underwater.png
