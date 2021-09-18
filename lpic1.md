cmd1 ; cmd2 ; cmd3	# run multi commands 
cmd1 && cmd2		# cmd2 runs if cmd1 runned success
cmd1 || cmd2		# cmd2 runs if cmd1 NOT runned success
cmd  > filename		# send output to filename (ovewwrite)
cmd >> filename		# append output to filename
cmd < filename		# send input data to cmd from filename
wc 					# print newline, word, and byte counts from std input or file (-l , -c, -w)
