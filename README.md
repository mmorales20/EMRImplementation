# EMRImplementation

package emr;

import static org.junit.Assert.*;

import org.junit.Before;
import org.junit.Test;

public class TestSuite {

	emr testString;

	@Before
	public void setUp ( ) {
		testString = new emr();
	}
	
	@Test 
	public void testFirstName () {
		//testString = "Sally";
		//String first = testString.getFirstName();
		testString.setFirstName("Sally");
		assertEquals("Sally", testString.getFirstName());
		
	
	}

	

}
