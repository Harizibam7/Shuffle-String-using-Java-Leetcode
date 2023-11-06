# Shuffle-String-using-Java-Leetcode

    class Solution {
        public String restoreString(String s, int[] indices) {
            char ans[]= new char[indices.length];
            String result = "";
            for(int i =0; i<indices.length;i++){
                ans[indices[i]]= s.charAt(i);
            }
            for(char j:ans){
                result+=j;
            }
            return result;
        }
    }
