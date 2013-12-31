package hlo;

import java.util.ArrayList;
import java.util.List;

/**
 * @author Joe A-W
 * 
 *         A Java implementation of some of the Haskell List Operations, or HaLO for short. I wrote the expression parser
 *         entirely by myself, and therefore I would not recommend using these operations in any truly performance critical
 *         code. 
 */
public class Halo
{
	/**
	 * @param expression
	 * @param array
	 * @return all elements up to (but not including) the first element to cause the expression evaluate to true.
	 */
	public static int[] takeWhile(String expression, int[] array)
	{
		List<Integer> tem = new ArrayList<Integer>();
		for (int temp : array)
		{
			if (!ExpressionParser.evaluate(expression, "x", temp))
				break;
			else
				tem.add(temp);
		}
		int[] tem1 = new int[tem.size()];
		for (int i = 0; i < tem1.length; i++)
			tem1[i] = tem.get(i);
		return tem1;
	}

	/**
	 * @param expression
	 * @param array
	 * @return all elements up to (but not including) the first element to cause the expression evaluate to true.
	 */
	public static String[] takeWhile(String expression, String[] array)
	{
		List<String> tem = new ArrayList<String>();
		for (String temp : array)
		{
			if (!ExpressionParser.evaluate(expression, "x", temp))
				break;
			else
				tem.add(temp);
		}
		String[] tem1 = new String[tem.size()];
		for (int i = 0; i < tem1.length; i++)
			tem1[i] = tem.get(i);
		return tem1;
	}

	/**
	 * @param expression
	 * @param array
	 * @return all elements up to (but not including) the first element to cause the expression evaluate to true.
	 */
	public static char[] takeWhile(String expression, char[] array)
	{
		List<Character> tem = new ArrayList<Character>();
		for (char temp : array)
		{
			if (!ExpressionParser.evaluate(expression, "x", temp))
				break;
			else
				tem.add(temp);
		}
		char[] tem1 = new char[tem.size()];
		for (int i = 0; i < tem1.length; i++)
			tem1[i] = tem.get(i);
		return tem1;
	}

	/**
	 * @param expression
	 * @param array
	 * @return all elements up to (but not including) the first element to cause the expression evaluate to true.
	 */
	public static double[] takeWhile(String expression, double[] array)
	{
		List<Double> tem = new ArrayList<Double>();
		for (double temp : array)
		{
			if (!ExpressionParser.evaluate(expression, "x", temp))
				break;
			else
				tem.add(temp);
		}
		double[] tem1 = new double[tem.size()];
		for (int i = 0; i < tem1.length; i++)
			tem1[i] = tem.get(i);
		return tem1;
	}

	/**
	 * @param expression
	 * @param array
	 * @return if the expression evaluates to true for any element.
	 */
	public static boolean any(String expression, String[] array)
	{
		for (String a : array)
		{
			if (ExpressionParser.evaluate(expression, a))
				return true;
		}
		return false;
	}

	/**
	 * @param expression
	 * @param array
	 * @return if the expression evaluates to true for any element.
	 */
	public static boolean any(String expression, int[] array)
	{
		for (int a : array)
		{
			if (ExpressionParser.evaluate(expression, a))
				return true;
		}
		return false;
	}

	/**
	 * @param expression
	 * @param array
	 * @return if the expression evaluates to true for any element.
	 */
	public static boolean any(String expression, char[] array)
	{
		for (char a : array)
		{
			if (ExpressionParser.evaluate(expression, a))
				return true;
		}
		return false;
	}

	/**
	 * @param expression
	 * @param array
	 * @return if the expression evaluates to true for any element.
	 */
	public static boolean any(String expression, double[] array)
	{
		for (double a : array)
		{
			if (ExpressionParser.evaluate(expression, a))
				return true;
		}
		return false;
	}

	/**
	 * @param expression
	 * @param array
	 * @return if the expression evaluates to true for all elements.
	 */
	public static boolean all(String expression, int[] array)
	{
		for (int a : array)
		{
			if (!ExpressionParser.evaluate(expression, a))
				return false;
		}
		return true;
	}

