# Trailgen
Trailgen is a Minetest C++ v6-like mapgen which uses the biome api.

This version is for Minetest-5.6.1

![Trailgen Example](screenshot.png?raw=true "Trailgen example screenshot with custom textures.")

# Installation:

Replace the files in the 'trailgen/minestest' folder into the relevant places.

---------
~~~
minetest_source_directory
		---->builtin
			---->mainmenu
				---->dlg_create_world.lua
			---->settingtypes.txt
		---->src
			---->mapgen
				---->CMakeLists.txt
				---->mapgen.h
				---->mapgen.cpp
				---->mapgen_trailgen.h
				---->mapgen_trailgen.cpp

		---->settings_translation_file.cpp
~~~
----------
