1. The bug was that that num1 and num2 were being treated as strings and were being concatenated instead of added.
2. I fixed it by using parseInt(num1) + parseInt(num2)