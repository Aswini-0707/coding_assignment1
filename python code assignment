def find_sum(list_num, arr_size, sum):

    # Fix the first element as list_num[i]
    for i in range(0, arr_size-2):

        # Fix the second element as list_num[j]
        for j in range(i + 1, arr_size-1):

            # Now look for the third number
            for k in range(j + 1, arr_size):
                if list_num[i] + list_num[j] + list_num[k] == sum:
                    print("True")
                    return True
    else:
        print("False")
    # If we reach here, then no
    # triplet was found
    return False


# Driver program to test above function
list_num = [4, 5, 6, 5, 4]
sum = 15
arr_size = len(list_num)
find_sum(list_num, arr_size, sum)
