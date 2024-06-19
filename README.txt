	windows key+r
	type cmd

	pip install rawpy pillow

How to run the script

	Open command prompt
	
	Navigate to the directory where you saved raw_to_png.py:
	cd C:\Users\YourUsername\Scripts

	Run command
	python raw_to_png.py input.raw output.png --width 268 --height 324 --bit_depth 8

How to run the script about a 3channel image (aka colorful)

	Open command prompt
	
	Navigate to the directory where you saved raw_to_png_color.py:
	cd C:\Users\YourUsername\Scripts

	Run command
	python raw_to_png_color.py output.raw output.png --width 269 --height 187 --channels 3 --bit_depth 8
