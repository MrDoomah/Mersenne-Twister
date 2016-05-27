# Mersenne-Twister
Mersenne-Twister RNG for Factorio

function seed_mt(seed): 

	Set a seed.
	Seed should be an integer above 0.
function random(p, q): 

	Get a random number.
	Works the same as math.random in the lua standard library.
	If called before setting a seed, it will use the map seed.
