# Notebooks
Jupyter notebooks, Python Code

Technically we can query Windows defender ATP raw events/base events using its advanced hunting feature. This feature comes pretty handy when we want to dissect and interpret interesting information, perform manual hunt for IOCs, IOAs, attack vectors and write custom detections.
 
In general 'Advanced Hunting' feature is available inside defender ATP portal and you need to login to the ATP portal every time you want to query additional data sets. If you want to collect these raw events/base events outside defender ATP, use their Advanced Hunting APIs to achieve the same.
 
In this post use Jupyter Notebook and Windows Defender Advanced Hunting API to query the data. You can do anything with data but below are the use cases I had in my mind.
 
- On board and schedule additional detection outside ATP.
- Perform joins with existing data sets available outside ATP portal.
- Run machine learning models.
- Build charts, Graphs and visualize the data using other tools.
 
You can use the same python code outside Jupyter notebook as well. Happy Hunting!