	/**
	 * @param expression
	 * @param array
	 * @return if the expression evaluates to true for all elements.
	 */
	public static boolean all(String expression, String[] array)
	{
		for (String a : array)
		{
			if (!ExpressionParser.evaluate(expression, a))
				return false;
		}
		return true;
	}

	/**
	 * @param expression
	 * @param array
	 * @return if the expression evaluates to true for all elements.
	 */
	public static boolean all(String expression, char[] array)
	{
		for (char a : array)
		{
			if (!ExpressionParser.evaluate(expression, a))
				return false;
		}
		return true;
	}

	/**
	 * @param expression
	 * @param array
	 * @return if the expression evaluates to true for all elements.
	 */
	public static boolean all(String expression, double[] array)
	{
		for (double a : array)
		{
			if (!ExpressionParser.evaluate(expression, a))
				return false;
		}
		return true;
	}

	/**
	 * @param expression
	 * @param array
	 * @return every member of the list after (and including) the first member to fail the expression.
	 */
	public static int[] dropWhile(String expression, int[] array)
	{
		List<Integer> tem = new ArrayList<Integer>();
		for (int i = 0; i < array.length; i++)
		{
			if (!ExpressionParser.evaluate(expression, "x", array[i]))
			{
				for (int j = i; j < array.length; j++)
					tem.add(array[i]);
				break;
			}
		}
		int[] tem1 = new int[tem.size()];
		for (int i = 0; i < tem1.length; i++)
			tem1[i] = tem.get(i);
		return tem1;
	}

	/**
	 * @param expression
	 * @param array
	 * @return every member of the list after (and including) the first member to fail the expression.
	 */
	public static String[] dropWhile(String expression, String[] array)
	{
		List<String> tem = new ArrayList<String>();
		for (int i = 0; i < array.length; i++)
		{
			if (!ExpressionParser.evaluate(expression, "x", array[i]))
			{
				for (int j = i; j < array.length; j++)
					tem.add(array[i]);
				break;
			}
		}
		String[] tem1 = new String[tem.size()];
		for (int i = 0; i < tem1.length; i++)
			tem1[i] = tem.get(i);
		return tem1;
	}

	/**
	 * @param expression
	 * @param array
	 * @return every member of the list after (and including) the first member to fail the expression.
	 */
	public static char[] dropWhile(String expression, char[] array)
	{
		List<Character> tem = new ArrayList<Character>();
		for (int i = 0; i < array.length; i++)
		{
			if (!ExpressionParser.evaluate(expression, "x", array[i]))
			{
				for (int j = i; j < array.length; j++)
					tem.add(array[i]);
				break;
			}
		}
		char[] tem1 = new char[tem.size()];
		for (int i = 0; i < tem1.length; i++)
			tem1[i] = tem.get(i);
		return tem1;
	}

	/**
	 * @param expression
	 * @param array
	 * @return every member of the list after (and including) the first member to fail the expression.
	 */
	public static double[] dropWhile(String expression, double[] array)
	{
		List<Double> tem = new ArrayList<Double>();
		for (int i = 0; i < array.length; i++)
		{
			if (!ExpressionParser.evaluate(expression, "x", array[i]))
			{
				for (int j = i; j < array.length; j++)
					tem.add(array[i]);
				break;
			}
		}
		double[] tem1 = new double[tem.size()];
		for (int i = 0; i < tem1.length; i++)
			tem1[i] = tem.get(i);
		return tem1;
	}

	/**
	 * @param array
	 * @return a reversed version of the array.
	 */
	public static <T> T[] reverse(T[] array)
	{
		for (int i = 0; i < array.length / 2; i++)
		{
			T temp = array[i];
			array[i] = array[array.length - 1 - i];
			array[array.length - 1 - i] = temp;
		}
		return array;
	}

	/**
	 * @param array
	 * @return a reversed version of the array.
	 */
	public static int[] reverse(int[] array)
	{
		for (int i = 0; i < array.length / 2; i++)
		{
			int temp = array[i];
			array[i] = array[array.length - 1 - i];
			array[array.length - 1 - i] = temp;
		}
		return array;
	}

