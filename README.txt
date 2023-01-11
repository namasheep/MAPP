

This application leverages the maps made available by Western to allow users to search and explore its interior spaces. 


At a high level, the application will allow users to:
• search for rooms in buildings, 
• locate points of interest in a building,
• browse through the maps provided
• create and save their own personal points of interest. 

The application also has an accompanying editing tool to facilitate the creation and editing of map metadata by developers for the application. 


LOGGING IN 

to log into the application use either a user or admin login. Two are provided here for easy use:

username: user
password: 123

or

username: admin
password: abc

To Run the program:

To run the program please run the executable provided.

If errors are encoutered please ensure the pom file includes the following dependancies:

<dependencies>
        <dependency>
            <groupId>org.netbeans.external</groupId>
            <artifactId>AbsoluteLayout</artifactId>
            <version>RELEASE150</version>
        </dependency>
        <dependency>
            <groupId>org.bidib.jbidib.swinglabs.swingx</groupId>
            <artifactId>swingx-autocomplete</artifactId>
            <version>1.6.5-1</version>
        </dependency>
        <dependency>
            <groupId>commons-io</groupId>
            <artifactId>commons-io</artifactId>
            <version>2.5</version>
            <type>jar</type>
        </dependency>
        <dependency>
            <groupId>org.junit.jupiter</groupId>
            <artifactId>junit-jupiter-api</artifactId>
            <version>5.6.0</version>
            <scope>test</scope>
        </dependency>
        <dependency>
            <groupId>org.junit.jupiter</groupId>
            <artifactId>junit-jupiter-params</artifactId>
            <version>5.6.0</version>
            <scope>test</scope>
        </dependency>
        <dependency>
            <groupId>org.junit.jupiter</groupId>
            <artifactId>junit-jupiter-engine</artifactId>
            <version>5.6.0</version>
            <scope>test</scope>
        </dependency>
        <!-- https://mvnrepository.com/artifact/org.json/json -->
	<dependency>
    	    <groupId>org.json</groupId>
    	    <artifactId>json</artifactId>
    	    <version>20220924</version>
	</dependency>
</dependencies> 


Thanks!