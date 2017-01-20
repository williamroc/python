def bubble_sort(lists):
    # 冒泡排序
    count = len(lists)
    for i in range(0, count):
        for j in range(i + 1, count):
            first = lists[i]
            second = lists[j]
            if first < second:
                lists[i] = lists[j]
                lists[j] = first
    return lists
array_list = ["12","23","11","1","56","93","67","89"]
sort = bubble_sort(array_list)
print(sort)