	/**
	 * @param array
	 * @return a reversed version of the array.
	 */
	public static char[] reverse(char[] array)
	{
		for (int i = 0; i < array.length / 2; i++)
		{
			char temp = array[i];
			array[i] = array[array.length - 1 - i];
			array[array.length - 1 - i] = temp;
		}
		return array;
	}

	/**
	 * @param array
	 * @return a reversed version of the array.
	 */
	public static double[] reverse(double[] array)
	{
		for (int i = 0; i < array.length / 2; i++)
		{
			double temp = array[i];
			array[i] = array[array.length - 1 - i];
			array[array.length - 1 - i] = temp;
		}
		return array;
	}

	/**
	 * @param element
	 * @param array
	 * @return if the given element exists in the array.
	 * 
	 *         This version uses .equals() for comparison.
	 */
	public static <T> boolean elem(T element, T[] array)
	{
		for (int i = 0; i < array.length; i++)
			if (array[i].equals(element))
				return true;
		return false;
	}

	/**
	 * @param element
	 * @param array
	 * @return if the given element exists in the array.
	 */
	public static boolean elem(int element, int[] array)
	{
		for (int i = 0; i < array.length; i++)
			if (array[i] == (element))
				return true;
		return false;
	}

	/**
	 * @param element
	 * @param array
	 * @return if the given element exists in the array.
	 */
	public static boolean elem(char element, char[] array)
	{
		for (int i = 0; i < array.length; i++)
			if (array[i] == (element))
				return true;
		return false;
	}

	/**
	 * @param element
	 * @param array
	 * @return if the given element exists in the array.
	 */
	public static boolean elem(double element, double[] array)
	{
		for (int i = 0; i < array.length; i++)
			if (array[i] == (element))
				return true;
		return false;
	}

	/**
	 * @param element
	 * @param array
	 * @return all indexes where the element equals the given element.
	 * 
	 *         This version uses .equals() for comparison.
	 */
	public static <T> int[] elemIndices(T element, T[] array)
	{
		List<Integer> temp = new ArrayList<Integer>();
		for (int i = 0; i < array.length; i++)
			if (array[i].equals(element))
				temp.add(i);
		int[] tem1 = new int[temp.size()];
		for (int i = 0; i < tem1.length; i++)
			tem1[i] = temp.get(i);
		return tem1;
	}

	/**
	 * @param element
	 * @param array
	 * @return all indexes where the element equals the given element.
	 * 
	 * 
	 */
	public static int[] elemIndices(int element, int[] array)
	{
		List<Integer> temp = new ArrayList<Integer>();
		for (int i = 0; i < array.length; i++)
			if (array[i] == (element))
				temp.add(i);
		int[] tem1 = new int[temp.size()];
		for (int i = 0; i < tem1.length; i++)
			tem1[i] = temp.get(i);
		return tem1;
	}

	/**
	 * @param element
	 * @param array
	 * @return all indexes where the element equals the given element.
	 * 
	 * 
	 */
	public static int[] elemIndices(char element, char[] array)
	{
		List<Integer> temp = new ArrayList<Integer>();
		for (int i = 0; i < array.length; i++)
			if (array[i] == (element))
				temp.add(i);
		int[] tem1 = new int[temp.size()];
		for (int i = 0; i < tem1.length; i++)
			tem1[i] = temp.get(i);
		return tem1;
	}

	/**
	 * @param element
	 * @param array
	 * @return all indexes where the element equals the given element.
	 * 
	 * 
	 */
	public static int[] elemIndices(double element, double[] array)
	{
		List<Integer> temp = new ArrayList<Integer>();
		for (int i = 0; i < array.length; i++)
			if (array[i] == (element))
				temp.add(i);
		int[] tem1 = new int[temp.size()];
		for (int i = 0; i < tem1.length; i++)
			tem1[i] = temp.get(i);
		return tem1;
	}

	/**
	 * @param element
	 * @param array
	 * @return the index of the first element to equal the target element.
	 * 
	 * 
	 */
	public static int elemIndex(int element, int[] array)
	{
		for (int i = 0; i < array.length; i++)
			if (array[i] == element)
				return i;
		return -1;
	}

	/**
	 * @param element
	 * @param array
	 * @return the index of the first element to equal the target element.
	 * 
	 * 
	 */
	public static int elemIndex(char element, char[] array)
	{
		for (int i = 0; i < array.length; i++)
			if (array[i] == element)
				return i;
		return -1;
	}

