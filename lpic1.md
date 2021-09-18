shell I/O
	cat 				# prints a file to stdout
	cat -b              # prints non-blank numbered lines
	cut -d <seprator> -f <col NO> /etc/passwd
	# seprate a file with seprator and send specified column
	echo				# shows a msg or variable 
	less                # show stdout in nice way, it should be piped after other commands
	cmd1 ; cmd2 ; cmd3	# run multi commands 
	cmd1 && cmd2		# cmd2 runs if cmd1 runned success
	cmd1 || cmd2		# cmd2 runs if cmd1 NOT runned success
	cmd  > filename		# send output to filename (ovewwrite)
	cmd >> filename		# append output to filename
	cmd < filename		# send input data to cmd from filename
	wc 					# print newline, word, and byte counts from std input or file (-l , -c, -w)
	grep -i				# find something from std input or file (-i for ignore case)
	uniq                # report or omit repeated lines
	tr                  # Translate, squeeze, and/or delete characters from standard input

	# Example
	# $ sort < temp.txt | uniq -c | sort -nr
	#  5 mina
	#  3 ali
	#  2 sara
	#  2 reza
	#  2 keyvan
	#  1 jafar

	sed 's/old/new/'    # it replaces first old word of each line wiith new like vim 
	sed 's/old/new/g'   # it replaces globaly
	sed -E 's/old/new/' # it support regex
