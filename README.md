# Java_XML
org.jsoup.nodes.Document 

org.jsoup.nodes.Document 

Document doc = Jsoup.parse(responseXml);
Elements elements_attribute1 = doc.select("attribute1");
for (Element attr : elements_attribute1) { 
	Elements ele_attribute11 = attr.select("attribute11");
}
	
