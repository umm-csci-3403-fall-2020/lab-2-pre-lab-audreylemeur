# Leak report

Memory leaks happen because memory is allocated incorrectly or the memory is allocated then forgotten about.
The memory leak here was caused because the allocated memory was not freed after being used.
To fix the leak, we needed to use the "free" method to free up the memory allocated for the string.
