lass Solution(object):
    def findTheWinner(self, n, k):
        """
        :type n: int
        :type k: int
        :rtype: int
        """
        arr = []    

        for i in range(1, n+1):
            arr.append(i)

        while len(arr) > 1:
            i= i + k - 1
            i = i % len(arr)
            arr.pop(i)

        return arr[0]

