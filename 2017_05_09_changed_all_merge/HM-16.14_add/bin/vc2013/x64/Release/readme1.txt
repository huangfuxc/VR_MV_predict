次处修改将下方以及右上角也进行了划分子块的使用，在对右上角进行划分时 将所有的满足条件的右上角都进行了划分。
同时使用了所有的merge，对于isAvailableA1 = pcCULeft &&
				  pcCULeft->isDiffMER(xP - 1, yP + nPSH - 1, xP, yP) &&
				  pcCULeft->isInter(uiLeftPartIdx);的判决更加宽松


