class Solution:
    def closeStrings(self, word1: str, word2: str) -> bool:
        if len(word1)!=len(word2):
            return False
        for j in word1:
            if j not in word2:
                return False
        b=Counter(word1)
        o=Counter(word2)
        kp=b.values()
        lp=o.values()
        if sorted(kp)==sorted(lp):
            return True
        return False
        
