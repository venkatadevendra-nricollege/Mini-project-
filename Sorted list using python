def mini(list):
  minval = list[0]
  for _ in list:
    if _ <= minval:
      minval = _
  return minval

def selection_sort(list):
  sorted_list = []
  while list:
    minval = mini(list)
    sorted_list.append(minval)
    list.remove(minval)
  return sorted_list
L1 = [0, 1, 6, 10, 8, 3]
L2 = selection_sort(L1)
print(L2)

#output=[0,1,3,6,8,10]
