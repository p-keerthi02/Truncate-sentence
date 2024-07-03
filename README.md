class Solution:
    def truncateSentence(self, s: str, k: int) -> str:
        x = s.split()
        y = ' '.join(x[:k])
        return y 
