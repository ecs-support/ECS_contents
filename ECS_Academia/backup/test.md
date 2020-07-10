data = chg.copy()
data['company'] = data['company'].str.replace("บริษัท","")
data['company'] = data['company'].str.replace("จำกัด","")
data['company'] = data['company'].str.replace("บจก.","")
data['company'] = data['company'].str.replace("หจก.","")
data['company'] = data['company'].str.replace("บริษัท","")
data['company'] = data['company'].str.replace("ห้างหุ้นส่วน","")
data['company'] = data['company'].str.strip()
data.sample(20)



def replace_company(data):
    data['company'] = data['company'].str.replace("บริษัท","")
    data['company'] = data['company'].str.replace("จำกัด","")
    data['company'] = data['company'].str.replace("บจก.","")
    data['company'] = data['company'].str.replace("หจก.","")
    data['company'] = data['company'].str.replace("บริษัท","")
    data['company'] = data['company'].str.replace("ห้างหุ้นส่วน","")
    data['company'] = data['company'].str.strip()
    return data