def find_max(numbers):
    max_value = numbers[0]
    for n in numbers:
        if n > max_value:
            max_value = n
    return max_value

if __name__ == "__main__":
    nums = [12, 45, 7, 89, 23]
    print(f"Numbers: {nums}")
    print(f"Maximum value: {find_max(nums)}")
