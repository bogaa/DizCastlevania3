here are notes how I distributed the NES banks to the SNES rom for the offsets to make sense and output usable code.

;bank 0-1 	= BANK 00 	DizBase $8000  NESoffset $0000  	0
;bank 7		= BANK 00 	DizBase $C000  NESoffset $E000		3
;bank 2-3	= BANK 01 	DizBase $18000 NESoffset $4000		1
;bank 4-5	= BANK 02 	DizBase $28000 NESoffset $8000		2
;bank 6		= BANK 03 	DizBase $38000 NESoffset $c000		3
;bank 8-9	= BANK 04 	DizBase $48000 NESoffset $10000		4
;bank a-b	= BANK 05 	DizBase $58000 NESoffset $14000 	5
;bank c-d	= BANK 06 	DizBase $68000 NESoffset $18000		6
;bank e-f	= BANK 07 	DizBase $78000 NESoffset $1c000		7
;bank 10-11	= BANK 08 	DizBase $88000 NESoffset $20000		8
;bank 12-13	= BANK 09 	DizBase $98000 NESoffset $24000		9
;bank 14-15	= BANK 0a 	DizBase $a8000 NESoffset $28000		a
;bank 16-17	= BANK 0b 	DizBase $b8000 NESoffset $2c000		b 
;bank 18-19	= BANK 0c 	DizBase $c8000 NESoffset $30000		c 
;bank 1a-1b	= BANK 0d 	DizBase $d8000 NESoffset $34000		d 
;bank 1c-1d	= BANK 0e 	DizBase $e8000 NESoffset $38000		e 
;bank 1e	= BANK 0f 	DizBase $fc000 NESoffset $3c000		f
;bank 1f	= BANK 0f 	DizBase $fe000 NESoffset $3e000		f 
