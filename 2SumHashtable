dataArray = [3,5,-4,8,11,1,-1,6]
targetData = 10
def sumWithHashTable(array,targetSum):
    hashTable = {};
    for num in array:
        if targetSum - num in hashTable:
            return sorted([targetSum - num , num])
        else:
            hashTable[num] = True
    return []

print(sumWithHashTable(dataArray,targetData));
