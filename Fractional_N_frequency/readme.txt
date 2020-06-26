for example you want to generate nume/deno frequence signal
essentially,you are going ro have to output deno pulses in a clock of nume inputs
first calculate nume/deno = quot...remd
so quot = nume/demo, remd = nume%demo
this requires remd  of "quot+1" frequency divison
and (deno-remd) of quot frequence division
calculate: remd*(quot+1)+(deno-remd)*quot = deno*quot+remd
