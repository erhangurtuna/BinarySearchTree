
//Test Class

public class Test {

	/**
	 * @param args
	 */
	public static void main(String[] args) {

		BinaryNode n2 = new BinaryNode(2);
		BinaryNode n3 = new BinaryNode(3);
		BinaryNode n4 = new BinaryNode(4);
		BinaryNode n5 = new BinaryNode(5);
		BinaryNode n6 = new BinaryNode(6);
		BinaryNode n7 = new BinaryNode(7);
		BinaryNode n8 = new BinaryNode(8);
		BinaryNode n10 = new BinaryNode(10);
		BinaryNode n12 = new BinaryNode(12);
		BinaryNode n13 = new BinaryNode(13);
		BinaryNode n14 = new BinaryNode(14);
		BinaryNode n15 = new BinaryNode(15);
		BinaryNode n16 = new BinaryNode(16);
		BinaryNode n17 = new BinaryNode(17);
		BinaryNode n18 = new BinaryNode(18);
		BinaryNode n19 = new BinaryNode(19);
		BinaryNode n20 = new BinaryNode(20);
		BinaryNode n21 = new BinaryNode(21);
		BinaryNode n22 = new BinaryNode(22);
		
		// n10 will be the root
		n10.insertLeft(n5);
		n10.insertRight(n15);
		
		n5.insertLeft(n3);
		n5.insertRight(n7);
		
		n3.insertLeft(n2);
		n3.insertRight(n4);
		
		n7.insertLeft(n6);
		n7.insertRight(n8);
		
		n15.insertLeft(n13);
		n15.insertRight(n19);
		
		n13.insertLeft(n12);
		n13.insertRight(n14);
		
		n19.insertLeft(n16);
		n19.insertRight(n21);
		
		n16.insertLeft(n17);
		n16.insertRight(n18);
		
		n21.insertLeft(n20);
		n21.insertRight(n22);

		System.out.println(n10.findMin());
		System.out.println(n10.findMax());
		System.out.println(n10.findSecondMin());
		System.out.println(n10.findSecondMax());
		
	}

}

