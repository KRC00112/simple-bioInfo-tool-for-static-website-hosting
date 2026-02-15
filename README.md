Project: Secure Cloud-Hosted Bioinformatics Web App
📘 Project Overview

This project demonstrates how to deploy a static web application using a secure cloud architecture that prevents direct access to storage while improving performance through caching.

The application analyzes biological nucleotide sequences and determines whether the input is DNA or RNA. It also performs basic sequence analysis such as generating complementary sequences, counting codons, translating proteins, and visualizing distributions.

The deployment architecture ensures:
✅ Private origin storage (not publicly accessible)
✅ Fast global delivery through CDN edge caching
✅ Secure resource access using origin restrictions
✅ Reduced backend load and improved performance