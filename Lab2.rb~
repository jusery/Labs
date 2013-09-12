# Part1: Hello World
class HelloWorldClass
    def initialize(name)
       @name = name.capitalize
    end
    def sayHi
        puts "Hello #{@name}!"
    end
end
hello = HelloWorldClass.new("{John Usery}")
hello.sayHi

#Part 2: Palindrome
#Part a
puts "Problem 2a"

puts "Type a Palindrome"
x = gets

def palindrome?(string)

  	x = string.downcase.scan(/\w/)
	x == x.reverse
		
end

p palindrome?(x)

#Part b
puts "Problem 2b"
puts "Type a string of words"
phrase = gets
def count_words(string)
   	y = Hash.new(0)
	syb = string.gsub(/\W+/, ' ')
	nib = syb.downcase
	tip = nib.split
	tip.each do |word|
		if y.has_key? word
			y[word] += 1
		else
			y[word] = 1
		end
	end
	return y

end

p count_words(phrase)


