def determine_grade(score):
    if 90 <= score <= 100:
        return 'A'
    elif 80 <= score < 90:
        return 'B'
    elif 70 <= score < 80:
        return 'C'
    elif 60 <= score < 70:
        return 'D'
    elif 50 <= score < 60:
        return 'E'
    else:
        return 'F'

def main():
    try:
        num_students = int(input("Enter the number of students: "))
        total_score = 0

        for i in range(num_students):
            student_name = input(f"Enter the name of student {i + 1}: ")
            score = float(input(f"Enter the score for {student_name}: "))
            total_score += score
            print(f"{student_name}'s grade: {determine_grade(score)}")

        average_score = total_score / num_students
        print(f"\nAverage score: {average_score:.2f}")
        print(f"Overall grade: {determine_grade(average_score)}")
    except ValueError:
        print("Invalid input. Please enter a valid numeric score.")

if __name__ == "__main__":
    main()