	/**
	 * @param element
	 * @param array
	 * @return the index of the first element to equal the target element.
	 * 
	 * 
	 */
	public static int elemIndex(double element, double[] array)
	{
		for (int i = 0; i < array.length; i++)
			if (array[i] == element)
				return i;
		return -1;
	}

	/**
	 * @param element
	 * @param array
	 * @return the index of the first element to equal the target element.
	 * 
	 *         This version uses .equals() for comparison.
	 */
	public static <T> int elemIndex(T element, T[] array)
	{
		for (int i = 0; i < array.length; i++)
			if (array[i].equals(element))
				return i;
		return -1;
	}

	/**
	 * @param expression
	 * @param array
	 * @return the index of the first element in the array to satisfy the expression.
	 * 
	 * 
	 */
	public static int findIndex(String expression, int[] array)
	{
		for (int i = 0; i < array.length; i++)
			if (ExpressionParser.evaluate(expression, array[i]))
				return i;
		return -1;
	}

	/**
	 * @param expression
	 * @param array
	 * @return the index of the first element in the array to satisfy the expression.
	 * 
	 * 
	 */
	public static int findIndex(String expression, char[] array)
	{
		for (int i = 0; i < array.length; i++)
			if (ExpressionParser.evaluate(expression, array[i]))
				return i;
		return -1;
	}

	/**
	 * @param expression
	 * @param array
	 * @return the index of the first element in the array to satisfy the expression.
	 * 
	 * 
	 */
	public static int findIndex(String expression, String[] array)
	{
		for (int i = 0; i < array.length; i++)
			if (ExpressionParser.evaluate(expression, array[i]))
				return i;
		return -1;
	}

	/**
	 * @param expression
	 * @param array
	 * @return the index of the first element in the array to satisfy the expression.
	 * 
	 * 
	 */
	public static int findIndex(String expression, double[] array)
	{
		for (int i = 0; i < array.length; i++)
			if (ExpressionParser.evaluate(expression, array[i]))
				return i;
		return -1;
	}

	/**
	 * @param expression
	 * @param array
	 * @return an array containing all indices of the elements that satisfy the expression.
	 */
	public static int[] findIndices(String expression, int[] array)
	{
		List<Integer> temp = new ArrayList<Integer>();
		for (int i = 0; i < array.length; i++)
			if (ExpressionParser.evaluate(expression, array[i]))
				temp.add(i);
		int[] tem1 = new int[temp.size()];
		for (int i = 0; i < tem1.length; i++)
			tem1[i] = temp.get(i);
		return tem1;
	}

	/**
	 * @param expression
	 * @param array
	 * @return an array containing all indices of the elements that satisfy the expression.
	 */
	public static int[] findIndices(String expression, String[] array)
	{
		List<Integer> temp = new ArrayList<Integer>();
		for (int i = 0; i < array.length; i++)
			if (ExpressionParser.evaluate(expression, array[i]))
				temp.add(i);
		int[] tem1 = new int[temp.size()];
		for (int i = 0; i < tem1.length; i++)
			tem1[i] = temp.get(i);
		return tem1;
	}

	/**
	 * @param expression
	 * @param array
	 * @return an array containing all indices of the elements that satisfy the expression.
	 */
	public static int[] findIndices(String expression, char[] array)
	{
		List<Integer> temp = new ArrayList<Integer>();
		for (int i = 0; i < array.length; i++)
			if (ExpressionParser.evaluate(expression, array[i]))
				temp.add(i);
		int[] tem1 = new int[temp.size()];
		for (int i = 0; i < tem1.length; i++)
			tem1[i] = temp.get(i);
		return tem1;
	}

	/**
	 * @param expression
	 * @param array
	 * @return an array containing all indices of the elements that satisfy the expression.
	 */
	public static int[] findIndices(String expression, double[] array)
	{
		List<Integer> temp = new ArrayList<Integer>();
		for (int i = 0; i < array.length; i++)
			if (ExpressionParser.evaluate(expression, array[i]))
				temp.add(i);
		int[] tem1 = new int[temp.size()];
		for (int i = 0; i < tem1.length; i++)
			tem1[i] = temp.get(i);
		return tem1;
	}

