# Spotify Million DataSet Project

Used Colab and Drive Link to directly open the ZIP file and processed it along the way

Second Question thoughts:
- I am selecting two songs, finding those two songs in the dataset. let say our playlists range from 0th to nth index. And we find song A at xth index such that 0<x<n. As soon as we do find a, we continue the loop, and in the next iteration we add the next playlist to our empty playlist (x+1). We keep adding until we find our song B at, lets say y index (x>y>n). We stop here (also including the y playlist)
- Now first I find a direct relation between x and y playlist. If found, then thats all. If not, I take three playlists, x y & z. Such that z is x > z > y. So in summary, only searching for pairs between those two earlier found lists. I tried to traverse in each direction of x and y but that just crashed the memory on colab. So yes, there is a possibility, regardless of how low it is, that there may not be a pair found in indirect relation.