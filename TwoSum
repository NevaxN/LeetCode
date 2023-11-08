class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:

        seen = {}

        for i in range (len(nums)):
            diff = target - nums[i]
            if diff in seen:
                return [seen[diff], i]
            else:
                seen[nums[i]] = i

 #My O(n²) Solution
"""
index = []

pivot = 0
i = pivot + 1

while True:
    if nums[pivot] + nums[i] == target:
        index = [pivot, i]
        break
    elif nums[pivot] + nums[i] != target and i == len(nums) - 1:
        pivot += 1
        i = pivot
    i += 1
return index
"""

#O(n) Solution

"""
seen = {}

for i in range (len(nums)):
    diff = target - nums[i]
    if diff in seen:
        return [seen[diff], i]
    else:
        seen[nums[i]] = i 
"""
