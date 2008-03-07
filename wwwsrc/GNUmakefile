all: status.mdwn
	ikiwiki --setup ikiwiki.setup

%: %.m4
	m4 -P $< >$@
