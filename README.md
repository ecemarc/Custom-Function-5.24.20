# Custom-Function-5.24.20



def function(c):
    return (1.8 * c) + 32


c = 0

print("THE CELSIUS TEMP IS:", c, "DEGREES")

f = function(c)

print("THE FAHRENHEIT EQUIVALENT IS:", f, "DEGREES")


print("--------------------")


score = 87.5


def numeric_to_letter_grade(score):
    if (score >= 93):
        print("A")
    elif (score <= 92 >= 89):
        print("A-")
    elif (score <= 88 >= 85):
        print("B+")


print("THE NUMERIC SCORE IS:", score)

grade = numeric_to_letter_grade(score)

print("THE LETTER-GRADE EQUIVALENT IS:", grade)


# TODO: define temperature conversion function here

# TODO: define gradebook function here

if __name__ == "__main__":

    print("--------------------")
    print("CUSTOM FUNCTIONS EXERCISE...")
