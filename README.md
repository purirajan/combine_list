# combine_list
This python code will combine two lists. 
def combine_lists(list1, list2):
  # Generate a new list containing the elements of list2
  # Followed by the elements of list1 in reverse order
  new_list=list2
  for i in reversed(range(len(list1))):
    new_list.append(list1[i])
  return new_list
