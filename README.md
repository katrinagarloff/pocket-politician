# pocket-politician

Using OpenSecrets getLegislators API to retrieve politician data.

·····sssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssse····
····)QQQQQQQQQQQQQQQQQQQQQQQQddddPbPSSQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ····
····)QQQQQQQQQQQQQQQQQQQQQbb·················PPSQQQQQQGQQQQQQQQQQQQQQQQQQQQQ····
····)QQQQQQQQQQQQQQQQGPbC······p··)ssqqp··············bsSQQQQQQQQQQQQQQQQQQb····
····)QQQQQQQQQQQQQQP·····psQSb················ep···········QQQQQQQQQQQQQQQQb···
····)QQQQQQQQQQQQQQo···)QQb······················s·········)QQQQQQQQQQQQQQQb···
····)QQQQQQQQQQQQQSC··sQb··························e·········)QQQQQQQQQQQQQb···
····SQQQQQQQQQQQQQQ··QQC····p·········b·)QeQQQq······o·······)QQQQQQQQQQQQQb···
····sQQQQQQQQQQQQQC)QQC··sdQQQQeee····GQQQPC·····o···)······)QQQQQQQQQQQQQQb···
····SQQQQQQQQQQQQb·QQQb)dGb····SQQb····SC·s·····e·e···b··s··)QQQQQQQQQQQQQQb···
····SQQQQQQQQQQQb···QQsQQS·)sssSdCs········bbbbb······)··Q)··QQQQQQQQQQQQQQ····
····SQQQQQQQQQQQb··sQQQQQSb······p····················)o·sQQsQQQQQQQQQQQQQQ····
····QQQQQQQQQQQQb·sQQQQb)p·······QeeeQQ················b·sQQQQQQQQQQQQQQQQQ····
····QQQQQQQQQQQQQQQQQS··········)QQQQSQQe··············)·)QQQQQQQQQQQQQQQQQ····
····QQQQQQQQQQQQQQQQQQessQ·····)dSPb·······u············p·)QQQQQQQQQQQQQQQQ····
····QQQQQQQQQQQQQQQQQQQQQQQ···)·····pp··················Q··QQQQQQQQQQQQQQQQ····
····QQQQQQQQQQQQQQQQQQQQQQQ··)··sdC········e············)·Q····QQQQQQQQQQQQ····
····SQQQQQQQQQQQQQQQQQQQQQQ··C)S)QQQQPPPSep·············)C····(QQQQQQQQQQQQ····
····SQQQQQQQQQQQQQQQQQQQQQb·C··QQGb············e········S·····SQQQQQQQQQQQQ····
····QQQQQQQQQQQQQQQS·GQQQQQQp)C························QQssssQQQQQQQQQQQQQQb···
····QQQQQQQQQQQQQQQQosQQQQQQQessssssQQQQQQeeQQQQQQsssQQQQQQQQQQQQQQQQQQQQQQb···
····QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQb···
····)QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ·SQSQQQQQQQQQQQQQQQQb···
····)QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ·sQQSQQQQQQQQQQQQQQQb····
····)QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQb·SQQQQQQQQQQQQQQQQQQb····
····)QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQC)QQQQQQQQQQQQQQQQQQQb····
····)QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQSQQQQQQQQQQQQQQQQQQQQ····
····)QQQQQQQQQQQQQQQQQQQQdGQQQQQQQQQQQQQQQQQQQQQQQQSO··)QQQQQQQQQQQQQQQQQQQQ····
····)QQQQQQQQQQQQQQQQQQQS·····QQQQQQQQQQQQQQQQSPC·······QQQQQQQQQQQQQQQQQQQQ····
····)QQQQQQQQQQQQQQQQQQS············PQQQQQQQQ···········QQQQQQQQQQQQQQQQQQQQ····
·····QQQQQQQQQQQQQQQQQQb··········)QQQQQ·)QQQQe·········QQQQQQQQQQQQQQQQQQQQ····
·····QQQQQQQQQQQQQQQQQQb·········S··PGQQQ)QQQGP)o······)QQQQQQQQQQQQQQQQQQQS····
·····QQQQQQQQQQQQQQQQQQb·······)b····seb)QP······p·····)QQQQQQQQQQQQQQQQQQS·····
·····QQQQQQQQQQQQQQQQQQb······d····)QQS·SQ········e····)QQQQQQQQQQQQQQQQQS······
····)QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQb·······
····)QQQQQQQQQQQQQQQQQQep·)s·)SSQSSSSQQb·)o·(·)e·)···Q·QQQQQQQQQQQQQQQQC········
····)QQQQQQQQQQQQQQQQQQQb·)b·)p·b·)p·sQb·)b·p·)b·)·b·)·QQQQQQQQQQQQQQS··········
····)QQQQQQQQQQQQQQQQQQQb·sb·)b·p··eeQQb·Pb·b·)O·)·Q···QQQQQQQQQQQQQS···········
····)QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQep········
················································································
