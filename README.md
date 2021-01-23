# print-function
#start Program
#prompt user for the 3 dimensions of cardboard shipping box.
#assign each side to variables; length, widht, depth
#calculate the volume of the box
#print answer to 2 decimal places
#calculate the total surface area of the box
#print answer to 3 decimal places
#end program

def main():
    #prompt user for the 3 dimensions of cardboard shipping box.
    dimension = float(input('Enter the 3 dimensions of box'))
    length = 16.25
    width  = 12.12
    depth = 8.29

    #calculate the volume of the box
    volume = length * width * depth

    #format answer to 2 decimal places
    print(format(volume, ".2f"))

    #print answer
    print('The volume of the box is', volume)

    #calcuate the surface of the box to 3 decimal places
    surface_area = 2(lenght*width) + 2(lenght*depth) + 2(width*height)

    #format answer to 3 decimal places
    print(format(surface_area, ".3f"))

    #print answer
    print('The Surface Area of the box is,', surface_area)

    main()
