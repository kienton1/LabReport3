public class ArrayTests {

  @Test 
	public void testReverseInPlaceforLabReportPass() {
    int[] input1 = { 3, 3, 3 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 3, 3, 3 }, input1);
	}

  @Test 
	public void testReverseInPlaceforLabReportFail() {
    int[] input1 = { 1, 2, 3 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 3, 3, 3 }, input1);
	}
}
