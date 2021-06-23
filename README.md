# MyJavaPractice

package com.JavaPractice;

ublic class Main {

    public static void main(String[] args) {

    }

    public void StudentGrades() {
        int x = 92;
        if (x > 100) {
            System.out.println("You have an A+.");
        } else if (x < 100 && x >= 94) {
            System.out.println("You have a A");
        } else if (x >= 90 && x < 94) {
            System.out.println("You have an A-");
        } else if (x < 90 && x >= 87) {
            System.out.println("You have a B+");
                System.out.println("You have an B.");
        } else if (x >= 87 && x < 83) {
                System.out.println("You have an B-");
        } else if (x < 80 && x >= 83) {
                System.out.println("You have a C+");
        } else if (x >= 77 && x < 80) {
            System.out.println("You have an C");
        } else if (x < 73 && x >= 77) {
            System.out.println("You have a C-");
        } else if (x >= 70 && x < 73) {
            System.out.println("You have an D+");
        } else if (x < 67 && x >= 70) {
            System.out.println("You have a D");
        } else if (x >= 63 && x < 67) {
            System.out.println("You have an D-");
        } else if (x < 60 && x >= 63) {
            System.out.println("You have a F");

        }
    }
}
