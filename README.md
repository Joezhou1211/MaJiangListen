# MaJiangListen

// 本开源算法可以计算清一色情况下的具体听牌和剩余张数 可自行部署到服务器使用
// 自定义修改建议： 
// 如果需要将其改写为 完整的广东麻将/四川麻将听牌逻辑 可以将牌定义为 
// 万 = 1～9 
// 条 = 11～19 
// 筒 = 21～29 
// 字 = 31，33，35，37，39，41，43 对应东南西北中发白 字需要额外处理逻辑 
// 花 = ...... 

// 修改 find_hu_combinations_for_each_possible_hu 中的记分模式为对应分数 限定清一色范围 
// 修改 check_hu和find_possible_hu 以适应万条筒的模式 
// 修改 combinations_data 适应新结构 
// 其余部分可以适当修改 
// 加入图像处理ML可实现拍照识别图像 进行牌池识别可以精确判断剩余张数以及出牌最优解
