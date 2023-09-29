here are notes how I distributed the NES banks to the SNES rom for the offsets to make sense and output usable code.

;bank 0-1 	= BANK 00 	base $8000  offset $0000  		0
;bank 7		= BANK 00 	base $C000  offset $4000		3
;bank 2-3	= BANK 01 	base $18000 offset $8000		1
;bank 4-5	= BANK 02 	base $28000 offset $10000		2
;bank 6		= BANK 03 	base $38000 offset $18000		3
;bank 8-9	= BANK 04 	base $48000 offset $20000		4
;bank a-b	= BANK 05 	base $58000 offset $28000 		5
;bank c-d	= BANK 06 	base $68000 offset $30000		6
;bank e-f	= BANK 07 	base $78000 offset $38000		7
;bank 10-11	= BANK 08 	base $88000 offset $40000		8
;bank 12-13	= BANK 09 	base $98000 offset $48000		9
;bank 14-15	= BANK 0a 	base $a8000 offset $50000		a
;bank 16-17	= BANK 0b 	base $b8000 offset $58000		b 
;bank 18-19	= BANK 0c 	base $c8000 offset $60000		c 
;bank 1a-1b	= BANK 0d 	base $d8000 offset $68000		d 
;bank 1c-1d	= BANK 0e 	base $e8000 offset $70000		e 
;bank 1e	= BANK 0f 	base $f8000 offset $78000		f
;bank 1f	= BANK 0f 	base $fe000 offset $7e000		f 