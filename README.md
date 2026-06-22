when green flag clicked
forever
if <key [up arrow v] pressed?> then
change y by (5)
end
if <key [down arrow v] pressed?> then
change y by (-5)
end
if <key [right arrow v] pressed?> then
change x by (5)
end
if <key [left arrow v] pressed?> then
change x by (-5)
end
go to [mouse-pointer v]
if <mouse down?> then
repeat (4)
turn right (15) degrees
end
repeat (4)
turn left (15) degrees
end
end
end
