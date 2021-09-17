# STATES




from csv import reader 
with open('-------', 'r') as ArticleIVSection3Clause1:
    csv_reader = reader(ArticleIVSection3Clause1)
    statesDotes = list(csv_reader)
    for i in range(len(statesDotes)):
        if i == [i][0]:
            AAA = FIELD_state = (statesDotes[i][0])
            BBB = FIELD_population = (statesDotes[i][1])
            VVV = FIELD_electoralvotes = (statesDotes[i][2])
            WWW = FIELD_highwaymiles = (statesDotes[i][3])
            OOO = FIELD_squaremiles = (statesDotes[i][4])
            statesDataVIP = [FIELD_state, BBB, FIELD_electoralvotes, WWW, OOO]
            AAAAA = statesDataVIP[0:1]
            State = str(AAAAA)
            YYYY = statesDataVIP[1:2]
            badACTORS = ['Population']
            TTITTI1 = ''.join(i for i in YYYY if not i in badACTORS)
            PPopulation = (TTITTI1)
            ZZZZ = statesDataVIP[2:3]
            okACTORS2 = ['ElectoralVotes']
            TTITTI2 = ''.join(i for i in ZZZZ if not i in okACTORS2)
            Electoral_Votes = (TTITTI2)
            WY372CR486 = statesDataVIP[3:4]
            greatACTORS4M5 = ['HighwayMiles']
            TTITTI3 = ''.join(i for i in WY372CR486 if not i in greatACTORS4M5)
            Highway_Miles = (TTITTI3)
            KELOvCITYOFNEWLONDON = statesDataVIP[4:5]
            bestACTORSFIFTHA = ['SquareMiles']
            TTITTI4TTITTI = ''.join(i for i in KELOvCITYOFNEWLONDON if not i in bestACTORSFIFTHA)
            Square_Miles = (TTITTI4TTITTI)
            SuperStatesData = [State, PPopulation, Electoral_Votes, Highway_Miles, Square_Miles]
            B = PPopulation.split()
            BB = map(int, B)
            Dingle = list(BB)
            TRYTHISNUMEROUNO = sum(Dingle)
            Population = int(TRYTHISNUMEROUNO)
            WHANTAAHINT = (type(Population))
            V = Electoral_Votes.split()
            VV = map(int, V)
            FortJoyce = list(VV)
            TRYTHIS= sum(FortJoyce)
            ElectoralVotes = int(TRYTHIS)
            ASKANDRECEIVEINT = (type(ElectoralVotes))
            W = Highway_Miles.split()
            WW = map(float, W)
            RangerRick = list(WW)
            TRYTHISTHREETIMES = sum(RangerRick)
            HighwayMiles = float(TRYTHISTHREETIMES)
            FLOATER = (type(HighwayMiles))
            O = Square_Miles.split()
            OO = map(float, O)
            MACKTRUCK = list(OO)
            TRYTOTRYTOTRYTOKUIUC = sum(MACKTRUCK)
            SquareMiles = float(TRYTOTRYTOTRYTOKUIUC)
            LANDERFORLANDER = (type(SquareMiles))
            statesData = [State, Population, ElectoralVotes, HighwayMiles, SquareMiles]
            
            def reduce(function, iterable, initializer=None):
                it = iter(iterable)
                if initializer is None:
                    try:
                        initializer = next(it)
                    except StopIteration:
                            raise TypeError('reduce() of empty sequence with no initial value')
                            accum_value = initializer
                            for x in it:
                                accum_value = function(accum_value, x)
                  
                SumOfStatePopulation = reduce(lambda x, y: x+y, Population)
                SumOfStateElectoralVotes = reduce(lambda x, y: x+y, ElectoralVotes)
                SumOfStateHighwayMiles = reduce(lambda x, y: x+y, HighwayMiles)
                SumOfStateSquareMiles = reduce(lambda x, y: x+y, SquareMiles)
                
                print(SumOfStatePopulation)
                print(SumOfStateElectoralVotes)
                print(SumOfStateHighwayMiles)
                print(SumOfStateSquareMiles)
                
                
