import 'dart:io';

void main() {
  print('# Batch 63 will go a tour after final exam #');
  print('Now lets collect the tour fee.');
  print('Enter tour sport:');
  String? sport = stdin.readLineSync();

  if (sport == 'Shajek') {
    print('Enter your budget');
    int? budget01 = int.tryParse(stdin.readLineSync() ?? '');
    if (budget01 != null && (budget01 == 8000 || budget01 > 8000)) {
      print('Lets go to shajek');
    } else {
      print('Sorry... your budget is insufficient');
    }
    print('Tour fee was:8000 taka');
  } else if (sport == 'Sitakundo') {
    print('Enter your budget:');
    int? budget02 = int.tryParse(stdin.readLineSync() ?? '');
    if (budget02 != null && (budget02 == 2500 || budget02 > 2500)) {
      print('Lets go sitakundo');
    } else {
      print('Sorry... your budget is insufficient');
    }
    print('Tour fee was:2500 taka');
  } else if (sport == 'Sylhet') {
    print('Enter your budget:');
    int? budget03 = int.tryParse(stdin.readLineSync() ?? '');
    if (budget03 != null && (budget03 == 5000 || budget03 > 5000)) {
      print('Lets go Sylhet');
    } else {
      print('Sorry... your budget is insufficient');
    }
    print('Tour fee was:5000 taka');
  } else if (sport == 'Bandorban') {
    print('Enter you budget:');
    int? budget04 = int.tryParse(stdin.readLineSync() ?? '');
    if (budget04 != null && (budget04 == 10000 || budget04 > 10000)) {
      print('Lets go Bandorban');
    } else {
      print('Sorry.... your budget is insufficient');
    }
    print('Tour fee was:10000 taka');
  } else {
    print('I am not interested for this tour....THANK YOU');
  }
}
