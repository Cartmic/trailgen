# Trailgen
Trailgen is a Minetest C++ v6-like mapgen which uses the biome api.
This is very much an alpha release and things are needing to be tweaked but where it is now it is perfectly playable!

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
