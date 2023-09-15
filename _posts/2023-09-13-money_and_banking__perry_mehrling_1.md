---
title: lecture note 1
layout: post
tags:
  - economic

---

## 0. Big Picture

基于作者(perry mehrling)的 monetary economics and financial econimics 思想史基础上, I(作者) locate myself in the distinctly
American tradition of monetary thought

how we understand money, banking, and central banking.

origins of monetary thought lie in concrete banking practice.

切入点,
- we start not so much with the 经济学工具[^1] (tools of economics),
- 而是(but rather with), the testimony of practical bankers themselves(实践的银行家自身),
- whose business requires them to work out the implications of a changing world for their own practice(对变化的世界的理解).
- write down what they know in the form of a manual to teach others(撰写成册, 教别人)

并不是以介绍经典案例, 理论, 方法论等, 而是倾听, 学习一线从业者(银行家)的著书, 整理归纳出一套属于自己(对 monetary economics)的理解

we will be listening to bankers, trying to build up our own sense of the system inductively.

(这个方式不是不好, 需要有足够的自信的教授, 才会有底气这个干...)

### Prerequisites

The analytical backbone of the course is an accounting model(会计模型), both micro and macro.

intermediate macro(中级宏观)

    the determination of national income and the determination of the rate of interest, a nominal rate of interest(名义利率)

    thinking about monetary policy as shifting around the LM curve, the Taylor Rule, trying to do inflation targeting maybe

intermediate micro(中级微观)

    we have a tangent budget line here and the slope of that line is -1/1+R, the real interest rate in this case

    微观经济学的研究对象是单个经济单位, 如家庭、厂商等, 要解决资源配置问题, 即生产什么、如何生产和为谁生产, 以实现个体效益的最大化

### What is a bank ?

balance sheet

    资产负债表是分析经济的一种结构, 用于判断银行的偿付能力(solvency)和流动性(liquidity)

    商业银行、影子银行和央行的资产负债表, 并解释了央行扩大货币供应的方式

    solvency 是意味着 assets(资产)的价值是否大于 liabilities(负债),

            Bank
    Assets        Liabilities
    ------------+------------------
    loans       | deposits
    securities  | other borrowing
    cash        | net worth

* issue of solvency vs. liquidity

    - net worth(净值) 与 solvency(偿付能力)

        solvency just means, is the value of the assets greater than the value of the liability 
        so that the net worth is greater than zero

    - cash (cash reserves, 储备金) 与 liquidity(流动性)

        if a depositor transfers their deposit to somebody else,
        tries to make a payment to somebody else,

        does the bank have liquidity?
        does it have case reserves in order to make that payment

        These are demand deposits(活期存款). They can be withdrawn at any moment, Does it have its reserves? 
        And if it doesn't, 
            1. can it acquire them? 
            2. can it borrow them, in the money markets? 
            3. can it go to the Fed ultimately, to the window? 
            4. can it sell a security or repo a security? 
        These are words you haven't heard, but you're going to know what these are pretty soon. 

            5. or does it have to liquidate(清算, 变卖) these loans? 

                sell them at a fire sale price, and if it does, what happens to solvency? 
                If it sells them at a fire sale price, you know the assets are sold below their value. 
                so, there is a link between the liquidity and the solvency. 

    most economists approach banking by thinking first about solvency. We're going to approach banks by thinking first about 
    liquidity and see where that leads us, and that's how bankers think. 

    They face this liquidity constraint every day. They have to clear their accounts. The first two weeks of this course is about 
    the payment system, oddly enough, but you'll see why. It will all connect up. This is a balance sheet of a traditional bank.

* issue of monetary control


Q: bank, central bank 他们的 balance sheet 都有哪些项?

Q: central bank 的 balance sheet 的变化背后解释是什么? 有时增持长期国债, 有时增持短期国债, 有时持企业债券, ...

Q: central bank 可以刷钱, 那是凭空产生更多 currency ? central bank 也作为 bank 可通过 balance sheet 解释他的资产与负债

Q: 怎么去监管?

Q: 学习解读经济报道, 学会看懂 central bank 的 balance sheet, 作为银行、银行的银行、政府机构会蕴含当时的政府决策


## 1. The Four Prices of Money

### Four functions of banking

