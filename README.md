greeting.rb
===========
def space_out_letters(person)
	return person.split("").join(" ")
end

def greet(person)
	return "h e l l o, " + space_out_letters(person)
end

def decorate_greeting(person)
	puts "" + greet(person + "")
end

decorate_greeting("john")
decorate_greeting(1)