	/**
	 * @param string
	 * @return an array containing all strings separated by newlines as elements.
	 */
	public static String[] lines(String s)
	{
		List<String> temp = new ArrayList<String>();
		String tem1 = "";
		for (char c : s.toCharArray())
		{
			if (c == '\n')
			{
				temp.add(tem1);
				tem1 = "";
			}
			else
				tem1 += c;
		}
		temp.add(tem1);
		String[] t = new String[temp.size()];
		for (int i = 0; i < t.length; i++)
			t[i] = temp.get(i);
		return t;
	}

	/**
	 * @param strings
	 * @return The all strings in an array as one string, separated by newlines.
	 */
	public static String unlines(String[] s)
	{
		String temp = "";
		for (String t : s)
			temp += t + "\n";
		return temp;
	}

	/**
	 * @param string
	 * @return all individual words in a string (that are separated by spaces).
	 */
	public static String[] words(String s)
	{
		List<String> temp = new ArrayList<String>();
		String tem1 = "";
		for (char c : s.toCharArray())
		{
			if (c == ' ')
			{
				if (!tem1.isEmpty())
				{
					temp.add(tem1);
					tem1 = "";
				}
			}
			else
				tem1 += c;
		}
		temp.add(tem1.trim());
		String[] t = new String[temp.size()];
		for (int i = 0; i < t.length; i++)
			t[i] = temp.get(i);
		return t;
	}

	/**
	 * @param strings
	 * @return all elements of the array as a single string, separated by 1 space.
	 */
	public static String unwords(String[] s)
	{
		String temp = "";
		for (String t : s)
			temp += t + ' ';
		return temp;
	}

	/**
	 * @param array
	 * @return all strings in the array concatenated to one-another.
	 */
	public static String concat(String[] array)
	{
		String temp = "";
		for (String s : array)
			temp += s;
		return temp;
	}

	/**
	 * @param array
	 * @return a 1D array containing all the elements of the 2D Array.
	 */
	public static String[] concat(String[][] array)
	{
		String[] temp = new String[array.length * array[0].length];
		int cnt = 0;
		for (int i = 0; i < array.length; i++)
			for (int j = 0; j < array.length; j++)
			{
				temp[cnt] = array[i][j];
				cnt++;
			}
		return temp;
	}

	/**
	 * @param array
	 * @return a 1D array containing all the elements of the 2D Array.
	 */
	public static int[] concat(int[][] array)
	{
		int[] temp = new int[array.length * array[0].length];
		int cnt = 0;
		for (int i = 0; i < array.length; i++)
			for (int j = 0; j < array.length; j++)
			{
				temp[cnt] = array[i][j];
				cnt++;
			}
		return temp;
	}

	/**
	 * @param array
	 * @return a 1D array containing all the elements of the 2D Array.
	 */
	public static char[] concat(char[][] array)
	{
		char[] temp = new char[array.length * array[0].length];
		int cnt = 0;
		for (int i = 0; i < array.length; i++)
			for (int j = 0; j < array.length; j++)
			{
				temp[cnt] = array[i][j];
				cnt++;
			}
		return temp;
	}

	/**
	 * @param array
	 * @return a 1D array containing all the elements of the 2D Array.
	 */
	public static double[] concat(double[][] array)
	{
		double[] temp = new double[array.length * array[0].length];
		int cnt = 0;
		for (int i = 0; i < array.length; i++)
			for (int j = 0; j < array.length; j++)
			{
				temp[cnt] = array[i][j];
				cnt++;
			}
		return temp;
	}
	
	/**
	 * @param array
	 * @return a 1D array of Objects containing all the elements of the 2D Array.
	 */
	public  static <T> Object[] concat(T[][] array)
	{
		List<T> temp = new ArrayList<T>(array.length * array[0].length);
		for (int i = 0; i < array.length; i++)
			for (int j = 0; j < array.length; j++)
			{
				temp.add(array[i][j]);
			}
		Object[] t = new Object[temp.size()];
		for (int i = 0; i < t.length; i++)
			t[i] = temp.get(i);
		return t;
	}
}