1. Clearing
2. market making
3. advance clearing
4. intermediation

    关键词, liquidity
        payments system with liquidity,
        liquid markets with liquidity,
        ...

    understanding the payments system is the best starting place for understading the phenomenon of liquidity.
    understanding 支付系统(payments system)

    Once we understand the phenomenon of liquid assets we are ready to consider the phenomenon of liquid markets.
    understanding liquid markets

    Thus clearing and market making are the two central function

    Q: clearing 包含 payments??

        支付结算及清算目前国内没有一个统一的定义, 从央行的有关规定中可以看出,
            1. 认为银行与商户, 消费者之间为支付结算关系,
            2. 因跨行交易而产生的银行之间的债权债务而实时或定期结清的过程称为清算
        目前支付结算环节放开市场竞争, 鼓励创新; 清算环节为基础设施, 不希望市场进入

        清算系统均由央行主管,
            1. 主要包括大额实时支付系统(HVPS)、
            2. 小额批量支付系统(BEPS)、
            3. 网上支付跨行清算系统、
            4. 同城票据清算系统、
            5. 境内外币支付系统、
            6. 城市商业银行资金清算系统和农信银支付清算系统
            ...

        大额实时支付系统 HVPS-High Value Payment System, 国际上对这类系统的通用叫法是 RTGS-Real Time Gross Settlement

        RTGS 系统在收到资金转账指令后, 立即将付款资金从付款行在中央银行的备付金账户转移到收款行在中央银行的备付金账户,
        一般来说参加大额实时支付对参与方的流动性要求较高, 因为备付金账户里一定要有足够的资金保证支付成功

        美国(CHIPS,NET; Fedwire,RTGS)
        欧盟(TARGET,RTGS)
        中国(HVPS,RTGS; BEPS,NET)

        虽然 target2 系统规定, 每笔交易必须当天完成, 不能形成隔夜债权债务, 但在央行间后台账务处理中却没有类似规定

        Target2 容易导致失衡的机理, 可通过一个例子加以说明,

            一家希腊企业签一张支票给德国公司用于进口货物, 德国公司委托德国商业银行向希腊银行收款
            希腊商业银行将其持有的欧元体系准备金转移至德国商业银行, 最终完成结算

            但如果希腊商业银行准备金不足且无法从市场融资, 就只能通过希腊央行向欧央行申请"再融资", 所得资金将进入希腊央行在
            target2 系统中开立的专用母账户中. 此时欧央行 target2 系统中就拥有了对希腊央行的债权. 在 target2 系统的制度设计中,
            欧央行只是总协调方, 不承担净头寸风险, 欧央行会以希腊央行的担保品为抵押, 请德央行提供等额资金

            因此，德央行在 target2 系统中就拥有了一笔对欧央行的债权, 实现了对希腊央行的间接融资


### Four prices of money

1.  Par             - diferent types of money(currency, deposists);

    this is the price of one money in terms of another money right now (这是目前一种货币相对于另一种货币的价格)

        即时汇率, 即期汇率

    如果在银行账户中有 $100(deposit accounts), 可以去银行柜台取出 $100(cash reserves); that's par (平价? 票面价值?)

                    Bank
        Assets            Liabilities
        ----------------+------------------
        Loans           | Deposit Accounts
        Securities      | Other borrowing
        Cash Reserves   | Net Worth

        不同"形态"的 money, deposit or currency(cash reserves)

        -$100 存款负债; -$100 储备金,

        而 cash reserves 是来自于 central bank, central bank 与 bank 之间 interest rate 未必一直保持 1:1

        当没有 par clearing 建立的时候(央行??), 跨城、跨银行支付会产生额外费用, 并不是 real time 划账, 发生时差

    par: 在当下以一份货币(存款)为单位, 计算另一份货币(存款)的价格;

        假设在某家银行有 100 块活期存款, 一般情况下这 100 块存款可以随时换到 100 块现金. 但这 100 块存款实际上只是对银行的 100 块债权,
        极端情况下, 譬如银行破产, 那么可能无法全额取现或者跨行转账(其他银行不愿意同时接受 100 块对该银行的债权和 100 块对你的债务,
        因为已经资不抵债), 破产清算(以及在那之前) 这 100 块存款可能只值 55 块现金, 这个 55 块现金就是 par

2.  Interest        - future money(fed funds, Eurodollars, repo)

        我们国家是给准备金利息的, 但是其他国家如美国是不给的, 储备金是为了提高银行信用度和调节经济的.
        我国的准备金由于一般不会同业拆借, 为了弥补银行的损失, 央行是给利息的.
        至于美国为什么不给, 是由于美国的存款准备金收上去后, 是放在其联邦基金里面可以进行同业拆借的, 可以从存款准备金里面获益.

        cash reserves 的同行拆借的利率不低于 deposit rate, 还是不亏.


    但凡涉及 future, 离不开 credit + interest rate.. 承担风险收益浮动收益

3.  Exchange rate   - foreign money

4.  Price level     - commodities

all banking is essentially a swap of IOUs (借据的交换)

---

credit 带来的 money 不变的情况下, interest 差(  a-b 1%, b-c 2%, c-d 3% )

(储蓄 - 储备金 ~ 贷款 + credit 风险; 贷款利息 > 储蓄利息)

金融中介一般都是借短贷长，比如说银行、货币基金等等



---

[^1]: 经典理论, 研究方法(论)




