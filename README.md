## 1. Counting Sheep
1. \# of sheep jump over the fence (3)
2. Another sheep jumps over the fence, Another sheep jumps over the fence, Another sheep jumps over the fence
All sheep jumped over the fence
3. return func(total - 1)
4. console.log(n + "Another sheep jumps...")

## 2. Power Calculator
1. int, exponent (int, x>=0)
2. int to the exponent 
3. func(n, x-1)
4. return n 

## 3. Reverse String
1. string
2. reversed string
3. func(str.split(str.length - 1))
4. return str[str.length -1]

## 4. nth Triangular Number
1. n
2. equilateral triangle
3. func(num - 1)
4. return num + func(num - 1)

## 5. String Splitter
1. String and Delimiter
2. Array of splits
3. splitString(string, delimiter)
4.  return [].concat(splitString(string, index, delimiter))

## 6. Fibonacci
1. num
2. Fibonacci sequence
3. func(num)
4. return func(num - 1) + func (num - 2)

## 7. Factorial
1. num
2. factorial of a number
3. func (num)
4. return num * func(num - 1)

## 8. Find a way out of the maze
1. maze, string point, blocked, 
2. String
3. solveMaze(r,c, dir)
4. return dir + solveMaze(r,c, dir)

## 9. Find ALL the ways out of the maze
1. maze, string point, blocked, 
2. Array
3. solveMaze(r,c, dir)
4. return.concat(solveMaze(r,c, dir))

## 10. Anagrams
1. string
2. Array
3. anagram(string)
4. return.concat(solveMaze(r,c, dir))

## 11. Organization Chart
1. object
2. String
3. chart(obj)
4. return value + '\n' + chart(obj)

## 11. Binary Representation
1. num
2. string 
3. binary(num[index])
4. return value +  binary(num[index + 1])

