# -
旅游卡 免费旅游路线接口数据API

接口文档地址l：https://www.showdoc.com.cn/lvyoucard/11558810395375289

路线分类标签
URL: /openapi/v1/routetaglist
完整 URL: https://api.xycy.asia/openapi/v1/routetaglist
请求方法: get   
响应数据

{
    "code": 200,
    "list": [
        {
            "id": 1,
            "title": "全部"
        },
        {
            "id": 3,
            "title": "云南"
        },
        {
            "id": 4,
            "title": "贵州"
        },
        {
            "id": 5,
            "title": "广西"
        },
        {
            "id": 6,
            "title": "湖南"
        },
        {
            "id": 7,
            "title": "湖北"
        },
        {
            "id": 8,
            "title": "四川"
        },
        {
            "id": 9,
            "title": "重庆"
        },
        {
            "id": 10,
            "title": "厦门"
        },
        {
            "id": 11,
            "title": "内蒙"
        },
        {
            "id": 12,
            "title": "北京"
        },
        {
            "id": 13,
            "title": "甘肃/青海"
        },
        {
            "id": 14,
            "title": "港珠澳"
        },
        {
            "id": 15,
            "title": "国外游"
        },
        {
            "id": 16,
            "title": "推荐"
        }
    ],
    "Msg": "查询成功"
}


标签路线列表

URL: /openapi/v1/routeTagView
完整 URL: https://api.xycy.asia/openapi/v1/routeTagView
请求方法: post
返回数据


{
    "code": 200,
    "Msg": "查询成功",
    "data": [
        {
            "id": 61,
            "tagid": 4,
            "routeid": 23,
            "created_at": "2025-07-12T10:07:48.000Z",
            "tagTitle": "贵州",
            "routeInfo": {
                "ID": 23,
                "Img": "https:*********",
                "Name": "【会员专享】贵州 黄果树瀑布 西江苗寨5天4晚特惠游",
                "IsDel": 0,
                "Video": "https:*********",
                "OriMoney": 2480,
                "Recommend": "落地免费：酒店住宿 用餐 门票 景点讲解 观光巴士用车 落地接送",
                "TailMoney": 0,
                "Recommend2": "热门推荐，优质服务，适用40－64岁，双人同游，贵阳起止"
            }
        },
        {
            "id": 63,
            "tagid": 4,
            "routeid": 265,
            "created_at": "2025-07-12T10:09:18.000Z",
            "tagTitle": "贵州",
            "routeInfo": {
                "ID": 265,
                "Img": "https:*********",
                "Name": "【会员专享】四省连游-湖北（恩施）/湖南/贵州/重庆7天6晚品质游",
                "IsDel": 0,
                "Video": "",
                "OriMoney": 3980,
                "Recommend": "落地已含：落地接送机服务 酒店 用餐 门票 导游讲解 旅游巴士 旅责险",
                "TailMoney": 0,
                "Recommend2": "热门线路，国内多省连线，适用25-70岁，双人起订"
            }
        },
        {
            "id": 64,
            "tagid": 4,
            "routeid": 274,
            "created_at": "2025-07-12T10:09:28.000Z",
            "tagTitle": "贵州",
            "routeInfo": {
                "ID": 274,
                "Img": "https:*********",
                "Name": "【会员专享】四省联游-湖北/重庆/贵州/湖南 7天6晚品质游",
                "IsDel": 0,
                "Video": "",
                "OriMoney": 3980,
                "Recommend": "落地已含：落地接送机服务 酒店 用餐 门票 导游讲解 旅游巴士 旅责险",
                "TailMoney": 0,
                "Recommend2": "热门线路，国内多省连线，适用25-70岁，双人起订，定期发团"
            }
        }
    ]
}
